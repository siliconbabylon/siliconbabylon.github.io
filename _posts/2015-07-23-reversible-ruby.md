---
layout: post
title: Reversible Ruby
author: Ben Miller
tags: code ruby
category: programming
---

The other day I was chatting about what alien programming languages might look like, and one of the features I thought it might have would be reversability, or the property of being syntactically correct (and hopefully still useful) when interpreted in reverse. As a proof-of-concept I tried to write someting reversible in ruby and this is what I came up with:

`code = "stup = stup; puts stup; puts = puts"`

so now `eval code` and `eval code.reverse` are both syntactically sound, though all they do is print `nil` to string. What made me think of this was Bach's [Crab Canon](https://www.youtube.com/watch?v=xUHQ2ybTejU) which can be played in reverse (and so many other ways). Also, assigning a new variable to itself is a ruby [wat](https://www.destroyallsoftware.com/talks/wat). The palindromic approach seemed the easiest way, though exploring non-palindromic reversible code seems like a challenging next step. Also defining requirements for reversible code would be nice because technically `p p` is also reverse interpritable. I'm not entirely sure whats happening when `puts = puts`, will need to look into that further.

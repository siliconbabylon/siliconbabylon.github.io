---
layout: post
title: Winter Humidity
author: Ben Miller
tags: hvac environment energy
category: technology
---

### Intro
Well, I was wrong. Humidity became an issue, but during winter. Here's what things looked like during a typical week in November of 2021.
![Example week November 2021](/images/humidity_2021_week.png){: style="width:100%" }
Relative humidity is in the high 60s to low 70s while the thermostat was mostly kept at 63F during the day. A brief web search indicates the upper bound for indoor RH is 50 or 60, but as our pals at energy star [indicate](https://www.energystar.gov/products/appliances/dehumidifiers/dehumidifier_basics#:~:text=The%20optimum%20RH%20level%20for,RH%20to%20prevent%20window%20condensation.), 40% is best for keeping condensation off the windows. And we had a lot of that. To the point we were getting mildew on the window frames.

### Dehumidification options
Our HVAC system is a bit long in the tooth, so having an inline dehumidifier seemed expensive and might get replaced in the near future. Similarly, a [HRV](https://en.wikipedia.org/wiki/Heat_recovery_ventilation) would be dandy since it would bring it bring it outside [winter air](https://www.energyvanguard.com/blog/cold-air-is-dry-air/), and disposing of the stale humid indoor air. If we keep a ducted system once this one gives up the ghost, I'll be sure to ask for one but for now too expensive. That leaves us with standalone units. My wife didn't want a loud machine running and I wasn't particularly enthused about buying another potentially short-lived refrigerant-based devise (looking at you crappy Samsung fridge). In a previous dwelling our windowless jack-and-jill bathroom had all sorts of condensation issues, which were mitigated by small [thermoelectric](https://en.wikipedia.org/wiki/Thermoelectric_cooling#Consumer_products) dehumidifier with a humidistat. But it was noisy using a small computer fan to blow air across the heating and cooling fins, and didn't seem to scale up to the 1200 square feet of the house. That kind of left me with one option: Rotary desiccant!

### Rotary desiccant dehumidification to the rescue
It's the neatest thing! While compressor dehumidifiers are more performant at warmer temps, as it gets colder the performance decreases and desiccant tech catches up. The only moving parts in the desiccant dehumidifier are centrifugal fans and a rotating disc of desiccant material (more on that later), hence its fairly quiet. Another circumstantial boon is that it produces quite a of heat as a byproduct, which is doubly welcome in the winter thanks to solar power and a generous net metering agreement. So we're dehumidifying and offsetting warmth which would otherwise be produced by our gas furnace. In the end I opted for this one, the [Ivation 19 pint](https://www.ivationproducts.com/products/ivation-19-pint-small-area-desiccant-dehumidifier-compact-and-quiet-with-continuous-drain-hose-for-smaller-spaces-bathroom-attic-crawlspace-and-closets-for-spaces-up-to-410-sq-ft), aka IVADDH09.

### IVADDH09 review
Straight to stats! measured @ 61F, 60% RH

|     | low (400 Watts) | high (686 Watts)
| ----------- | ----------- |
| Performance (liters/kilowatt-hour)      | 0.5        | 0.51
| Throughput (liters/hour)   | 0.2        | 0.35

I was surprised to see that performance remained the same between the two settings. Needless to say, low is much quieter so I've kept it at that setting. There have also been suggestions online that only running low will extend the lifetime of the device, since on high the desiccant is being blasted with a lot more heat and undergoes more extreme thermo-cycling. I also have it on the same breaker circuit as another space heater, but it hasn't tripped yet on low. Emptying the bucket is easy, though there is an option for drainage hose. While the controls are simple enough, I'm still partial to analog controls since they seem more resilient to moisture and temperature swings. Maybe once every few days I'll run into an error where it displays `Fn` instead of the humidistat value and just blows cold air. A quick jiggle of the device fixes it. Jury is still out on overall longevity, as its only been truly pressed into service this winter so far.


### Results

![Example week November 2022](/images/humidity_2022_week.png){: style="width:100%" }

A much better humidity profile, hovering around 50%. Anecdotally, there's been much less condensation on the windows. The thermostat taking the humidity measurements is quite far from the dehumidifier (a hallway and two rooms over). The dehumidifier lives by the central air conditioning's supply register, which is configured to recirculate air for at least 5 minutes per hour. This mighty machine, despite being rated for only 410 square feet is managing to tame the dampness.

### Final thoughts

 Some confounding issues with the data is that we finally installed a vent in the master bath, decreasing the overall moisture load. The midnight spike of the dishwasher finishing it's cycle often quite pronounced. When the dehumidifier starts after idling for a while, it has a distinct smell that I can only describe as kiln-y. Or like a clay roof-tile dying in the sun after a rain. It's the [Zeolite](https://en.wikipedia.org/wiki/Adsorption#Zeolites). I'm curious about whether the air is being purified as well by the dehumidifier.

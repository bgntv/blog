---
layout: post
title: Risk Assessment Score
date: 2022-12-19
category: updates
---

Score assessment using the Twitch API

Abstract
Many portfolio management systems and banks assess risk with long term engagement and activity of the users. However, these institutions have a give and take loop: users would want to best scores hence it acts as an incentive to get the lowest risk, or best score. This model would create biased results if used if this scenario because in this case there’s no incentive.

Main risk score would be calculated based on whether in the long term, user’s viewership has increased or remained stable(above a minimum threshold).

* I.e score index = multiplier*(change in viewership) for a viewer uptick
* score index = multiplier*(difference of viewership from threshold) for stable viewership

This model,however, presents another requirement: predicting variations from trend line.

Just because the viewership is rising, or is stable, doesn’t mean it will continue that trajectory in the future. Similarly, if a channel is failing, there’s still possibility that it will rise up in the future.

All the methods described above work in theory but there isn’t an application or a working prototype for this. It should work well in practice too because most of this has been adapted from real risk assessment systems.
---
layout: post
title: Risk Assessment Score
date: 2022-12-19
category: updates
---

Analyzing viewership stats for scoring

Abstract 

Portfolio management systems and banks assess risk using long-term engagement data and the activity of each user. The problem with these institutions is that there is a give-and-take loop: users want to earn the highest scores, so there is an incentive to earn the lowest risk. This model would create biased results if used in this scenario because in this case there’s no incentive.

In general, the risk score would be calculated based on whether in the long term, the user's viewership has increased or remained stable (above a minimum threshold).

* I.e 
  * score index = multiplier*(change in viewership) for a viewer uptick
  * score index = multiplier*(difference of viewership from threshold) for stable viewership

However, this model requires another requirement: predicting variations from the trend line.

While viewership may have been rising or may be stable, it does not mean that the trend will continue. Similarly, if a channel is failing, there’s still a possibility that it will rise in the future.

Despite the fact that all the methods outlined in this post work, in theory, there is neither a working prototype nor an application for them. Because most of this has been adapted from real-life risk assessment systems, it is likely to work well in practice as well.

![rating.png](/assets/rating.png)
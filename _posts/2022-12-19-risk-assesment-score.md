---
layout: post
title: Risk Assessment Score
date: 2022-12-19
category: updates
---


Why do we need a risk assessment score?

A risk assessment score is a numerical value that is used to assess the level of risk associated with a particular situation or activity. It is often used to help identify the potential consequences of an action or event, and to determine the likelihood that it will occur. This information can then be used to make informed decisions about how to proceed, and to take appropriate measures to mitigate or eliminate the identified risks.

There are many different ways to calculate a risk assessment score, and the specific method used will depend on the context in which it is being applied. However, the basic principle is to identify the potential risks associated with a particular situation, and to assign a numerical value to each risk based on its likelihood and potential impact. The resulting score can then be used to prioritize risks and to guide the development of a risk management plan.

A risk assessment score can be used in a variety of contexts, including business, finance, and healthcare. By quantifying the potential consequences of a risk, a risk assessment score allows organizations to allocate resources and make informed decisions about how to proceed. It can also help to identify and track trends over time, which can be useful for identifying patterns and making long-term plans.

Within the following example, the goal is to develop an internal tool to help us evaluate the likelihood and potential impact of new live-streaming partners/content creators within the platform.

It's designed to help prioritize risk and determine the appropriate course of action to manage and or mitigate any risk associated with the content produced by each user.


Abstract: Analyzing viewership stats for scoring

Portfolio management systems and banks assess risk using long-term engagement data and the activity of each user. The problem with these institutions is that there is a give-and-take loop: users want to earn the highest scores, so there is an incentive to earn the lowest risk. This model would create biased results if used in this scenario because in this case there’s no incentive.

In general, the risk score would be calculated based on whether in the long term, the user's viewership has increased or remained stable (above a minimum threshold).

* I.e 
  * score index = multiplier*(change in viewership) for a viewer uptick
  * score index = multiplier*(difference of viewership from threshold) for stable viewership

However, this model requires another requirement: predicting variations from the trend line.

While viewership may have been rising or may be stable, it does not mean that the trend will continue. Similarly, if a channel is failing, there’s still a possibility that it will rise in the future.

Despite the fact that all the methods outlined in this post work, in theory, there is neither a working prototype nor an application for them. Because most of this has been adapted from real-life risk assessment systems, it is likely to work well in practice as well.

![rating.png](/assets/rating.png)
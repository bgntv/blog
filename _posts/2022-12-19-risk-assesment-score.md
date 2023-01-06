---
layout: post
title: Risk Assessment Score Using Viewership Stats
date: 2022-12-19
category: updates
---


**Why do we need a risk assessment score?**

A risk assessment score is a numerical value that is used to assess the level of risk associated with a particular situation or activity. It is often used to help identify the potential consequences of an action or event, and to determine the likelihood that it will occur. This information can then be used to make informed decisions about how to proceed, and to take appropriate measures to mitigate or eliminate the identified risks.

There are many different ways to calculate a risk assessment score, and the specific method used will depend on the context in which it is being applied. However, the basic principle is to identify the potential risks associated with a particular situation, and to assign a numerical value to each risk based on its likelihood and potential impact. The resulting score can then be used to prioritize risks and to guide the development of a risk management plan.

A risk assessment score can be used in a variety of contexts, including business, finance, and healthcare. By quantifying the potential consequences of a risk, a risk assessment score allows organizations to allocate resources and make informed decisions about how to proceed. It can also help to identify and track trends over time, which can be useful for identifying patterns and making long-term plans.

**Benefits of using risk assessment scores include:**

 1. Identifying and prioritizing potential risks: Risk assessment scores can help organizations identify and prioritize potential risks based on the likelihood and impact of those risks. This can help organizations allocate resources and take proactive steps to mitigate or manage those risks.

 2. Supporting decision-making: Risk assessment scores can provide a quantitative basis for decision-making, helping organizations make informed choices about how to allocate resources, prioritize projects, and allocate funds.

 3. Improving risk management processes: By regularly assessing and tracking risks, organizations can identify trends and patterns that can help them improve their risk management processes over time.

 4. Enhancing communication: Risk assessment scores can provide a common language for discussing and communicating about risks, which can help facilitate communication and collaboration within and between organizations.

 5. Facilitating compliance: In some cases, risk assessment scores may be used to demonstrate compliance with regulatory requirements or industry standards. 

**Analyzing viewership stats for risk scoring**

There are a number of ways to analyze viewership statistics for scoring purposes. Here are a few things you might consider:

 1. Average viewership: This is the most basic measure of viewership and can be calculated by dividing the total number of views by the number of episodes or pieces of content.

 2. Viewership over time: It can be useful to plot viewership over time to see how it has changed over the course of a     season or series. This can help identify trends and patterns in viewership.

 3. Demographic breakdown: Viewership data can be analyzed by demographic to see which age groups, gender, or other 
  demographic groups are watching the most.

 4. Geographical data: It can be interesting to see where the majority of viewership is coming from, and whether there are 
  any regional trends or differences in viewership.

 5. Comparison to competitors: Viewership data can be compared to that of competitors to see how a show or series is 
  performing relative to others in its market.

 6. Social media engagement: The level of social media engagement (such as likes, comments, and shares) can be a useful 
  indicator of how much a show or series is resonating with viewers.

There are many other factors that could be considered when analyzing viewership data, and the specific approach will depend on the goals of the analysis and the data that is available.

The objective was to design a scoring system to help us evaluate risk against new partners. 

Our goal is to develop an automated internal scoring tool to help us evaluate the likelihood and potential impact of new live-streaming partners/content creators within our platform using thier existing streaming platforms viewership stats. 

It's designed to help prioritize risk and determine the appropriate course of action to manage and or mitigate any risk associated with the content produced by each user.

**Summary**

Portfolio management systems and banks assess risk using long-term engagement data and the activity of each user. The problem with these institutions is that there is a give-and-take loop: users want to earn the highest scores, so there is an incentive to earn the lowest risk. This model would create biased results if used in this scenario because in this case there’s no incentive.

In general, the risk score would be calculated based on whether in the long term, the user's viewership has increased or remained stable (above a minimum threshold).

* I.e 
  * score index = multiplier*(change in viewership) for a viewer uptick
  * score index = multiplier*(difference of viewership from threshold) for stable viewership

However, this model requires another requirement: predicting variations from the trend line.

While viewership may have been rising or may be stable, it does not mean that the trend will continue. Similarly, if a channel is failing, there’s still a possibility that it will rise in the future.

Despite the fact that all the methods outlined in this post work, in theory, there is neither a working prototype nor an application for them. Because most of this has been adapted from real-life risk assessment systems, it is likely to work well in practice as well.

![rating.png](/assets/rating.png)

**Notice:** Mobile Users can access the full articles using the following links.

  * <a href="https://drive.google.com/file/d/1IyTMYQySqDn5An2isZRsKA0D2evAnRpi/view?usp=share_link" target="_blank">Risk Score Assessment Part 1</a>

  * <a href="https://drive.google.com/file/d/1cyyl-onJ-itg5R7YVI05-IyGruUYWj2j/view?usp=share_link" target="_blank">Risk Score Assessment Part 2</a>


<!-- https://stackoverflow.com/questions/56961472/jekyll-wont-render-text-after-pdf-is-embedded-into-an-article -->

<object 
  data="/assets/RiskScoreP1.pdf" 
  width="750" 
  height="1000" 
  type="application/pdf"></object>


<object 
  data="/assets/RiskScoreP2.pdf" 
  width="750" 
  height="1000" 
  type="application/pdf"></object>


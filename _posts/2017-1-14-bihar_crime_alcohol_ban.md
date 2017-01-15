---
title: "Alcohol Ban, and crime in Bihar: Not much to see here"
layout: single
tags: dev
excerpt: "Alleged spike in crime following alcohol ban is largely due to seasonality in crime figures."
---

## The Alcohol Ban and Crime figures in Bihar

[Placeholder] Alcohol ban in Bihar. Reception at the time. 

### The tide turns
A few days back, a couple of newspapers carried a report based on this [article](http://www.indiaspend.com/cover-story/270-days-after-bihar-liquor-ban-major-crimes-up-13-40759) about how crime rates in Bihar had increased steadily following the alcohol ban. I found this puzzling and decided to dig in deep. 

The key claim of rising crime post the April ban of alcohol was the following graph, generated from figures obtained from the Bihar police. The author compared the total crime figure of 14,279 in April, 2016 to 16,153 in October, 2016 to arrive at a difference of around 13% which was recorded as the increase in crime post the alcohol ban.

![Bihar Crime Report]({{ site.url }}/assets/images/Bihar_Crime/Bihar_Crime_Report.png)

Before we rule this shift as the result of the alcohol ban, we need to have a sense of what the crime figures for October, 2016 would have been if the ban had not happened. A rough and dirty method to get this sense is to look at how crime figures in Bihar behaved before the ban.

## Seasonality of crimes
The following figure plots the monthly figures for different types of crimes for the period 2010-2016, October. We notice straight away that the graph is extremely unstable with several peaks and valleys. Such peaks and valleys are characteristic of data with a strong seasonal changes- imagine a graph of day-time temperatures at a location over a year. 

To verify this hypothesis of seasonality I prepared the following graphs of crime by each month.

<img src="{{ site.url }}/assets/images/Bihar_Crime/Crimes_per_year.png" height="434" width="600">

![Crimes by the year]({{ site.url }}/assets/images/Bihar_Crime/Crimes_over_years.png)

![Thefts by month of the year]({{ site.url }}/assets/images/Bihar_Crime/Thefts_by_month.png)

![Riots by month of the year]({{ site.url }}/assets/images/Bihar_Crime/Riots_by_month.png)

![Burglaries by month of the year]({{ site.url }}/assets/images/Bihar_Crime/Burglaries_by_month.png)

![Kidnappings by month of the year]({{ site.url }}/assets/images/Bihar_Crime/Kidnappings_by_month.png)

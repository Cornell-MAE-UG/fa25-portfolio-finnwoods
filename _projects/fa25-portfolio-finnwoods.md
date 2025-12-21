---
layout: project
title: Analysis of a Heat Exchanger
description: Class project analyzing a heat exchanger under different operating conditions
technologies: 
image: /assets/images/he-lab-heater.png
---
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;   

## Description

For this project I analysed the input and output temperatures of a heat exchanger under different operating conditions. The two operating conditions that I altered were the flow rate through the heat exchanger and whether the heat exchanger was running in counter flow or parallel flow. 

The Experiment setup included one heat exchanger, two pumps, and four tubs (one with hot water warmed by an immersion heater and one insulated containing cold water). In each trial a flow rate was chosen for both of the pumps (fast or slow) and they were attached to the heat exchanger in parallel flow or in counter flow. 


![Heat Exchanger]({{ "assets/images/he-lab-heater.png" | relative_url }}){: .large-inline-image-l}  
&nbsp; 
&nbsp; 
&nbsp; 
&nbsp; 
&nbsp; 
&nbsp; 

Here are the system diagrams of counter flow and parallel flow:  

![Counter Flow]({{ "assets/images/counter-flow.png" | relative_url }}){: .inline-image1-l}  

![Parallel Flow]({{ "assets/images/parallel-flow.png" | relative_url }}){: .inline-image-r}  

## Analysis

The following data was collected

|Low/High Flow &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;|Counter/Parallel Flow  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;| Hot Temp in &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;| Cold Temp in &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;| Hot temp out &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;| Cold temp out &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;|
|---|---|---|---|---|---|
|Low|Counter|35.0C|11.6C|18.6C|23.3C|
|Low|Parallel|35.0C|11.3C|26.3C|22.3C|
|High|Counter|35.5C|11.0C|22.5C|24.5C|
|High|Parallel|36.0C|10.0C|24.7C|22.3C|

&nbsp;

In each experiment it was difficult to make sure that the initial hot temperature and the initial cold temperature were the exact same every time, however, I tried to make sure the difference in temperature between the two sources stayed at about 25 degrees celsius. 

It is important to keep the temperature difference relatively similar across trials because the way this heat exchanger transfers energy is through conduction where the heat transferred is proportional to the temperature difference at any given instant. 

The goal of a heat exchanger is often to transfer the largest amount of energy from a hotter substance to a cooler substance so I will compare the change in energy of the initially hot water and the change in energy of the initially cold water. 

For water in our temperature range (36C - 10C) it can be modeled as an incompressible substance because its volume doesn't change much with pressure and all measurements are being taken at typical atmospheric pressure. 
This means delta U = delta H = C delta T, where C is the specific heat of 4.18 kJ/(kg K)

Plugging in the final and initial temperatures we find

|Flow &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;|Hot &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;|Cold &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;|Average energy transfer &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;|
|---|---|---|---|
|Low Counter Flow|-68.6kJ/kg|69.8kJ/kg|69.2kJ/kg|
|Low Parallel Flow|-36.4kJ/kg|46.0kJ/kg|41.2kJ/kg|
|High Counter Flow|-54.34kJ/kg|56.43kJ/kg|55.4kJ/kg|
|High Parallel Flow|-47.0kJ/kg|51.4kJ/kg|49.2kJ/kg|

&nbsp;

If we analyse the effect of counter flow vs parallel flow we can see that the energy changes are greater for counter flow than parallel flow when accounting for the flow speed.
For low flow speeds we see that the energy transfer rate for counter flow is (69.2kJ/kg)/(41.2kJ/kg) *100% = 168% of the parallel flow energy transfer rate
For high flow speeds we see that the energy transfer rate for the counter flow is (55.4kJ/kg)/(49.2kJ/kg) *100% = 113% of the parallel flow energy transfer rate
This demonstrates that counter flow is more efficient for energy transfer compared to parallel flow. 

If we analyse the effect of high flow rate vs low flow rate we see that the energy changes are not consistent across different flow types.
For counter flow we see that the energy transfer rate for the low flow rate is (69.2kJ/kg)/(55.4kJ/kg) *100% = 125% of the higher flow rate
For parallel flow we see that the energy transfer rate for the low flow rate flow is (41.2kJ/kg)/(49.2kJ/kg) *100% = 84% of the higher flow rate
This indicates that flow rate may not be very important for energy transfer in this specific heat exchanger. Theoretically energy transfer should be greater for lower flow rate because there is more time of the water to transfer heat. One reason for this discrepancy may be that the initial temperature difference between the hot and cold water was not exactly 25 degrees celsius every time. For the low flow parallel experiment the temperature difference was 23.7 degrees Celcius, but it was a little higher for the high flow parallel experiment with a difference of 26 degrees Celcius. If I were to conduct this experiment again I would make sure that the temperature differences were as consistent as possible to double check the accuracy of this data. 


Another important thing to note is that in every trial the energy gained per unit of mass is always higher for the initially cold water compared to the initially hot water. Because the pumps for the hot and cold water were set to the same speed this means that our system gained energy. This energy gain is likely due to the heat exchanger not being completely adiabatic so there was heat transfer from the outside world into the heat exchanger which got transferred to the water. If the water was gaining energy, then you would expect the heat exchanger to lose energy by cooling down. And indeed this was the case. The heat exchanger felt cold to the touch after each trial, and after the last trial we measured the temperature at several different points on the heat exchanger finding temperatures between 16.1C and 20C.






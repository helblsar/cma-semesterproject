# Proposal for Semester Project

**Patterns & Trends in Environmental Data / Computational Movement
Analysis Geo 880**

| Semester:      | FS22                                   |
|----------------|--------------------------------------- |
| **Data:**      | Wild Boar Movement Data                |
| **Title:**     | A comparison of the behaviour of female|
|                |  and male wild boars after an encounter|
|                |   with the "Wildschweinschreck"        |
| **Student 1:** | Sarah Helbling                         |


## Abstract 
Throughout the year female and male wild boars spend rather little time together – young males leave the sounder between their 2nd and 4th year and only during the mating season from November to December adult, male wild boars will join the sounder of females. With such different social behaviours of males and females, it would be interesting to see, if their behaviours in the face of a deterrence differ.

## Research Questions
Are the movement patterns after an encounter with a deterrence of female and male wild boars different (flight distance, speed during the escape, returning to the field yes/no,...)?


## Results / products
Considering the socials groups in which the females are usually living in, it could be suspected, that they wouldn’t flee as far as males. Therefore, female wild boars might show quite different movement patterns after encountering a deterrence. 

 Process - Idea
1. buffer deterrence locations (lat, lon) with buffer= 1(?)km 
2. join/ union of all boars with the buffered deterrence locations
3. filtering boars by date when deterrence was active (filter "boars" data for dates between datum_on / datum_off )
4. visualize coincidences when boars were in close range of the active deterrence  
5. calculate escape distance, speed 
6. try to figure out if/how often/ after how much time (deterrence still active?) a boar returns to a field/ location it was deterred from
7. statistical analysis to find out if the before mentioned things differ between females and males


## Data
Data used: wild boar and deterrence data from the CMA library 


## R concepts
Which R concepts, functions, packages will you mainly use. 
library(ComputationalMovementAnalysisData)
library(dplyr)
library(lubridate)
library(sf)
library(ggplot2)
What additional spatial analysis methods will you be using? 


## Risk analysis
What could be the biggest challenges/problems you might face? What is your plan B? 
Looking at my preliminary process idea a lot of details of how I will do things are still unclear.
I will probably encounter a lot of challenges as I go (considering my limited knowledge on R), but until I encounter them there is no telling how much of a risk they will pose to answering the research question.


## Questions? 
Which questions would you like to discuss at the coaching session? 
- Is there more data on the tracked individuals (such as age)? (maybe research question could be extended to include not only sex, but also age/hierarchical status of the animals)
- Do I have to take features of the deterrence itself (lautstraerke, installations hoehe, intervall) into account? 



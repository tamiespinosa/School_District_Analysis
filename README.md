# School_District_Analysis
Module 4 homework

## Table of Contents
- [Overview of Project](#OverviewProject)
  * [Purpose](#purpose)
- [Results](#Results)
- [Summary](#Summary)
- [Resources](#Resources)

 
## <a name="OverviewProject"></a>Overview of Project

A school distric wants an analysis of their standarized test outcomes for math and reading for various high schools using the student's math and reading score data and additional school data such as school size and budget [[3]](#3)[[4]](#4). The data was analyzed to find trends in school performance [[2]](#2). After the first analysis was performed, the data for the Thomas High School 9th grade was brought into question due to potential inconsistances [[1]](#1). The effects of this data removal will be explained. 

### <a name="purpose"></a>Purpose

 The analysis gathered the following information for data excluding and including Thomas High School 9th grade [[1]](#1)[[2]](#2).
 
* A high-level snapshot of the district's key metrics
* An overview of the key metrics for each school
* Tables presenting each of the following metrics:
  - Top 5 and bottom 5 performing schools, based on the overall passing rate
  - The average math score received by students in each grade level at each school
  - The average reading score received by students in each grade level at each school
  - School performance based on the budget per student
  - School performance based on the school size 
  - School performance based on the type of school
 
 In this report, we will discuss the differences in results from one analysis to the other.
 
## <a name="Results"></a>Results



* How is the district summary affected?

The summary for the district indicates that when excluding the Thomas Highschool 9th Grade from the overall data, the passing percentages are slightly reduced. The overall passing percentage was reduced by a tenth of a percent. The math and reading passing percent were reduced by two and three tenths of a percent respectively. This shows that the Thomas High School 9th grade testing scores were making the percentages marginally higher.   

<p align="center"> <img src="Resources/Pictures/District_Summary_with.png" width ="70%" alt="District_Summary_with"> </p>
<p align="center"> Figure 1: District Summary Including THS 9th Grade</p> 

<p align="center"> <img src="Resources/Pictures/District_Summary_without.png" width ="70%" alt="District_Summary_without"> </p>
<p align="center"> Figure 2: District Summary Excluding THS 9th Grade</p> 

* How is the school summary affected?

<p align="center"> <img src="Resources/Pictures/Per_School_Metrics_with.png" width ="70%" alt="Per_School_Metrics_with"> </p>
<p align="center"> Figure 3: School Summary Including THS 9th Grade</p> 

<p align="center"> <img src="Resources/Pictures/Per_School_Metrics_without_Corrected_THS.png" width ="70%" alt="Per_School_Metrics_without_Corrected_THS"> </p>
<p align="center"> Figure 2: School Summary Excluding THS 9th Grade - THS only</p> 


* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

The 9th graders' math and reading scores did not affect Thomas High School's ranking with respect to the other schools. In the analysis including and excluding the data, Thomas High School came second in both school rankings. The overall passing percentage is reduced from 90.94% to 90.63% from when including to when excluding the 9th graders' scores. This drop was not significant tnough to move Thomas High School's place. 

<p align="center"> <img src="Resources/Pictures/Top_Schools_with.png" width ="70%" alt="Top_Schools_with"> </p>
<p align="center"> Figure 3: Top Schools Including THS 9th Grade</p> 

<p align="center"> <img src="Resources/Pictures/Top_Schools_without.png" width ="70%" alt="Top_Schools_without"> </p>
<p align="center"> Figure 4: Top Schools Excluding THS 9th Grade</p> 

* How does replacing the ninth-grade scores affect the following:

  - Math and reading scores by grade
  
The only change for this part of the analysis is that the math and reading for Thomas High School 9th grade is changed from a value, to nan. All the other values remain unchanged. 

  - Scores by school spending, school size and school type

The results for scores by school spending, size and type were slightly changed in the categories that Thomas High School belonged in when removing the 9th grade data. But the changes were so insignificant, that when rounding up for formatting purposes the tables for school spending, school size and school type looked identical with and eithout the 9th grade data. 

 

## <a name="Summary"></a> Summary

Generally speaking, the effects of excluding the Thomas High School 9th grade data were insignificant. At a district level the ranking of Thomas High School did not change, . At the school level, . Overall although the 9th grade data did enhance the passing percentages, the effects were small. 

## <a name="Resources"></a>Resources

<a name="1">[1]</a> [School Distric Analysis without Thomas High School 9th Grade](https://github.com/tamiespinosa/School_District_Analysis/blob/d230e051353b12aff7ec079be477609ec4f7bb8c/PyCitySchools_Challenge.ipynb)

<a name="2">[2]</a> [School District Analysis](https://github.com/tamiespinosa/School_District_Analysis/blob/d230e051353b12aff7ec079be477609ec4f7bb8c/PyCitySchools.ipynb)

<a name="3">[3]</a> [School Data](https://github.com/tamiespinosa/School_District_Analysis/blob/d230e051353b12aff7ec079be477609ec4f7bb8c/Resources/schools_complete.csv)

<a name="4">[4]</a> [Student Data](https://github.com/tamiespinosa/School_District_Analysis/blob/d230e051353b12aff7ec079be477609ec4f7bb8c/Resources/students_complete.csv)

[5] https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax


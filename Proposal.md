---
title: "Capstone Proposal Markdown"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## What is the problem you want to solve?

A school district recently implemented a pilot model of teacher assessment to measure teacher's impact on student's learning. This model is implemented by school leaders(principals & asst. principals. After its first implementation, the school district conducted a survey among school leaders to measure effectiveness of the assessment program. In a one-page memo to the superintendent, I need to outline the main findings and headlines of this survey(raw data), and offer recommendations based on the findings. 
 
## Who is your client and why do they care about this problem? In other words, what will your client DO or DECIDE based on your analysis that they wouldn’t have otherwise?

* My client is the Superintendent of a school district. The superintendent wants to measure teachers' impact on student outcomes through this new teacher assessment, which is executed by the school leaders(principals & asst. principals). 
* The raw data(survey) reflects school leaders’ feedback and satisfaction levels on this new teacher assessment. Based on my analysis of the survey, the superintendent may consider changes to the teacher assessment and its implementation so it will better reflect and improve teachers’ instructional performance. 
 
## What data are you going to use for this? How will you acquire this data?

The survey **dataset**(raw data) is in the form of an excel file, which can be downloaded at [Yumi's dataframe](https://github.com/yumi2014/Capstone/blob/master/dataframe.csv)  I was asked to convert it to a csv file to import to RStudio where I can visualize each data component.

## In brief, outline your approach to solving this problem (knowing that this might change later). 

Firt, I'll use dplyr commands to the raw data to identify key questions & answer patterns. Then I'll use ggplot to visualize the answer patterns as indicators of 
survey analysis.

## What are your deliverables? Typically, this would include code, along with a paper and/or a slide deck.
There will be an introductory and visual charts, using a slide deck for 10-15 min. 
 
This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.



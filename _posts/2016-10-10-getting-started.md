---
layout: post
title: "Projects"
author: "Mauricio Vazquez Moran"
categories: documentation
tags: [documentation,sample]
image: city-1.jpg
---

# Analysis of the virality of femicides on social networks "Lima Buendía"

**By Mauricio Vazquez Moran,
  Jr. Data Analyst of the research project "Lima Buendía".**
 
### Introduction

On March 25, 2015, there was a change in the pronouncements of the Supreme Court of the Nation. The first pronouncement, related to femicide, of said institution had been given. The Mariana Lima Buendia sentence allowed, for the first time in the history of Mexican justice, that investigations related to the violent homicide of women be analyzed from a gender perspective. Since then, the situation in national territory has been worrisome. An upward trend is observed year after year. Mexico is experiencing a widespread problem of violence against women. A problem that penetrates society regardless of the socio-economic context. There have been numerous investigations that have analyzed, quantified, and delved into this wave of violence that is flooding our country. However, the phenomenon surprises the more it is studied. In addition, under a digitized era and exacerbated by the mass media, the national situation becomes even more complicated and delicate.

Having said the above, the present analysis was focused on defining and identifying which variables, in social networks, influence a femicide to go viral. Under this task, some questions were proposed. These were essential, as a point of reference, for the correct follow-up and execution of the analysis. From which it results that the following questions were raised: What is virality? What femicides are mentioned on social networks? Is there talk of the same case of femicide for months? Do the local and national media talk about the same cases? Although the analysis raised following these questions as a guide, it is also true that on several occasions they proposed, under certain contexts in social networks, new issues to be analyzed and quantified. In other words, the questions raised led to more questions to answer in order to expand, maximize the findings and correct the course of the investigation.

### Stages

The analysis, for its correct execution, was divided into two main stages. In the first instance, an exploratory analysis of the data provided by the NGO SocialTIC. Deepening and exploring the variables observed in the different data sets, the data was extracted, transformed and loaded so that the models used, later, were the best optimized. Bilaterally, trends and peaks of surface interactivity were sought. Secondly, it focused on a contextual analysis of the publications. Investigating and questioning the digital environment of the publication, the words, phrases and reactions surrounding publications related to particular cases of femicide selected randomly and/or at the suggestion of SocialTIC were analyzed. It should be added that the NGO SocialTIC was actively involved by providing data on the historical, social and chronological context of the data provided for its correct interpretation and management by the group of analysts involved with these stages of the investigation.

### Data Sources

The diversity, in terms of means of propagation for messages, interactions, headlines or publications, on femicides can be very wide in a digitized era. The complexity of finding reliable and truthful sources of information was a huge task. In the same way, the selection of the variables that were analyzed was of the utmost importance for the findings found. Therefore, for a better performance of the analysis, SocialTIC in collaboration with the analysts, selected and extracted relevant information from the following data sources:

* MediaCloud. Open source platform for media analysis. The variables that were selected for the analysis were the date of publication, the headline of the news and the   medium that published it. 145,174 observations from this source of information were recorded.
* Facebook pages. They are commercial accounts created with the aim of being communication channels within the social network. The variables to be analyzed were the     date of the post, the name of the page, the message published and the interaction. 335,653 observations from this source of information were analyzed.
* Facebook groups. They are spaces within Facebook, in which different Facebook users can share information or knowledge. As in the pages, there are the variables of     the publication date of the message, the messages and the interactions. 56,124 observations from this source of information were analyzed.
* Twitter. It is a microblogging service, that is, it allows its users to post short messages of less than 180 characters. The data set is made up of the tweets and     the variables to be analyzed are: date of publication and the message of the tweet. 149,465 observations from this source of information were analyzed.
* Data from the Executive Secretariat of the National Public Security System. The data set is made up of monthly statistics by state of various types of crime           (homicide, femicides, abortions, injuries). The variable that is of interest is type of crime, from which the following crimes are excluded: kidnapping, kidnapping,   corruption of minors, extortion, injuries, other crimes against society and trafficking of minors. 58,880 observations from this data source were analyzed.

It should be noted to the reader that the interaction, in the present analysis, is defined as any action that the user performs with the publication without distinguishing whether it is positive or negative.

### Analysis

#### Stage 1

Stage 1, of this analysis, was made up of analyzing, exploring, visualizing and cleaning the data sets provided by SocialTIC. During this part of the analysis run, attempts were made to provide explanations, either through events or general knowledge social events, for the various spikes in interactions that occurred in the data. It was at this stage when the analysts became familiar with the data, the variables and the construction of bridges that allowed them to relate to each other. In addition, observations were made about the function of each data source. Since each data source is used and designed for a different purpose, the processing of data, obtained from said sources, could not be bilateral between different data sets.

During this stage, a very particular anomaly was detected in the data from the social network Facebook. Coming from the same source of information, the main assumption hanging around was similar messaging behavior and interactions between Facebook Pages and Facebook Groups. However, when exploring the information and quantifying the aforementioned variables, an opposite behavior was observed from 2020 to 2022, as can be seen in graph 1. Pointing out, while Facebook pages grew in terms of the number of messages published on the network, the groups showed a decline in the amount of the same variable over the same period of time. While it is true that the Pages data set was larger, it is also true that their growth trends did not show the same. Consequently, it was an important finding for handling these different data sets. It allowed analysts to make the right assumptions for handling these.

### Stage 2

Once the correct understanding of the data has been overcome. The analysts proceeded to answer the aforementioned questions. Mainly, the analysis focused on understanding which variables played an important role in the chronological durability of a publication related to a particular femicide. Throughout the first stage, it had been observed how ephemeral the virality of the publications was. Therefore, understanding the reasons for this situation was essential for the development of the analysis.

Having said the above, the case of Ingrid Escamilla, which occurred on February 9, 2020, was taken as an example, to delve more deeply into the aforementioned situation. For the practical purposes of this stage of the analysis, the other data sets were left out and only the observations and interactions of the Facebook pages were used. This is because this data set had the minimum amount required to use machine learning models and to be able to potentiate the results with these computational tools. The results obtained were discouraging. As can be seen in graph 2, the virality of the case did not last long during its first year of occurrence. Unfortunately, the models used failed to find what was desired in a case classified as "viral". The finding is based on concluding that given the political conversation in the social networks analyzed and the countless cases of femicides in the country, the cases of feminicides in social networks do not go viral when another case has already occurred and the previous one is being left behind. forgotten by users and pages of social networks.

### Conclusion

The polarization of Mexican society, given the country's political situation, does not allow society to become aware, at least digitally, of the situation of the plague of femicide that the nation is experiencing. The situation, in social networks, has become dehumanizing, to a certain extent, and justice does not reach the victims anywhere. The analysis concludes that the virality in femicides does not compete, mainly, against the political conversation currently observed in the main social networks used by Mexicans. Unfortunately, the victims are forgotten in a morning.

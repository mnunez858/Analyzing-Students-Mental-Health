Mental Health of International Students: A PostgreSQL Data Analysis
This repository contains SQL queries and analysis of data related to the mental health of international students, focusing on whether going to university in a different country affects their mental health. The data used for this analysis is sourced from a Japanese international university's survey conducted in 2018, which was subsequently published in a study approved by several ethical and regulatory boards.

Background
The study found that international students have a higher risk of mental health difficulties compared to the general population. Specifically, it highlighted two key factors: social connectedness (the sense of belonging to a social group) and acculturative stress (the stress associated with adapting to a new culture), which were found to be predictive of depression among international students.

Objective
The objective of this analysis is to explore the provided dataset using PostgreSQL and determine if the findings from the aforementioned study are reflected in the data. Additionally, we aim to investigate whether the length of stay in the host country is a contributing factor to the mental health of international students.

Data Description
The dataset contains the following columns, which may be helpful for the analysis:

inter_dom: Types of students (international or domestic)
japanese_cate: Japanese language proficiency
english_cate: English language proficiency
academic: Current academic level (undergraduate or graduate)
age: Current age of student
stay: Current length of stay in years
todep: Total score of depression (PHQ-9 test)
tosc: Total score of social connectedness (SCS test)
toas: Total score of acculturative stress (ASISS test)

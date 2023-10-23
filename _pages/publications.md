---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

2023
=====

Personalization in Circadian Rhythm-Based Event Scheduling [\[PDF\]](http://mattc1745.github.io/files/Personalization_in_Circadian_Rhythm-Based_Event_Scheduling.pdf)
---

<span font-size:10px>
The human body follows a natural circadian rhythm, influencing sleep timing, cognitive abilities, and physical energy. Many people live contrary to this biological rhythm, leading to reduced cognitive performance and sleep loss, with college students especially vulnerable to these effects. Currently, there are limited technologies that assist with circadian rhythm alignment, despite the potential for health and productivity benefits. This paper investigates the feasibility of circadian-based activity scheduling for college students. We develop three circadian-based activity schedules that are increasingly personalized: (1) common activity timing according to circadian rhythms research, (2) timing curation according to sociodemographic context, and (3) timing adjustment based on individuals’ specific constraints and context. In a three-week study, we explore users’ responses to each scheduling approach and the potential impact on subjective wellbeing and overall performance. Our results show that participants could follow more activity recommendations as the level of personalization increased. Participants who followed the circadian schedules reported significantly improved well-being than others. However, reported wellbeing was not significantly correlated with increased personalization of timings. These observations provide useful insights into design requirements for circadian-aware recommendation systems.

P. Sadekar, J. Baitinger, S. Conway, M. Clark, and A. Doryab, “Personalization in Circadian Rhythm-Based Event Scheduling,” the 2023 Systems and Information Engineering Design Symposium (SIEDS), Apr. 2023.  
</span>

2022
=====

Sounds of Health: Using Personalized Sonification Models to Communicate Health Information [\[PDF\]](http://mattc1745.github.io/files/Sounds_of_Health_Using_Personalized_Sonification_Models_to_Communicate_Health_Information.pdf)
---

<span font-size:10px>
This paper explores the feasibility of using sonification in delivering and communicating health and wellness status on personal devices. Ambient displays have proven to inform users of their health and wellness and help them to make healthier decisions, yet, little technology provides health assessments through sounds, which can be even more pervasive than visual displays. We developed a method to generate music from user preferences and evaluated it in a two-step user study. In the first step, we acquired general healthiness impressions from each user. In the second step, we generated customized melodies from music preferences in the first step to capture participants’ perceived healthiness of those melodies. We deployed our surveys for 55 participants to complete on their own over 31 days. We analyzed the data to understand commonalities and differences in users’ perceptions of music as an expression of health. Our findings show the existence of clear associations between perceived healthiness and different music features. We provide useful insights into how different musical features impact the perceived healthiness of music, how perceptions of healthiness vary between users, what trends exist between users’ impressions, and what influences (or does not influence) a user’s perception of healthiness in a melody. Overall, our results indicate validity in presenting health data through personalized music models. The findings can inform the design of behavior management applications on personal and ubiquitous devices.

M. Clark and A. Doryab, “Sounds of Health: Using Personalized Sonification Models to Communicate Health Information,” Proceedings of the ACM on Interactive, Mobile, Wearable, and Ubiquitous Technologies (IMWUT), vol. 6, no. 4, p. 206:1-206:31, Dec. 2022, doi: 10.1145/3570346.
</span>

2020
===== 

Moving Recursion Out of the RDBMS for Transactional Graph Workloads [\[PDF\]](http://mattc1745.github.io/files/Moving_Recursion_Out_of_the_RDBMS_for_Transactional_Graph_Workloads.pdf)
---

<span font-size:10px>
This paper presents work in progress that focuses on querying transactional graph data that is stored in a relational database system (RDBMS). We focus on transactional workloads where there are frequent insert and update operations. Although these types of workloads are common in social network, scientific, and business applications, much of the prior work has focused on graph analytics workloads where there is little to no change to the data over time. We introduce an approach that combines simple database queries with parallel programming, and compare our approach to the recursive SQL operations that are known to have poor performance. Our initial experiments and results provide guidance for the future directions of this project where we will refine the parallel programing approach and structure of the experiment in order to better compare these two approaches.

C.F. Reilly and M. Clark, "Moving Recursion Out of the RDBMS for Transactional Graph Workloads," The 11th IEEE Ubiquitous Computing, Electronics Mobile Communication Conference (UEMCON), Oct. 2020, p. 0371-0376. doi: 10.1109/UEMCON51285.2020.9298122.
</span>

Analyzing Privacy Practices of Existing mHealth Apps [\[PDF\]](http://mattc1745.github.io/files/Analyzing_Privacy_Practices_of_Existing_mHealth_Apps.pdf)
---

<span font-size:10px>
Given students’ reliance on smartphones and the popularity of mobile health apps, care should be taken to protectstudents’ sensitive health information; one of the major potential risks of the disclosure of this data could be discrimination by insurance companies and employers. We conducted an exploratory study of 197 existing smartphone apps, which included 98 mobile health apps, to study their data collection, usage, sharing, storage and deletion practices. We present our findings from the analysis of privacy policies and permission requests of mHealth apps, and propose the need for a usable health data dashboard for users to better understand and control how their health data is collected, used, shared and deleted.

A. Prasad, M. Clark, H. Nguyen, R. Ruiz, and E. Xiao, "Analyzing Privacy Practices of Existing mHealth Apps," The 13th International Conference on Health Informatics (HEALTHINF), Feb. 2020, p. 563-570. doi: 10.5220/0009059605630570.
</span>

<!-- [Download PDF]() -->

<!-- 
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->

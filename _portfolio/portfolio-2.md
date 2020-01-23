---
title: "Applying Rhetorical Structure Theory to Student Essays for Providing Automated Writing Feedback" 

excerpt: "
**#Natural Language Processing**, **#Feedback Automation**
<br>**#K-12 Writing Education**
<br><br>
In this research, we partner with [Turnitin, Inc.](https://www.turnitin.com/), a language technology company, in an effort to automate the structural feedback for student essays, specifically, for the genre of argumentative writing. This research is funded by NSF and Schimdt Family Foundation.  
<img src="https://kexin-yang.github.io/images/RST_tutor/tree.png?raw=true" alt="Photo" style='width: 650px;'/> "  
collection: portfolio  
---
<br>
<br>
/#Natural Language Processing, /#Feedback Automationsimon
<br>/#K-12 Writing Education

**Duration**: Jul. 2018 - Apr. 2019<br>
**Mentors**: Prof. Carolyn Rose, Prof. Shiyan Jiang 

In this research, we partner with [Turnitin, Inc.](https://www.turnitin.com/), a language technology company, in an effort to automate the structural feedback for student essays, specifically, for the genre of argumentative writing. This research is funded by NSF and Schimdt Family Foundation.  
 
**Background**
 
 While low-level feedback for students' writing has been more successfully automated, it has always been a challenge for AI-based educational systems to give high-level structural feedback on students' essays.
 Part of the reasons are 1) There lacks an accurate way to automatically and accurately detect the high-level structure of students' essays. 2) There is no one-size-fit-all standard or rubrics for what a good structure is like for students' essays.
  
**Our Approach**   
Firstly, to identify the structure of students' essays, we adopted [Rhetorical Structure Theory](https://www.sfu.ca/rst/). Rhetorical Structure Theory (RST) is a linguistics framework, frequently used in information retrieval area, useful for identifying the relation between different Elementary Discourse Unit (EDU). <br>
   <p align="center">
 <img src="https://kexin-yang.github.io/images/RST_tutor/allRelations.png?raw=true" alt="Photo" style="width: 650px;"/>  
</p>

To code the existing students' essays using RST, we make use of the [RSTWeb](https://corpling.uis.georgetown.edu/rstweb/info/), an open source, browser based annotation tool for discourse analyses in Rhetorical Structure Theory. <br>
 <p align="center">
 <img src="https://kexin-yang.github.io/images/RST_tutor/tree.png?raw=true" alt="Photo"/>  
</p>

In the coding process, in an effort to build inter-rater reliability, we developed a flowchart, as well as an annotation guideline (see references). 
 <p align="center">
 <img src="https://kexin-yang.github.io/images/TII_Proj/partFlow.png?raw=true" alt="Photo"/>  
</p>

 <p align="center">
 <img src="https://kexin-yang.github.io/images/TII_Proj/fullFlow.png?raw=true" alt="Photo"/>  
</p>


We also developed an [intelligent tutoring system](https://kxyang.com/portfolio/portfolio-5/) in order to teach novices grasp RST annotation. 


**References**
- Applying Rhetorical Structure Theory to Student Essays for Providing Automated Writing Feedback, Shiyan Jiang, Kexin Yang, Chandrakumari Suvarna, Pooja Casula, Mingtong Zhang, Carolyn Rose, Proceedings of the Workshop on Discourse Relation Parsing and Treebanking 2019. [[PDF]](https://www.aclweb.org/anthology/W19-2720.pdf).
- Guideline and Flowchart for Rhetorical Structure Theory Annotation, Technical Report, Carnegie Mellon University Language Technologies Institute. [[PDF]](https://www.lti.cs.cmu.edu/sites/default/files/Guideline%20and%20Flowchart%20for%20Rhetorical%20Structure%20Theory%20Annotation_2.pdf)

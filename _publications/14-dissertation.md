---
collection: theses
permalink: /publications/14-dissertation

title: "Automated Analysis of Bug Descriptions to Support Bug Reporting and Resolution"
authors: "**Oscar Chaparro**"
venue_key: utd

track: "Dissertation"
pages: 
date: 2019-09-01
doiurl: https://utd-ir.tdl.org/handle/10735.1/7148?show=full

paperurl: /files/14-dissertation.pdf
notes: 
---

**Abstract:** User-written bug descriptions are the main information source for software developers to triage and fix the reported software bugs. Unfortunately, bug descriptions are often unclear, ambiguous, and miss critical information. In consequence, developers spend excessive time and effort triaging and solving the bugs, and, in many cases, they are unable to reproduce the problems, let alone fix the bugs in the code. Current bug reporting technology, which is mostly passive and does not verify the information provided by the users, provides little help in collecting high-quality bug information and improving the quality of bug descriptions. 

This research aims at improving: (1) the quality of bug descriptions, and (2) the accuracy of bug resolution tasks that rely on bug descriptions. The approach towards achieving our goals is the automatic analysis of bug descriptions in combination with software analysis techniques. In the context of our goals, we focus on two bug resolution tasks, namely, automated duplicate bug report detection and bug localization in source code. In addition, we focus on analyzing the main information in bug descriptions, namely, the unexpected software behavior (i.e., the observed behavior), the steps to reproduce such (mis)behavior (i.e., the steps to reproduce), and the normal software behavior (i.e., the expected behavior). 

In this dissertation, we propose automatic techniques to identify, verify, and leverage the observed behavior, the expected behavior, and the steps to reproduce from bug descriptions, for  generating automated feedback to reporters about problems in their bug descriptions, and for improving the accuracy of bug resolution tasks. Specifically, we propose techniques and present empirical results on (i) discovering discourse patterns used by reporters to describe bugs; (ii) automatically detecting missing information in bug descriptions; (iii) automatically assessing the quality of the steps to reproduce provided in such descriptions; and (iv) leveraging bug descriptions and query reformulation to improve automated bug localization and duplicate bug report detection. 

The proposed techniques aim to reduce the effort and time devoted by developers when triaging and solving software bugs. We expect that the feedback provided by these techniques will help write higher-quality bug descriptions, while facilitating the detection of duplicate bug reports and the localization of the reported bugs in source code.
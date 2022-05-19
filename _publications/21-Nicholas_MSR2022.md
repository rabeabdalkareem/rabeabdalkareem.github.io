---
collection: publications
permalink: /publications/21-Nicholas_MSR2022

title: "On the Co-Occurrence of Refactoring of Test and Source Code"

authors: "N. Alexandre Nagy and R. Abdalkareem"


venue_key: "NicholasMSR2022"
track: Proceedings of the 18th International Conference on Mining Software Repositories (MSR’22), Mining Challenge Track<strong style="color:#E42217"> -Received the Best Student Presentation of the Mining Challenge track</strong>




pages: "1–5"
date: 2022-03-07
doiurl: 

paperurl: /files/21-Nicholas_MSR2022.pdf
notes:
---

**Abstract:** Refactoring is a widespread practice that aims to help improve the quality of a software system without altering its external behaviour. In practice, developers can perform refactoring operations on test and source code. 
However, while prior work shows that refactoring source code brings many benefits, a limited number of studies empirically investigate refactoring of test code and whether it is co-occurred with source code. To examine those co-occurring refactorings, we conducted an empirical study of 60,465 commits spanning 77 open-source Java projects.

First, we quantitatively analyzed the commits from those projects to identify co-occurring refactoring commits (i.e., commits contain refactorings performed on test and source code). Our results showed that on average 17.9% of refactoring commits are co-occurring refactoring commits, which is twice as much as test code-only refactoring commits. Also, we investigated the type of refactorings applied to test code in those co-occurring commits. We found Change Variable Type and Move Class are the most common refactorings. 
Second, we trained random forest classifiers to predict when refactoring test code should co-occur with refactoring source code using features extracted from the refactoring source code in ten selected projects. Our results showed that the classifier can accurately predict when test and source code refactoring co-occurs with AUC values between 0.67-0.92. Our analysis also showed that the most important features for our classifier are related the refactoring size and developer refactoring experience.
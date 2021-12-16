---
collection: publications
permalink: /publications/14-Hoyos_EMSE2020

title: "On the Removal of Feature Toggles A Study of Python Projects and Practitioners Motivations"
authors: "J. Hoyos, R. Abdalkareem, S. Mujahid, E. Shihab, and A. Espinosa"
venue_key: "Hoyos_EMSE2020"
track: Empirical Software Engineering (EMSE)
pages: "1–30"
date: 2020-10-12
doiurl: 

paperurl: /files/14-Hoyos_EMSE2020.pdf
notes:
---

**Abstract:** Feature Toggling is a technique to control the execution of features in a software project. For example, practitioners using feature toggles can experiment with new features in a production environment by exposing them to a subset of users. Some of these toggles require additional maintainability efforts and are expected to be removed, whereas others are meant to remain for a long time. However, to date, very little is known about the removal of feature toggles, which is why we focus on this topic in our paper.
We conduct an empirical study that focuses on the removal of feature toggles. We use source code analysis techniques to analyze 12 Python open source projects and surveyed 61 software practitioners to provide deeper insights on the topic. Our study shows that 75% of the toggle components in the studied Python projects are removed within 49 weeks after introduction. However, eventually practitioners remove feature toggles to follow the life cycle of a feature when it becomes stable in production. We also find that not all long-term feature toggles are designed to live that long and not all feature toggles are removed from the source code, opening the possibilities to unwanted risks. Our study broadens the understanding of feature toggles by identifying reasons for their survival in practice and aims to help practitioners make better decisions regarding the way they manage and remove feature toggles.
---
collection: publications
permalink: /publications/18-Abbas_TSE2021

title: "Dependency Smells in JavaScript Projects"

authors: "A. Javan Jafari, D. Elias Costa, R. Abdalkareem, E. Shihab, and N. Tsantalis"




venue_key: "AbbasTSE2021"
track: IEEE Transactions on Software Engineering (TSE) - <strong>invited to be presented at ICSE 2022 as a Journal First paper.</strong>
pages: "1-18"
date: 2021-08-16
doiurl: 

paperurl: /files/19-Abbas_TSE2021.pdf
notes:
---

**Abstract:** Dependency management in modern software development poses many challenges for developers who wish to stay up to date with the latest features and fixes whilst ensuring backwards compatibility. Project maintainers have opted for varied, and sometimes conflicting, approaches for maintaining their dependencies. Opting for unsuitable approaches can introduce bugs and vulnerabilities into the project, introduce breaking changes, cause extraneous installations, and reduce dependency understandability, making it harder for others to contribute effectively.

In this paper, we empirically examine evidence of recurring dependency management issues (dependency smells). We look at the commit data for a dataset of 1,146 active JavaScript repositories to catalog, quantify and understand dependency smells. Through a series of surveys with practitioners, we identify and quantify seven dependency smells with varying degrees of popularity and investigate why they are introduced throughout project history. Our findings indicate that dependency smells are prevalent in JavaScript projects with two or more distinct smells appearing in 80% of the projects, but they generally infect a minority of a project's dependencies. Our observations show that the number of dependency smells tend to increase over time. Practitioners agree that dependency smells bring about many problems including security threats, bugs, dependency breakage, runtime errors, and other maintenance issues. These smells are generally introduced as developers react to dependency misbehaviour and the shortcomings of the npm ecosystem.
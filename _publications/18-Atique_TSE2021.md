---
collection: publications
permalink: /publications/18-Atique_TSE2021

title: "On the Untriviality of Trivial Packages: An Empirical Study of npm JavaScript Packages"

authors: "A. Reza Chowdhury, R. Abdalkareem, E. Shihab, and B. Adams"


venue_key: "AtiqueTSE2021"
track: IEEE Transactions on Software Engineering (TSE)
pages: "1-16"
date: 2021-03-15
doiurl: 

paperurl: /files/18-Atique_TSE2021.pdf
notes:
---

**Abstract:** Nowadays, developing software would be unthinkable without the use of third-party packages. Although such code reuse helps to achieve rapid continuous delivery of software to end-users, blindly reusing code has its pitfalls. For example, prior work has investigated the rationale for using packages that implement simple functionalities, known as trivial packages (i.e., in terms of the code size and complexity). This prior work showed that although these trivial packages were simple, they were popular and prevalent in the npm ecosystem. This popularity and prevalence of trivial packages peaked our interest in questioning the 'triviality of trivial packages'. 

To better understand and examine the triviality of trivial packages, we mine a large set of JavaScript projects that use trivial npm packages and evaluate their relative centrality. Specifically, we evaluate the triviality from two complementary points of view: based on project usage and ecosystem usage of these trivial packages. Our result shows that trivial packages are being used in central JavaScript files of a software project. Additionally, by analyzing all external package API calls in these JavaScript files, we found that a high percentage of these API calls are attributed to trivial packages. Therefore, these packages play a significant role in JavaScript files. Furthermore, in the package dependency network, we observed that 16.8% packages are trivial and in some cases removing a trivial package can impact approximately 29% of the ecosystem. Overall, our finding indicates that although smaller in size and complexity, trivial packages are highly depended on packages by JavaScript projects. Additionally, our study shows that although they might be called trivial, nothing about trivial packages is trivial.
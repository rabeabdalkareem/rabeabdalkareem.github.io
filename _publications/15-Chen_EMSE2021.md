---
collection: publications
permalink: /publications/15-Chen_EMSE2020

title: "Helping or not Helping? Why and How Trivial Packages Impact the npm Ecosystem"
authors: "X. Chen, R. Abdalkareem, S. Mujahid, E. Shihab, and X. Xia"
venue_key: "ChenEMSE2020"
track: Empirical Software Engineering (EMSE)
pages: "1–26"
date: 2020-11-02
doiurl: 

paperurl: /files/15-Chen_EMSE2020.pdf
notes:
---

**Abstract:** Developers often share their code snippets by packaging them and making them available to others through software packages. How much a package does and how big it is can be seen as positive or negative. Recent studies showed that many packages that exist in the npm ecosystem are trivial and may introduce high dependency overhead.

Hence, one question that arises is why developers choose to publish these trivial packages. Therefore, in this paper, we perform a developer-centered study to empirically examine why developers choose to publish such trivial packages. Specifically, we ask 1) why developers publish trivial packages, 2) what they believe to be the possible negative impacts of these packages, and 3) how such negative issues can be mitigated. The survey response of 59 JavaScript developers who publish trivial npm packages showed that the main advantages for publishing these trivial packages are to provide reusable components, testing & documentation, and separation of concerns. Even the developers who publish these trivial packages admitted to having issues when they publish such packages, which include the maintenance of multiple packages, dependency hell, finding the right package, and the increase of duplicated packages in the ecosystems. Furthermore, we found that the majority of the developers suggested grouping these trivial packages to cope with the problems associated with publishing them. Then, to quantitatively investigate the impact of these trivial packages on the npm ecosystem and its users, we examine grouping these trivial packages. We found that if trivial packages that are always used together are grouped, the ecosystem can reduce the number of dependencies by approximately 13%. Our findings shed light on the impact of publishing trivial packages and show that ecosystems and developer communities need to rethink their publishing policies since it can negatively impact the developers and the entire ecosystem.
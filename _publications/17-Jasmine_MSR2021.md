---
collection: publications
permalink: /publications/17-Jasmine_MSR2021

title: "How Effective is Continuous Integration in Indicating Single-Statement Bugs?"

authors: "J. Latendresse, R. Abdalkareem, D. Elias Costa, and E. Shihab"


venue_key: "JasmineMSR2021"
track: Proceedings of the 17th International Conference on Mining Software Repositories (MSR’21), Mining Challenge Track.
pages: "1–5"
date: 2021-02-22
doiurl: 

paperurl: /files/16-Costa_TSE2021.pdf
notes:
---

**Abstract:** Continuous Integration (CI) is the process of auto-matically compiling, building, and testing code changes in the hope of catching bugs as they are introduced into the code base. With bug fixing being a core and increasingly costly task in software development, the community has adopted CI to mitigate this issue and improve the quality of their software products. Bug fixing is a core task in software development and becomes increasingly costly over time. However, little is known about how effective CI is at detecting simple, single-statement bugs.

In this paper, we analyze the effectiveness of CI in 14 popular open source Java-based projects to warn about 318 single-statement bugs (SStuBs). We analyze the build status at the commits that introduce SStuBs and before the SStuBs were fixed. We then investigate how often CI indicates the presence of these bugs, through test failure. Our results show that only 2% of the commits that introduced SStuBs have builds with failed tests and 7.5% of builds before the fix reported test failures. Upon close manual inspection, we found that none of the failed builds actually captured  SStuBs, indicating that CI is not the right medium to capture the SStuBs we studied. Our results suggest that developers should not rely on CI to catch SStuBs or increase their CI pipeline coverage to detect single-statement bugs.
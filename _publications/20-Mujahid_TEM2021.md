---
collection: publications
permalink: /publications/20-Mujahid_TEM2021

title: "Towards Using Package Centrality Trend to Identify Packages in Decline"

authors: "S. Mujahid, D. Elias Costa, R. Abdalkareem, E. Shihab, M. Saied, B. Adams"






venue_key: "MujahidTME2021"
track: IEEE Transactions on Engineering Management (TEM)
pages: "1-16"
date: 2021-10-18
doiurl: 

paperurl: /files/20-Mujahid_TEM2021.pdf
notes:
---

**Abstract:** Due to its increasing complexity, today’s software systems are frequently built by leveraging reusable code in the form of libraries and packages. Software ecosystems (e.g., npm) are the primary enablers of this code reuse, providing developers with a platform to share their own and use others’ code. These ecosystems evolve rapidly: developers add new packages every day to solve new problems or provide alternative solutions, causing obsolete packages to decline in their importance to the community. Developers should avoid depending on packages in decline, as these packages are reused less over time and may become less frequently maintained. However, current popularity metrics (e.g., Stars, and Downloads) are not fit to provide this information to developers because their semantics do not aptly capture shifts in the community interest.

In this paper, we propose a scalable approach that uses the package’s centrality in the ecosystem to identify packages in decline. We evaluate our approach with the npm ecosystem and show that the trends of centrality over time can correctly distinguish packages in decline with an ROC-AUC of 0.9. The approach can capture 87% of the packages in decline, on average 18 months before the trend is shown in currently used package popularity metrics. We implement this approach in a tool that can be used to augment npms metrics and help developers avoid packages in decline when reusing packages from npm.
---
collection: publications
permalink: /publications/7-Mujahid_MSR2020

title: "Using Others’ Tests to Avoid Breaking Updates"
authors: "S. Mujahid, R. Abdelkareem, E. Shihab, and S. McIntosh"
venue_key: "Mujahid_MSR2020"
track: Proceedings of the 17th International Conference on Mining Software Repositories (MSR’20)
pages: "1–12"
date: 2020-03-01
doiurl: 

paperurl: /files/7-Mujahid_MSR2020.pdf
notes:
---

**Abstract:** The reuse of third-party packages has become a common practice in contemporary software development. Software dependencies are constantly evolving with newly added features and patches that  fix bugs in older versions. However, updating dependencies could introduce new bugs or break backward compatibility. In this work, we propose a technique to detect breakage-inducing versions of third-party dependencies. The key insight behind our approach is to leverage the automated test suites of other projects that depend upon the same dependency to test newly released versions We conjecture that this crowd-based approach will help to detect breakage-inducing versions because it broadens the set of realistic usage scenarios to which a package version has been exposed. To evaluate our conjecture, we perform an empirical study of 391,553 npm packages. We use the dependency network from these packages to identify candidate tests of third-party packages. Moreover, to evaluate our proposed technique, we mine the history of this dependency network to identify ten breakage-inducing versions. We find that our proposed technique can detect six of the ten studied breakage-inducing versions. Our findings can help developers to make more informed decisions when they update their dependencies.
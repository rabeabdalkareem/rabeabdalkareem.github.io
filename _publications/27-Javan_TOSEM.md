---
collection: publications
permalink: /publications/27-Javan_TOSEM23

title: "Dependency Update Strategies and Package Characteristics"

authors: "A. Javan Jafari, D. Elias Costa, E. Shihab and R. Abdalkareem"




venue_key: "JavanTOSEM23"
track: ACM Transactions on Software Engineering and Methodology (TOSEM)
pages: "1–28"
date: 2023-04-05
doiurl: 

paperurl: /files/27-Javan_TOSEM23.pdf
notes:
---

**Abstract:** Managing project dependencies is a key maintenance issue in software development. Developers need to
choose an update strategy that allows them to receive important updates and  xes while protecting them
from breaking changes. Semantic Versioning was proposed to address this dilemma but many have opted for
more restrictive or permissive alternatives. This empirical study explores the association between package
characteristics and the dependency update strategy selected by its dependents to understand how developers
select and change their update strategies. We study over 112,000 npm packages and use 19 characteristics to
build a prediction model that identi es the common dependency update strategy for each package. Our model
achieves a minimum improvement of 72% over the baselines and is much better aligned with community
decisions than the npm default strategy.We investigate how di erent package characteristics can in uence the
predicted update strategy and  nd that dependent count, age and release status to be the highest in uencing
features. We complement the work with qualitative analyses of 160 packages to investigate the evolution of
update strategies. While the common update strategy remains consistent for many packages, certain events
such as the release of the 1.0.0 version or breaking changes in uence the selected update strategy over time.
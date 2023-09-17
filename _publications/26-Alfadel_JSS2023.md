---
collection: publications
permalink: /publications/26-Alfadel_JSS2023

title: "Qualitative Analysis of Security-Related Code Reviews: An Empirical Study"

authors: "M. Alfadel, N. Nagy, D. Costa, R. Abdalkareem, and E. Shihab"




venue_key: "AlfadelJSS2023"
track: The Journal of Systems and Software (JSS)
pages: "1–28"
date: 2023-04-05
doiurl: 

paperurl: /files/26-Alfadel_JSS2023.pdf
notes:
---

**Abstract:** Security issues are a major concern in software packages and their impact can be detrimental if exploited.
Modern code review is a widely-used practice that project maintainers adopt to improve the quality of
contributed code. Prior work has shown that code review has an important role in improving software
quality, however, in-depth analyses on code review in relation to security issues are limited.
Therefore, in this paper, we aim to explore the role of code review in finding and mitigating security
issues. In particular, we investigate active and popular npm packages to understand what types of
security issues are raised during code review, and what kind of mitigation strategies are employed by
package maintainers to address them. With pull requests (PRs) being the medium of code review under
study, we analyze 171 PRs with raised security issues. We find that such issues are discussed at length
by package maintainers. Moreover, we find that code review is effective at identifying certain types of
security concerns, e.g., Race Condition, Access Control, and ReDOS, as dealing with such issues requires
in-depth knowledge of the project domain and implementation specifics. Interestingly, we also observe
that some projects have automated tools integrated in the project development cycle, which enhances the
identification of frequent cases of certain security issues. When analysing how maintainers respond to the
raised security issues, we find that most of the issues (55%) are frequently addressed and mitigated. In
other cases, security concerns ended up not being fixed or are ignored by project maintainers. Leveraging
our findings, we offer several implications for project maintainers to support the role of reviewing code
in finding and fixing security concerns.
---
collection: publications
permalink: /publications/24-Obrien_FSE2022

title: "23 Shades of Self-Admitted Technical Debt: An Empirical Study on Machine Learning Software"
authors: "D. OBrien, S. Biswas, S. Imtiaz, R. Abdalkareem, E. Shihab, and H. Rajan"
venue_key: "Obrien_FSE2022"
track: Proceedings of the 11th Joint Meeting of the European Software Engineering Conference and the ACM SIGSOFT Symposium on the Foundations of Software Engineering (ESEC/FSE’22)
pages: "1–12"
date: 2022-10-01

paperurl: /files/4-Abdalkareem_FSE2017.pdf
notes:
---

**Abstract:** In software development, the term “technical debt” (TD) is used to
characterize short-term solutions and workarounds implemented
in source code which may incur a long-term cost. Technical debt
has a variety of forms and can thus affect multiple qualities of software
including but not limited to its legibility, performance, and
structure. In this paper, we have conducted a comprehensive study
on the technical debts in machine learning (ML) based software.
TD can appear differently in ML software by infecting the data that
ML models are trained on, thus affecting the functional behavior of
ML systems. The growing inclusion of ML components in modern
software systems have introduced a new set of TDs. Does ML software
have similar TDs to traditional software? If not, what are the
new types of ML specific TDs? Which ML pipeline stages do these
debts appear? Do these debts differ in ML tools and applications
and when they get removed? Currently, we do not know the state
of the ML TDs in the wild. To address these questions, we mined
68,820 self-admitted technical debts (SATD) from all the revisions of
a curated dataset consisting of 2,641 popular ML repositories from
GitHub, along with their introduction and removal. By applying
an open-coding scheme and following upon prior works, we provide
a comprehensive taxonomy of ML SATDs. Our study analyzes
ML SATD type organizations, their frequencies within stages of
ML software, the differences between ML SATDs in applications
and tools, and quantifies the removal of ML SATDs. The findings
discovered suggest implications for ML developers and researchers
to create maintainable ML systems.
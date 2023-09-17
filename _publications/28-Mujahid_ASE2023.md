---
collection: publications
permalink: /publications/28-Mujahid_ASE2023

title: "Where to Go Now? Finding Alternatives for Declining Packages in the npm Ecosystem"
authors: "S. Mujahid, D. Elias Costa, R. Abdalkareem, and E. Shihab"
venue_key: "Mujahid_ASE2023"
track: Proceedings of the 38th IEEE/ACM International Conference on Automated Software Engineering (ASE 2023)
pages: "1–12"
date: 2023-10-01

paperurl: /files/28-Mujahid_ASE2023.pdf
notes:
---

**Abstract:** Software ecosystems (e.g., npm, PyPI) are the backbone
of modern software developments. Developers add new
packages to ecosystems every day to solve new problems or
provide alternative solutions, causing obsolete packages to decline
in their importance to the community. Packages in decline
are reused less over time and may become less frequently
maintained. Thus, developers usually migrate their dependencies
to better alternatives. Replacing packages in decline with better
alternatives requires time and effort by developers to identify
packages that need to be replaced, find the alternatives, asset
migration benefits, and finally, perform the migration.
This paper proposes an approach that automatically identifies
packages that need to be replaced and finds their alternatives
supported with real-world examples of open source projects
performing the suggested migrations. At its core, our approach
relies on the dependency migration patterns performed in the
ecosystem to suggest migrations to other developers. We evaluated
our approach on the npm ecosystem and found that
96% of the suggested alternatives are accurate. Furthermore, by
surveying expert JavaScript developers, 67% of them indicate
that they will use our suggested alternative packages in their
future projects.
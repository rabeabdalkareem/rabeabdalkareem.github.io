---
collection: publications
permalink: /publications/12-saner19

title: "Reformulating Queries for Duplicate Bug Report Detection"
authors: "**Oscar Chaparro**, Juan Manuel Florez, Unnati Singh, and Andrian Marcus"
venue_key: "saner19"
track: 
pages: "218-229"
date: 2019-01-01
doiurl: https://doi.org/10.1109/SANER.2019.8667985

paperurl: /files/12-saner19.pdf
package: https://seers.utdallas.edu/projects/ob-query-reformulation-duplicates/
notes: 
---

**Abstract:** When bugs are reported, one important task is to check if they are new or if they were reported before. Many approaches have been proposed to partially automate duplicate bug report detection, and most of them rely on text retrieval techniques, using the bug reports as queries. Some of them include additional bug information and use complex retrieval- or learning-based methods. In the end, even the most sophisticated approaches fail to retrieve duplicate bug reports in many cases, leaving the bug triagers to their own devices. We argue that these duplicate bug retrieval tools should be used interactively, allowing the users to reformulate the queries to refine the retrieval. With that in mind, we are proposing three query reformulation strategies that require the users to simply select from the bug report the description of the software’s observed behavior and/or the bug title, and combine them to issue a new query. The paper reports an empirical evaluation of the reformulation strategies, using a basic duplicate retrieval technique, on bug reports with duplicates from 20 open source projects. The duplicate detector failed to retrieve duplicates in top 5-30 for a significant number of the bug reports (between 34% and 50%). We reformulated the queries for a sample of these bug reports and compared the results against the initial query. We found that using the observed behavior description, together with the title, leads to the best retrieval performance. Using only the title or only the observed behavior for reformulation is also better than retrieval with the initial query. The reformulation strategies lead to 56.6%-78% average retrieval improvement, over using the initial query only.
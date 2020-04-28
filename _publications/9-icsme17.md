---
collection: publications
permalink: /publications/9-icsme17

title: "Using Observed Behavior to Reformulate Queries during Text Retrieval-based Bug Localization"
authors: "**Oscar Chaparro**, Juan Manuel Florez, and Andrian Marcus"
venue_key: "icsme17"
track: 
pages: "376–387"
date: 2017-04-01
doiurl: https://doi.org/10.1109/ICSME.2017.100

paperurl: /files/9-icsme17.pdf
package: https://seers.utdallas.edu/projects/ob-query-reformulation/
notes: 
distinction: "IEEE TCSE Distinguished Paper Award"
---

**Abstract:** Text Retrieval (TR)-based approaches for bug localization rely on formulating an initial query based on a bug report. Often, the query does not return the buggy software artifacts at or near the top of the list (i.e., it is a low-quality query). In such cases, the query needs reformulation. Existing research on supporting developers in the reformulation of queries focuses mostly on leveraging relevance feedback from the user or expanding the original query with additional information (e.g., adding synonyms). In many cases, the problem with such low-quality queries is the presence of irrelevant terms (i.e., noise) and previous research has shown that removing such terms from the queries leads to substantial improvement in code retrieval. Unfortunately, the current state of research lacks methods to identify the irrelevant terms. Our research aims at addressing this problem and our conjecture is that reducing a low-quality query to only the terms describing the Observed Behavior (OB) can improve TR-based bug localization. To verify our conjecture, we conducted an empirical study using bug data from 21 open source systems to reformulate 451 low-quality queries. We compare the accuracy achieved by four TR-based bug localization approaches at three code granularities (i.e., files, classes, and methods), when using the complete bug reports as queries versus a reduced version corresponding to the OB only. The results show that the reformulated queries improve TR-based bug localization for all approaches by 147.4% and 116.6% on average, in terms of MRR and MAP, respectively. We conclude that using the OB descriptions is a simple and effective technique to reformulate low-quality queries during TR-based bug localization.
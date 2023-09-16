---
collection: publications
permalink: /publications/23-Sellami_ICSOC2022

title: "Combining Static and Dynamic Analysis to Decompose Monolithic Application into Microservices"

authors: "K. Sellami, M. Aymen Saied, A. Ouni, and R. Abdalkareem"





venue_key: "SellamiICSOC2022"
track: In Proceedings of the 2022 20th International Conference on Service Oriented Computing, (ICSOC'2022) - <strong style="color:#8B0000">Received the Distinguished Paper and Candidates for the Best Paper Award</strong>
pages: "203–218"
date: 2022
doiurl: 

paperurl: /files/23-Sellami_ICSOC2022.pdf
notes:
---

**Abstract:** In order to beneﬁt from the advantages oﬀered by the microservices architectural design, many companies have started migrating their monolithic application to this newer design. However, due to the high cost and development time associated to this task, automated approaches need to be developed to solve these issues.

Solutions that tackle this problem can be classiﬁed based on the information available for the monolithic application which are often based on source code or runtime traces. The latter provides a more accurate representation of the interactions between the classes within the application however it often fails to cover all of the classes. On the other hand, the source code of the application is more readily available and can be used to extract additional information like semantic meaning of the classes.

The objective of this paper is to provide a hybrid solution that combines both of these approaches in order to take advantage of their strengths while covering their weaknesses. The proposed solution performs static and dynamic analysis on the monolithic application based on the available information and the user’s input. Afterwards, an iterative clustering process is applied on the processed data in order to generate the microservices decomposition. We compare diﬀerent strategies for combining the static and dynamic approaches and we evaluate the performance of the hybrid approach compared to each of the separate approaches on 4 monolith applications. We provide as well a comparison with state-of-the-art solutions.
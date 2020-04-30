---
collection: publications
permalink: /publications/5-mujahid_icsme_2018

title: "Studying Permission Related Issues in Android Wearable Apps"
authors: "S. Mujahid, R. Abdalkareem, and E. Shihab"
venue_key: "mujahid_icsme_2018"
venue.name
track: Proceedings of the 34th International Conference on Software Maintenance and Evolution (ICSME’18)
pages: "1–12"
date: 2018-03-01
doiurl: 

paperurl: /files/5-mujahid_icsme_2018.pdf
notes:
---

**Abstract:** Wearable devices are becoming increasingly popular; these devices host software that is known as wearable
              apps. Wearable apps could be packaged alongside handheld apps,
              hence they must be installed on the accompanying device (e.g.,
              smartphone). This device dependency causes both apps to be
              also tightly coupled. Most importantly, when a wearable app is
              distributed by embedded it in a handheld app, Android Wear
              platform requires to include the wearable permission also in the
              handheld app which is error-prone.
              In this paper, we defined two permission issues related to
              wearable apps–namely permission mismatches and superfluous
              features. To study the permission related issues, we propose
              a technique to detect permission issues in wearable apps. We
              implement our technique in a tool called PERMLYZER, which
              automatically detects these permission issues from an app’s APK.
              We run PERMLYZER on a dataset of 2,724 apps that have
              embedded wearable version and 339 standalone wearable app.
              Our result shows that I) 6% of wearable apps that request
              permissions are suffering from the permission mismatching
              problem; II) out of the apps that requires underlying features,
              523 (52.4%) of handheld apps and 66 (80.5%) of standalone
              wearable apps have at least one superfluous feature; III) all the
              studied apps missed a declaration of underlying features for one
              or more of their permissions, which shows that developers may
              not know the mapping between the permissions they request and
              the hardware features. Additionally, in a survey of wearable app
              developers, all of the developers that responded mention that
              having a tool like PERMLYZER, that detect permission related
              issues would be useful to them. Our results contribute to the
              understanding of permissions related issues in wearable apps, in
              particular, proposing a technique to detect permission mismatch
              and superfluous features.
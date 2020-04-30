---
collection: publications
permalink: /publications/4-Abdalkareem_FSE2017

title: "Why Do Developers Use Trivial Packages? An Empirical Case Study on npm"
authors: "R. Abdalkareem, O. Nourry, S. Wehaibi, S. Mujahid, and E. Shihab"
venue_key: "Abdalkareem_FSE2017"
venue.name
track: Proceedings of the 11th Joint Meeting of the European Software Engineering Conference and the ACM SIGSOFT Symposium on the Foundations of Software Engineering (ESEC/FSE’17)
pages: "1–12"
date: 2017-03-01
doiurl: 

paperurl: /files/4-Abdalkareem_FSE2017.pdf
notes:
---

**Abstract:** Code reuse is traditionally seen as good practice. Recent trends
              have pushed the concept of code reuse to an extreme, by using
              packages that implement simple and trivial tasks, which we call
              ‘trivial packages’. A recent incident where a trivial package led to
              the breakdown of some of the most popular web applications such
              as Facebook and Netix made it imperative to question the growing
              use of trivial packages.
              erefore, in this paper, we mine more than 230,000 npm packages and 38,000 JavaScript applications in order to study the prevalence of trivial packages. We found that trivial packages are common and are increasing in popularity, making up 16.8% of the
              studied npm packages. We performed a survey with 88 Node.js
              developers who use trivial packages to understand the reasons and
              drawbacks of their use. Our survey revealed that trivial packages
              are used because they are perceived to be well implemented and
              tested pieces of code. However, developers are concerned about
              maintaining and the risks of breakages due to the extra dependencies trivial packages introduce. To objectively verify the survey
              results, we empirically validate the most cited reason and drawback
              and nd that, contrary to developers’ beliefs, only 45.2% of trivial
              packages even have tests. However, trivial packages appear to be
              ‘deployment tested’ and to have similar test, usage and community
              interest as non-trivial packages. On the other hand, we found that
              11.5% of the studied trivial packages have more than 20 dependencies. Hence, developers should be careful about which trivial
              packages they decide to use.
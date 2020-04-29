---
collection: publications
permalink: /publications/12-abdelkareem_emse2020

title: "On the impact of using trivial packages: an empirical case study on npm and PyPI"
authors: "R. Abdalkareem, V. Oda, S. Mujahid, and E. Shihab"
venue_key: "abdelkareem_emse2020"
track: Empirical Software Engineering (EMSE)
pages: "1–39"
date: 2020-03-01
doiurl: 

paperurl: /files/12-abdelkareem_emse2020.pdf
notes:
---

**Abstract:** Code reuse has traditionally been encouraged since it enables one to avoid re-inventing the
              wheel. Due to the npm left-pad package incident where a trivial package led to the breakdown
              of some of the most popular web applications such as Facebook and Netflix, some questioned such reuse. Reuse of trivial packages is particularly prevalent in platforms such as
              npm. To date, there is no study that examines the reason why developers reuse trivial packages other than in npm. Therefore, in this paper, we study two large platforms npm and PyPI.
              We mine more than 500,000 npm packages and 38,000 JavaScript applications and more
              than 63,000 PyPI packages and 14,000 Python applications to study the prevalence of trivial
              packages. We found that trivial packages are common, making up between 16.0% to 10.5%
              of the studied platforms. We performed surveys with 125 developers who use trivial packages to understand the reasons and drawbacks of their use. Our surveys revealed that trivial
              packages are used because they are perceived to be well implemented and tested pieces
              of code. However, developers are concerned about maintaining and the risks of breakages
              due to the extra dependencies trivial packages introduce. To objectively verify the survey
              results, we validate the most cited reason and drawback. We find that contrary to developers’
              beliefs only around 28% of npm and 49% PyPI trivial packages have tests. However, trivial
              packages appear to be ‘deployment tested’ and to have similar test, usage and community
              interest as non-trivial packages. On the other hand, we found that 18.4% and 2.9% of the
              studied trivial packages have more than 20 dependencies in npm and PyPI, respectively.
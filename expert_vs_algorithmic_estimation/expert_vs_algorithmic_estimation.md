---
title: "Expert vs Algorithmic Estimation"
author: ""
date: "2018-03-23"
header-includes: \usepackage{unicode-math}
---
<!-- Write a 700-word essay discussing and contrasting algorithmic vs. experience (expert) based software effort estimation. Discuss their use in waterfall (traditional) and agile development.

Include planning poker as one method used in experience-based estimation. You can find more information about planning poker in the optional reading or by listening to the lecture video. -->

<!-- 70 words -->


## Software Effort Estimation
**Effort estimation** is an activity that is a part of software planning. Traditionally effort estimation was done by the project manager, but nowadays the whole development team participates. Uncertainties make effort estimation difficult in the early stages of development, but the estimate becomes more accurate as the project advances. The effort is usually underestimated compared to the real effort measured at the end of the project. Effort estimation plays several roles in software development, for example it is used to calculate the estimated cost and budget of the project's activities and communicate with customers and developers that how much time the project will take [@Sommerville2010, chap. 23].

The next sections discuss about the two models that can be used for effort estimation: **Experience based estimation** and **algorithmic estimation**, and then makes a comparison between the models.


## Experience Based Estimation
Expericence based estimation is based on the previous experience of the project's developers (experts) and it will lead to informed judgement of the effort. The estimation activity should involve a group (development team) and each of the member should explain their estimates. Involving a group reveals factors to others that they may not have considered helping to iterate towards agreed group estimate [@Sommerville2010, chap. 23]. One such approach that involves a group is **planning poker** [@Mountain33] ...

The difficulties in experience based estimation are estimating the productivity of the developers which depends on attributes such as the developers skill level, their familiarity of the problem and dicipline. The lack of commonalities compared to previous projects can also make the estimation process difficult.


## Algorithmic Estimation
- formulaic approach to effort estimation based on estimates of product attributes (size,...) and process characteristics (staff experience,...)
- models often based on simple formula \[\mathrm{effort} = A ⋅ \mathrm{size}^{B} ⋅ M,\] where
    - \(A\) is constant factor depending on the local organizational practices and the software type
    - \(B\) is the value of the exponent, usually between \(1.0\) and \(1.5\), the effort does not usually increase linearly with the project size (increase complexity -> communication overhead, ...)
    - \(M\) is multiplier made by combining process, product and development attributes (dependability requirements, experience of the team)
    - \(\mathrm{size}\) may be assesment of code size or functionality estimate
- Shortcomings: Size is hard to estimate, estimates of \(B\) and \(M\) are subjective, models are difficult and hard to use, models require historical data for accurately estimating parameters, if using published values it is hard to know if they relate to their ogranizations values
- **COCOMO 2**


## Comparison


<!-- TODO? ## Conclusion -->


## Bibliography

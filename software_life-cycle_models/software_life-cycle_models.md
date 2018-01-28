---
title: "Software Life-cycle Models"
author: ""
date: "2018-01-28"
header-includes: \usepackage{unicode-math}
---
<!-- Write a 750-word (+-25%) essay describing and comparing the waterfall and incremental models. Describe the principles of each model, its strengths, weaknesses, and applicability. In particular, give practical examples of implementations of the incremental model. Explain the RUP model, and its relationship to the waterfall and incremental model. -->

This essay discusses about the principles, weaknesses and applicability of *waterfall* and *incremental* developement models, and makes comparisons between them. The essay also explains the relationship between waterfall and incremental developement models to *rational unified process (RUP)* [@Sommerville:2010:SE:1841764; @3Softwar25:online].


## Waterfall Model
Waterfall developement model is sequential model where each of the steps is fully completed before the next one. The steps of waterfall model in order are

1) Requirements analysis and definition
2) System and software design
3) Implementation and unit testing
4) Integration and system testing
5) Operation and maintenance

Waterfall model originates from the manufacturing and constrution industries where later modifications to the product are very expensive or impossible. The problem with waterfall model is the difference between hardware and software. It is not as costly to change software as it is hardware, and changes are usually required because the full specification may not be known beforehand or may change during the process. Waterfall model makes fixing problems hard and expensive and is only applicable for software developement when the requirements are fully known beforehand.


## Incremental Model
Incremental development model dates back to 1950s and later became popular development model in response to shortcomings of waterfall model [@Larman2003]. Incremental developement model is iterative model in which after the initial planning, the software is developed in repeated cycles called iterations. During each iteration, specification, developement and validation processes happen all interleaved, while incorporating the new functionality required by the customer. After the iteration, a new version of the program is released for the customers to evaluate. Developers then receive feedback from the customers about the new iteration which can be taken account for later iterations. Incremental model is very flexible and allows the customer feedback on all of the developement processes. Popular incremental developement models are agile and plan-driven developement.


## Comparison
@Differen58:online article lists a number of differences between waterfall and inremental developements models

**User involvement**: Users are only involved at requirements stage of waterfall model compared to every stage in incremental model.

**Supply**: Waterfall model deliveres software to the customer after all stages are completed. In comparison in incremental developement software is delivered after each increment is made and development will move to the next stage after use approval.

**Variability**: Software can't be (easily) changed during waterfall process compared to incremental model where changes to the software can be made accoding the the requirements and are easier to make.

**Credentials**: Waterfall model focuses on documenting every stage and deliveres documentation as end product compared to incremental developement where main focus is customer satisfaction over documentation

**Manpower**: Waterfall model requires more manpower compared to incremental developement.

**Time limitation**: Waterfall model deliveres operation software in months compared to weeks in incremental developement model.

**Project size**: Waterfall model is not suited for small project where as incremental model can be

Waterfall model is best suited for large projects where the requirements are well known prior the developement process and are not subject to change. Incremental developement model on the other hand is suited for project that might require any change or evolution during the life cycle of the software.


## Rational Unified Process (RUP)
Rational unified process (RUP) provides adaptive framework to software developement process. RUP consists of building blocks and project life-cycle phases. The three building blocks are roles, work products and tasks. Four project life-cycle phases are inception, elaboration, construction and transition. Relation to waterfall and inremental models RUP has similarities with waterfall method is iterative. Also each of its phases has multiple internal iterations. Compared to some incremental methods like agile, RUP is not as flexible [@Waterfal1:online].


## Bibliography

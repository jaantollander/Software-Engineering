---
title: "Adopting Agile Development in the Large"
author: ""
date: "2018-02-01"
header-includes: \usepackage{unicode-math}
---
<!-- Write a 700-1000-word essay discussing the use of agile development in large organizations. Discuss reasons to do it, as well as its benefits, drawbacks and adoption problems and tips. Use both the readings (textbook, article), as well as the Ericsson podcast interview.  -->

Many large organizations have traditionally used *waterfall* software development models. Because of the flaws and inefficiencies of the waterfall model large organization are looking to adopt *agile* development models. The adoption of agile development model requires transition that can be challenging and take considerable amount of time and effort. Part of the challence is scaling the agile model, because it was developed for smaller organizations with team size of roomful of people. Agile practices such as customer involvement, informal communication over documentation, continuous integration and frequent system builds often require changes withing the organization and the codebase. This essay discusses about the benefits, drawbacks and the adoption problems of the transition into agile development and about agile development in large organizations.

## Agile Development in Large Organizations
Large organization and systems contain components that violate the principles of agile development. They also require a number of adaptations to work. @Sommerville:2010:SE:1841764 lists a number these challences and adaptations:

#) Large systems consists of multiple parts, often developed in separate from each other by separate teams that maybe in other places. This also makes it practically impossible to have a view of the whole system.
#) Large systems interact with other existing systems, which may not be compatible with agile development practices.
#) System configuration takes larger portion of development time in large integrated systems. This is not compatible with agile development practices.
#) Development of large systems is often constrained by external rules and regulations which limit the development.
#) Due to long produrement and development time, it is challencing to maintain coherent teams with knowledge of the system over the whole development period.
#) It is impossible to involve the whole set of stakeholders into the development process since large systems have lots of stakeholders.

In order for large organization to adapt agile methods they have to maintain the fundamentals for agile development such as *flexible planning*, *frequent system releases*, *continuous integration*, *test drive development* and *good team commmunications*. Critical adaptations are

#) More up-front design and system documentation, software architecture has to be designed, documentation about the critical aspects of the system.
#) Cross-team communication mechanisms, for instance through phone or video.
#) Continuous integration may be practically impossible, but organization should maintain frequent system builds and releases of the system.


## Agile Development at Ericsson
Lassenius and Engblom discusses about transformation from waterfall model to using scrum at Ericsson [@httpslas12:online].

Around 400 people and 40 teams in 3 different locations developing a mobile core network node with size of 50 million lines of code. The development has been on going since 1990s.

Engblom described that the main problems in waterfall model were

- Too big scope resulted in lead times of two years of development time were no longer viable for 21th century software.
- Responsiveness and flexibility were not good enough and changes would take too long to implement.
- Quality of the software would degrade since size of the tests kept growing.
- Motivation inside teams was suffering since there was no room for developers to grow and they had limited view of the whole picture.

The reasons for choosing agile described were to avoid oversized specification and the use of direct communication over documents.

Engblom then describes how they scaled the agile practices inside Ericsson.

- Initial testing with one team revealed problems with time boxing, also test and build times were found to be too long. This was a problem for implementing continuous integration.
- Cross-functional teams were implemented and component guardians who were available for teams to consult for specic knowledge about specic parts of the system.
- Scrum masters were chosen from former line and project managers and later from developer team members. Each team also had a product proxy owner.
- To implement communication between teams, application was divided into areas and the teams communicated at area level and with teams that were working on same features.
- Workspace was physically changed from a traditional offices where every one was in their own room into more open space where people were together to improve communication and transparency. Physical change also visualized the change of the development method.

Noted benefits and improvements that changing into agile development model were savings in admistritative costs, average feature cost decreases, release interval time has decresed and positive change in the athmosphere.


## Bibliography

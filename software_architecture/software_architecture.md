---
title: "Software Architecture"
author: ""
date: "2018-02-22"
header-includes: \usepackage{unicode-math}
---
<!-- Write a 700-word essay discussion on the role and importance of software architecture in agile development. Discuss the idea of architecture as an emergent versus planned property of a system, when, how, and by whom architecture should be planned. What is the role of a software architect in agile development? -->

This essay discusses the importance of software architecture in agile development. Software architecture is a high-level description of the system. Architectural decisions have profound effects on the ability of the software to meet the critical requirements, such as performance or security. The architectural style and structure depend on the non-functional requirements of the software. [@Sommerville:2010:SE:1841764]


## Software Architecture in Agile Development
@Abrahamsson2010 discuss the relationship between agile development and architecture. According to them, software architecture in agile development is about finding the balance between *adaptiveness* of agile methods and the *anticipatory* nature of traditional methods. They emphasize that architecture is important in agile development and it is sometimes ignored due to a misunderstanding of agile methods. They list the potential issues with agile software architecture:

#) The organization should define what they mean by software architecture such that it can be distinguished from other software design.
#) The amount of architectural activity depends on the context (project environment, organization, domain) and other specific factors such as the size of the project. A large project may require significant architectural effort.
#) Architecture decisions should be early enough since they have an effect on other significant decisions about the structure and behavior of the system.
#) An agile project can have multiple software architects with different skills.
#) For most projects, an architectural prototype is sufficient amount of explicit documentation, but the larger project may require more.
#) Agile development has a focus on delivering business value thus the value of architecture might remain invisible.


<!--
The role of software architects in agile development?
Architecture as Emergent versus Planned Property
-->

In an interview Philippe Kruchten shares his views and experiences software architecture in agile development [@philippekruchten]. The main points he made about agile software architecture:

#) Architecture is important and aids the project in scaling up.
#) Architecture or atleast the requirements for one *emerges* during the development process, but the architectural design cannot be left on its own or otherwise it will be ignored, which at worst could lead to having to rewrite large parts of the codebase.
#) The role of software architect not a jobtitle, but collectively shared responsibility. New project however should appoint project architecture owner, someone with experience in software architecture, and who is persistent and curious. The software architects have to play a role of communicator between teams and the client.
#) Technical dept can accumulate if a lot of quick and easy fixes are done instead of building an architecture that allows scaling up. Sole focus on emmediate results may have long term negative consequences.
#) Traditionally architecture has been upfront activity. In agile development its usually conducted in the early third.
#) Arhitectural decisions should be organized by importance in such a way that they allow other team members to make progress.
#) Critical architectural decisions can be postponed until there is enough information to implement them.
#) The effects on critical requirements (i.e performance, security) should be considered when making significant architectural decisions.
#) Agile architecure should be flexible enough to accomodate certain number of anticipated changes. Agile principles can be used to build an software architecture such as incremental design. Different architectures can be tested and validated by running real code on them instead of relying purely on upfront design.
#) The value of good architecture shoudl be exposed to the client since its effect are hard to see

## Bibliography

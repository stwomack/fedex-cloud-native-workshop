# Cloud Native Workshop
Cloud Native Application development with Spring and Cloud Foundry. Join Pivotal for a hands-on workshop to introduce key concepts in modern cloud native application development and delivery. The labs will leverage Spring Boot.

**Events**
- Stay informed for the [2019 SpringOne Platform](https://springoneplatform.io/) to be held in Austin, TX, Oct 7-10, 2019.

## Agenda

Time | Session
---- | -------
9:00 AM - 9:15 AM | _Workshop Kickoff And Intros_
9:15 AM - 10:00 AM | _Cloud Native Architectures and Frameworks( Microservices, 12Factor Apps )_
10:00 AM- 10:15 AM | _Break_
10:15 AM - 12:00 PM | _Developer Workshop (*LABS*)_
12:00 PM - 1:00 PM | _Lunch_
1:00 PM - 1:30 PM | _Spring Boot Overview_
1:30 PM - 2:30 PM | _Developer Workshop (*LABS* Continued)_
2:30 PM - 3:00 PM | _Wrap-up, Q&A_

_*See [Labs Materials](#labs-materials) section below for slides and labs_

This is a _loose_ schedule for the day. We will adjust as necessary based on our pace through the material. We'll take breaks as the group agrees

The talk-tracks for this workshop are generally light and are only intended to set the stage for the hands-on labs.
The majority of our time will be spent engaging with the technology directly.

## Getting started

**Prerequisites**

Start by downloading and installing the appropriate prerequisite tools.
- [Cloud Foundry CLI](MAC: https://cli.run.pivotal.io/stable?release=macosx64&source=pws, Windows: https://cli.run.pivotal.io/stable?release=windows64&source=pws) to interact with a cloud foundry instance
- [Git Client](https://git-scm.com/downloads) to clone Github repo or download and unzip
- An IDE, like [Spring Tool Suite](https://spring.io/tools/sts/all) or [IntelliJ IDEA](https://www.jetbrains.com/idea/download/)
- [Java SE Development Kit](http://info.pivotal.io/n0I60i3021AN0JU0le10CRR)

**Download materials**

Next, download the course materials.  This can be accomplished either through the GitHub website by downloading a repository zip and unzipping locally, or if you have Git installed, use the following commands:


```
git clone https://github.com/stwomack/at-cloud-native-workshop.git
cd at-cloud-native-spring-workshop
```

```
$ git clone git@github.com:stwomack/at-cloud-native-workshop.git
$ cd at-cloud-native-spring-workshop/
```

***NOTE***
When labs reference $COURSE_HOME, that's where you checked out this repository

**PCF Environments**

In order to perform the labs, you must be connected or logged into a live PCF environment.

## Labs Materials

### _Cloud Native Architectures and Frameworks( Microservices, 12Factor Apps )_ [(Slides)](session_02/Session_02-Cloud_Native_Architectures_and_Frameworks.pptx)

### _Enabling Continuous Delivery with 'cf push'_
  - [Lab 1 - Building and Pushing Your First Application](session_03/lab_01/lab_01.adoc)
  - [Lab 2 - Binding to Cloud Foundry Services](session_03/lab_02/lab_02.adoc)
  - [Lab 3 - Scaling Applications](session_03/lab_03/lab_03.adoc)
  - [Lab 4 - Monitoring Applications](session_03/lab_04/lab_04.adoc)

### _Lunch:_
  
### _Spring Boot and Actuator_ [(Slides)](session_05/Session_05-Spring_Boot_Actuator-2xpg.pdf)
  - [Lab 5 - Introspection, Monitoring, and Metrics using Spring Boot Actuator](session_05/lab_05/lab_05.adoc)
  
### _Spring Cloud Services_  [(Slides)](session_06/Session_06-Spring-Cloud-Services-2xpg.pdf)
  - [Lab 6 - Spring Cloud Config Server](session_06/lab_06/lab_06.adoc)


### SKIP - Already Complete - REFERENCE ONLY _Cloud Native Platforms_ [(Slides)](session_04/Session_04-Cloud_Native_Platforms.pdf)

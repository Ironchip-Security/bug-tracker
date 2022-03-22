![GitHub issues](https://img.shields.io/github/issues/Ironchip-Security/bug-tracker?color=green&style=plastic)
![GitHub closed issues](https://img.shields.io/github/issues-closed/Ironchip-Security/bug-tracker?color=green&style=plastic)

<!--[![][IronchipImage]][Ironchip]-->

Copyright 2021 [Ironchip].

[Ironchip]: https://www.ironchip.com/
[IronchipImage]: https://

About Ironchip
=============

IronChip is a startup that creates cybersecurity solutions based on our exclusive technology, IronChip Location-Based Security, that provides RF based anti-hackers geolocation. IronChip LBS allows companies to protect the digital identity along the value chain in which their employees, customers, suppliers, and logistics are located. For knowing more about Ironchip, please visit the Ironchip project website: https://www.ironchip.com


Documentation
-------------

The Ironchip project provides detailed [documentation] , installation and development guides.

[documentation]: https://helpcenter.ironchip.com/userdocumentation/


Ironchip Bug Tracker
===================

Reporting Issues
----------------

When reporting a bug, please include as much information as possible, this will help us solve the problem. Also, try to follow these guidelines as closely as possible, because they make it easier for people to work on the issue, and that means more chances that the issue gets fixed:

- **Be proactive**. If you are working with an old version of our products, please check with newer versions. We can't emphasize this enough: *it's the first thing that we are going to ask*.

- **Be curious**. Has it been asked before? Is it really a bug? Everybody hates duplicated reports. The Search tool is your friend!

- **Be precise**. Don't wander around your situation and go straight to the point, unless the context around it is technically required to understand what is going on. Describe as precisely as possible what you are doing and what is happening but you think that shouldn't happen.

- **Be specific**. Explain how to reproduce the problem, being very systematic about it: step by step, so others can reproduce the bug. Also, report *only one problem per opened issue*.


How to report a bug
-------------------

### Is it really a bug?

The first thing before reporting a bug, is to really make sure it is a bug. Many of the messages from the list are not bugs: coding issues, configuration problems... In order to make sure there is indeed a bug, you can follow this checklist:

* Read the documentation: If the answer is in the documentation, the answer will be "Read the documentation!"... one mail round wasted.

* Is it working on a different browser?

* Is there a tutorial that does exactly what you are trying to do? Check out the code from GitHub, run it in your machine and see what happens. Those tutorials are tested in our CI environment, so you can be quite certain they are in good shape.

* Check your pipeline. Make a drawing if you need to, but make sure everything is connected the way it should.

* Read the logs, they are normally quite interesting. Sometimes building tools are just not configured correctly or others have reported the same error. Client logs, server logs, build tool logs... For all of those, use Google!

### Ok, it's a bug. What now?

First of all, don't panic! There is still a small work to be done before reporting the bug:

* If it's an installation issue, don't touch anything! Normally when this happens, we tend to do random things that could only make things worse.

* Choose a bug header that fits the problem:

  * **_Bad_**: "I can't logging on the app. Help!"

  * **_Better_**: "XXX-dev not showing loopback video"

  * **_Best_**: "XXX 6.7.1-dev, 6.7.1-SNAPSHOT, Mac OSX, FF40: Can't see loopback video"

* Provide a good description of the problem, with the minimum relevant amount of information to reproduce and diagnose the bug

  * What steps will reproduce the problem?

  * What is the expected output?

  * What happens instead?

  * What are the specific versions of...

  * How is the system deployed?

  * Have you checked the development version?

* If you can provide a test application, please do so. 

* Provide the logs if they are relevant (i.e. 99% of the time).

For some specific type of bugs, there is some more information that you can provide:

* If the bug was recently introduced, finding a regression window can help identify the cause of the bug.

### So, how should a bug report look like?

* Title: Name clear the bug in less than 30 characters
  
* Preflight Checklist: 

* Version: Select the earliest Version with what the problem can be reproduced.
  
* Device Type: Which device Type are you using?

* Intallation Type: How did you install?
  
* Expected results.
  
* Actual results.
  
* Steps to reproduce.
  
* Description: The details of your problem report, including:

  * Overview.

  * Build Id.
  
  * Links
  
  * References
  
  * Logs



Licensing and distribution
--------------------------

Copyright 2021 Ironchip

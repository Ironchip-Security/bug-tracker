![GitHub issues](https://img.shields.io/github/issues/Ironchip-Security/bug-tracker?color=green&style=plastic)
![GitHub closed issues](https://img.shields.io/github/issues-closed/Ironchip-Security/bug-tracker?color=green&style=plastic)

<!--[![][IronchipImage]][Ironchip]-->

Copyright 2021 [Ironchip]. Licensed under [Apache 2.0 License].

[Ironchip]: https://www.ironchip.com/
[IronchipImage]: https://
[Apache 2.0 License]: http://www.apache.org/licenses/LICENSE-2.0



Ironchip Bug Tracker
===================

Reporting Issues
----------------

When reporting a bug, please include as much information as possible, this will help us solve the problem. Also, try to follow these guidelines as closely as possible, because they make it easier for people to work on the issue, and that means more chances that the issue gets fixed:

- **Be proactive**. If you are working with an old version of our products, please check with newer versions, specially with the [latest pre-release version](https://....). We can't emphasize this enough: *it's the first thing that we are going to ask*.

- **Be curious**. Has it been asked before? Is it really a bug? Everybody hates duplicated reports. The Search tool is your friend!

- **Be precise**. Don't wander around your situation and go straight to the point, unless the context around it is technically required to understand what is going on. Describe as precisely as possible what you are doing and what is happening but you think that shouldn't happen.

- **Be specific**. Explain how to reproduce the problem, being very systematic about it: step by step, so others can reproduce the bug. Also, report *only one problem per opened issue*.


How to report a bug
-------------------

### Is it really a bug?

The first thing before reporting a bug, is to really make sure it is a bug. Many of the messages from the list are not bugs: coding issues, configuration problems... In order to make sure there is indeed a bug, you can follow this checklist:

* Read the documentation: If the answer is in the documentation, the answer will be "Read the documentation!"... one mail round wasted.

* Check the documentation to test with the [latest pre-release version](https://doc../en/latest/user/installation_dev.html).

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

  * **_Best_**: "XXX 6.7.1-dev, magic-mirror 6.7.1-SNAPSHOT, Mac OSX, FF40: Can't see loopback video"

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

* Summary: How would you describe the bug in less than 60 characters?

* Version: Select the earliest Version with what the problem can be reproduced.

* OS: On which operating system (OS) did you find it?

* Description: The details of your problem report, including:

  * Overview.

  * Build Id.

* Steps to reproduce.

* Actual results.

* Expected results.



About Ironchip
=============

IronChip is a startup that creates cybersecurity solutions based on our exclusive technology, IronChip Location-Based Security, that provides RF based anti-hackers geolocation. IronChip LBS allows companies to protect the digital identity along the value chain in which their employees, customers, suppliers, and logistics are located. For knowing more about Ironchip, please visit the Ironchip project website: https://www.ironchip.com


Documentation
-------------

The Ironchip project provides detailed [documentation] , installation and development guides.

[documentation]: https://helpcenter.ironchip.com/userdocumentation/


Useful Links
------------

Usage:

* [Installation Guide](https://doc-/en/latest/user/installation.html)

Issues:

* [Bug Tracker](https://github.com/Ironchip-Security/bug-tracker/issues)
* [Support](https:// .... /user/support.html)

News:

* [Ironchip Blog](https://www/blog)



Source
------

All source code belonging to the Ironchip project can be found in the [Ironchip GitHub organization page].

[Ironchip GitHub organization page]: https://github.com/Ironchip



Licensing and distribution
--------------------------

Copyright 2021 Ironchip

Licensed under the Apache License, Version 2.0 (the "License");

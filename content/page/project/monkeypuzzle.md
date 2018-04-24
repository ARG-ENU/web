---
title: MonkeyPuzzle
subtitle: It all starts with argument analysis
comments: false
---

Much argumentation research begins with analysis of real world examples. Even as we move towards compuational argumentation systems, there is still much that can be learned from examining how people interact argumentatively. The MonkeyPuzzle tools aim to provide graphical interfaces to a suite of tools for analysing, storing, and working with argument resources.


Our tools come in two flavours, a Browser-hosted web application and a Desktop-based Java applications (which is essentially Araucaria built for a modern JVM).

The aim is to provide argument analysis tools that are not dependent upon the cloud or other people's computers so that, if you are a researcher or argument analyst you do not have to risk your workflow to the goodwill or longevity of third-party research organisations or commerical companies.

## Monkeypuzzle (Web)

A free (GPL), open-source, web-based (HTML5, CSS, Javascript) argument analysis tool.

![](/img/monkeypuzzle.png)


There is an ARG@ENU hosted instance:

* [http://arg.napier.ac.uk/monkeypuzzle/](http://arg.napier.ac.uk/monkeypuzzle/)

    
However you can also download Monkeypuzzle and run it from your local file system or from your own web-server. Deployment is primarily via one of the following three modes:

* As a hosted web-service
* As a local, non-server based single-page web-app
* As a browser-hosted, offline app

The source code for MonkeyPuzzle (web) is available from the [project repository](https://github.com/ARG-ENU/monkeypuzzle_web) which also hosts the [issue-tracker](https://github.com/ARG-ENU/monkeypuzzle_web/issues) to support ongoing developement. There is also a live, hosted version. 

## Monkeypuzzle (Desktop)

Araucaria was one of the first computer-based argument analysis tools, developed in 2001 at the University of Dundee. Unfortunately Arauacaria was not updated for many years, partly due to researchers moving to newer tools. However, Araucaria was the only GPL-licensed, pure argument analysis toolwhich meant that as other tools became "online only" or subscription based, Araucaria remained the only free, source-inclusive, argument analysis tool that analysts could run privately on their own machine. For many users, being able to perform private analyses of argumentation resources, for example, within research or legal argumentation, is critical, and externally hosted web-services are not an acceptable substitute.

As a result, Araucaria was adopted under it's GPL license, the code was added to a modern source-control repository, and regular builds were created to ensure that the tool will run under modern Java virtual machines. To celebrate this new lease of life, Araucaria was rebranded to Monkeypuzzle.


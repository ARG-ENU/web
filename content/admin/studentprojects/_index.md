---
title: Student Projects 
description: Just some ideas to get you started
#image: "images/author.jpg"
comments: false
---

# Undergraduate & Masters Projects

Projects generally fall into a number of groups depending upon your programme, skills, and interests but are usually either software engineering projects, data gathering & analysis projects, or research projects (usually involving the development of techniques for handling data & working out new things).

## Manual Argument Analysis

[Monkeypuzzle](/projects/monkeypuzzle) is a web-based tool that has been developed at ENU over the last few years. It currently support analysis of plain text and the visualisation of the results, but we'd like to extend this to deal with multi-modal arguments and arguments expressed in different media, for example, 

* analysing arguments from audio, such as SoundCloud recordings,
* video, such as Youtube videos, 
* websites, such as newspapers articles and blog posts,
* PDFs, because a lot of research outputs are published in this form.
* Support Leo Groarke's ART visual argument analysis method ([groarke_2019_depicting.visual.arguments](https://windsor.scholarsportal.info/omp/index.php/wsia/catalog/view/123/303/1653-1))

There are probably a whole bunch of other ways that the software could be extended such as support for analysing dialogical arguments, and once that is done, we also have a desktop version, written in Java, that needs a thorough overhaul. Projects in this area are more oriented towards software engineering processes.

## Argument Mining - Automated Argument Analysis

Argument Mining is the automatic detection, analysis, extraction, and reconstruction, of arguments from real world sources, basically from anything that might contain arguments, but primarily from text. A lot of argument and debate occurs through monological text, a person writes an article with the goal of persuading an audience. Often however, arguments explicitly involve multiple active participants, listening to what is said and, ideally, responding appropriately. Argumentative debate, of varying quality, occurs wherever people interact, and is increasingly occurring online.

Argument mining is a tough problem that is currently a hot research topic. Projects in this area are more research focussed and involve a balance of development of algorithms & tools, together with applying those tools to a small and well-defined problem. For example, a project might be:

* Canary is a new Python library for Argument Mining. Depending upon your degree programme, projects will involve either extending canary with the addition of new algorithms then evaluating & benchmarking them, or else developing new features for the library.
* PickAxe is a project that aims to provide a search interface for arguments. Projects related to this topic involve prototyping search-oriented user interfaces and APIS to argumentative data. 
* StripMine is a project to develop a pipeline of argument mining tools that can be pointed towards a given resource, e.g. a database, dataset, the web, common crawl, and which will extract structured argument data and store it in a database for reuse. Stripmine builds on other projects, for eaxmple, using algorithms from Canary, and user interfaces from PickAxe, together with off-the-shelf software to provide an end-to-end argument mining solution.
* Developing an algorithm to automatically detect periodic sentences, classify them as argument or non-argument, and convert them into argumentation structures that are saved using the [SADFace](/projects/sadface) format (developed at ENU). NB. Periodic sentences often encapsulate an entire argument, including premises and conclusion, into a single sentence, e.g. "The beach, with white sand, crystal clear water, and palm trees, is a favorite hangout for the locals." but they are problematic because they may have various forms, and sometimes the same form can express an argument and at other times the sentence does not contain an argument.
* Developing an algorithm to automatically detect overlaps between SADFace arguments. For example, two statements might express the same idea, but be presented in different ways. The aim of this project is to identify those instances so that these arguments can be combined.
* Integrate argument mining functionality into the [Monkeypuzzle](/projects/monkeypuzzle) (see above under "Manual Argument Analysis") tool. This way we can begin the process of moving from completely manual analysis, towards semi-automated, and eventually perhaps, completely automated operation.

## Argumentative Dialogue

Arguments are often discovered, constructed, elaborated upon, and exchanged during conversation. As a result dialogue is intimately related to argument. 

* Projects in this area can be focussed on formalising argumentative dialogue, for example as multi-player turn-taking games. Other projects can be focussed on using dialogue, perhaps via a chat-style interface to interact with argument data.
* Discursive is a new project aimed at developing a generalised argumentative chat interface that provides dialogical access to argumentative data.
* The Dialogue Game Description Language (DGDL) is a project that provides a domain specific language for describing the "rules" of different dialogues games. Projects can involve creating new DGDL rulesets, implementing them, and exploring their effects.
* A DGDL game description toolkit for producing new DGDL game descriptions. This might involve implementing a web-based user interface (or perhaps a Python & QT interface) to support the process of building and validating new games. The interface might enable a library of existing games to be built and maintained, perhaps used as the basis for creating new games. The output would be a DGDL description that could be used by ADAMANT.
* The Argumentative DiAlogue MANagement Tool (ADAMANT) is a project to provide a runtime engine for DGDL rules.
* Once you have rules to play by, you still need to decide what to say. Where there is choice over what to say there is an opportunity for strategy. Projects in this area will involve selecting a dialogue game and exploring various strategies for effectively playing that game.
* Jawbone: This is a project to develop a web-based tool for doing descriptive dialectic based analysis of dialogue. The idea is to take existing records of dialogues and to mark-up, and tease apart, all of the various actitivities that occur during the dialogue, for example, identifying the kind of things that are said (speech acts), the various ways that those speech acts link together as the dialogue develops, and identifying the effects, e.g. in terms obligations and commitments that result. The output will be a JSON file that describes the input dialogue from a descriptive dialectic perspective. Much previous research on dialectic has focussed upon "formal dialectic", that is, building sets of rules that describe ideal behaviour during a dialogue, but with descriptive dialectic we wish to focus upon real world behaviour.

## Dataset Construction & Analysis

Much AI work is dependent upon data and argumentation research is no exception. Collecting high-quality research datasets is difficult and time consuming and involves the development of experimental procedures, construction of tools to aid the process, and analysis of the data gathered. 

* The Argument Database (ArgDB) is a project that aims to provide a datastore, web interface, and API for analysed arguments represented using the SADFace format. The goal is for instances of ArgDB to be flexibly deployed on servers, and personal computers, in both public and private instances, and with full support for managing and federating argument data between instances. Projects in this area will involve designing, implementing, testing, and evaluating extensions to the ArgDB.
* Building an integrated dataset collection tool to support the RADAR (Reproducible Approach to Datasets for Argumentation Research) methodology. This could be a web or desktop based tool which supports and enables the user to construct their argumentative datasets according to the principles of the RADAR methodology.
* Projects in this theme will generally involve the design and construction of a web site that engages, and perhaps argues, with people with the aim of eliciting arguments and opinions that can be stored in our database of arguments, the [ArgDB](/projects/argdb)

## Abstract Argumentation

The computational approach to argumentation, often referred to as "abstract" or "formal" argumentation, studies how argumentative structure can be used to reason about knowledge, primarily in artificially intelligent software systems. [ALIAS](/projects/alias) (A Library for Implmenting Argumentation Systems) is an open-source Python library that has been developed to support abstract argumentation. The current version of ALIAS is approaching maturity, it works reasonably well and is easy to get started with but there is plenty of room for improvement in terms of performance. The library is currently reasonably performant on reasonably sized argumentation frameworks but this could be improved, both in terms of the size of frameworks that can be handled but also in terms of the time and space complexity of the solution (essentially the amount of memory consumed and the time take to reach a solution). There are a number of approaches that could be taken for a project in this area, for example:

* Investigate the use of solvers to calulate solutions. For example, some preliminary work using the Z3 solver has looked promising, and there is research in the literature on cutting edge SAT,SMT, & Constraint based solutions.
* Investigate the use of GPU programming as a method for improving performance.
* Adopt another technique from the literature that hasn't yet been incorporated into ALIAS - Projects in this area will likely follow a similar pattern of identifying a technique that might lead to an improvement, prototpying a solution, evaluating your solution against the existing ALIAS library & also against other tools submitted to the [ICCMA](http://argumentationcompetition.org) (International Competition on Computational Models of Argumentation).

## Argumentation & Dialogue Competition Entries

There are a number of competitions and shared tasks in the argumentation and dialogue research area. Students will select a challenge from either of the following:

* [ICCMA](http://argumentationcompetition.org) (International Competition on Computational Models of Argumentation)
* [Touche](https://touche.webis.de/)

Then you will produce your own entry that addresses the competition challenge or task. Entry into the competition isn't the main goal here, rather you should use the scenario as a starting place for your project. That said, should things work out nicely, and we feel that we'd have a competitive entry, then I would be supportive of also taking part, however the priorty is using the competitions and shared tasks as a starting place for building your own unique solution.

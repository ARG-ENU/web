---
title: Student Projects 
subtitle: Just some ideas to get you started
comments: false
---

## Undergraduate & Masters Projects

Projects generally fall into a number of groups depending upon your programme, skills, and interests but are usually either software engineering projects, data gathering & analysis projects, or research projects (usually involving the development of techniques for handling data & working out new things).

### Manual Argument Analysis

[Monkeypuzzle](http://arg.napier.ac.uk/monkeypuzzle) is a web-based tool that has been developed at ENU over the last few years. It currently support analysis of plain text and the visualisation of the results, but we'd like to extend this to deal with multi-modal arguments and arguments expressed in different media, for example, 

* analysing arguments from audio, such as soundclound recordings,
* video, such as youtube videos, 
* websites, such as newspapers articles and blog posts,
* PDFs, because a lot of research outputs are published in this form.

There are probably a whole bunch of other ways that the software could be extended such as support for analysing dialogical arguments, and once that is done, we also have a desktop version, written in Java, that needs a thorough overhaul. Projects in this area are more oriented towards software engineering processes.

### Argument Mining - Automated Argument Analysis

Argument Mining is the automatic detection, analysis, extraction, and reconstruction, of arguments from real world source, basically from anything that might contain arguments. This is a tough problem that is currently a hot research topic. Projects in this area are more research focussed and involve a balance of development of algorithms & tools, together with applying those tools to a small and well-defined problem. For example, a project might be:

* PickAxe is a new tool for Argument Mining processes and projects can involve extending pickaxe with the addition of new algorithms or approaches.
* StripMine is a new project that aims to support web search for arguments. Projects related to this involve prototyping search interfaces to argumentative data as well as indexing and mining web-resources in an efficient, robust, and accurate manner.
* Developing an algorithm to automatically detect periodic sentences, classify them as argument or non-argument, and convert them into argumentation structures that are saved using the [SADFace](/page/project/sadface) format (developed at ENU). NB. Periodic sentences often encapsulate an entire argument, including premises and conclusion, into a single sentence, e.g. "The beach, with white sand, crystal clear water, and palm trees, is a favorite hangout for the locals." but they are problematic because they may have various forms, and sometimes the same form can express an argument and at other times the sentence does not contain an argument.
* Developing an algorithm to automatically detect overlaps between SADFace arguments. For example, two statements might express the same idea, but be presented in different ways. The aim of this project is to identify those instances so that these arguments can be combined.

### Argumentative Dialogue

Arguments are often discoverd, constructed, elaborated upon, and exchanged during conversation. As a result dialogue is intimately related to argument. 

* Projects in this area can be focussed on formalising argumentative dialogue, for example as multi-player turn-taking games. Other projects can be focussed on using dialogue, perhaps via a chat-style interface to interact with argument data.
* Discursive is a new project aimed at developing a generalised argumentative chat interface that provides dialogical access to argumentative data.
* The Dialogue Game Description Language (DGDL) is a project that provides a domain specific language for describing the "rules" of different dialogues games. These are then . Projects can involve creating new DGDL rulesets, implementing them, and exploring their effects.
* The Argumentative DiAlogue MANagement Tool (ADAMANT) is a project to provide a runtime engine for DGDL rules.
* Once you have rules to play by, you still need to decide what to say. Where there is choice over what to say there is an opportunity for strategy. Projects in this area will involve selecting a dialogue game and exploring various strategies for effectiely playing that game.

### Dataset Construction & Analysis

Much AI work is dependent upon data and argumentation research is no exception. Collecting high-quality research datasets is difficult and time consuming and involves the development of experimental procedures, construction of tools to aid the process, and analysis of the data gathered. 

* Projects in this theme will generally involve the design and construction of a web site that engages, and perhaps argues, with people with the aim of eliciting arguments and opinions that can be stored in our database of arguments, the [ArgDB](/page/project/argdb)
* The Argument Database (ArgDB) is a project that aims to provide a datastore, web interface, and API for analysed arguments represented using the SADFace format. The goal is for instances of ArgDB to be flexibly deployed on servers, and personal computers, in both public and private instances, and with full support for managing and federating argument data between instances. Projects in this area will involve designing, implementing, testing, and evaluating extensions to the ArgDB.

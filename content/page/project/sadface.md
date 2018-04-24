---
title: SADFace
subtitle: The Simple Argument Description Format
comments: false
---

SADFace is a simple JSON based Argument description format, software library, and supporting tools to enable developers and researchers to describe arguments then easily reuse their data. The goal is to make it as easy as possible to incorporate argument data into modern software.

There are a number of argument description and markup languages, for example, the Argument Markup Language (AML) and the Argument Interchange Format (AIF). Both have their advantages and disadvantages, AML is a simple tree-based format, but is a pain to parse, and requires an XML toolchain, something that is falling out of favour amongst main-stream web toolchains. AIF on the other hand provides an excellent, extensible high-level ontology for representing arguments, dialogues, schemes, and many peripherally related concepts. However with AIF that flexibility has the price of opaque terminology and complexity, both in terms of underlying model and in terms of the required RDF toolchain. Where both of these formats fail is in the documentation and support for users who want to work with them,

SADFace seeks to address the drawbacks of other formats. It has:

* A simple underlying but extensible model that is compatible with AIF
* Clear extension points for domain specific analysis & representation tasks
* Tooling to support import from other formats, e.g. AML
* An open source canonical implementation
* Documentation
* Supporting tools for SADFace document creation, editing, and manipulation
* [Liberal (GPL3) licensing](https://github.com/ARG-ENU/SADFace/blob/master/LICENSE)
* [Git Repository](https://github.com/ARG-ENU/SADFace)
* [Open development Model](https://github.com/ARG-ENU/SADFace/issues)

For further information, visit the SADFace project page: 

* [https://github.com/ARG-ENU/SADFace](https://github.com/ARG-ENU/SADFace)

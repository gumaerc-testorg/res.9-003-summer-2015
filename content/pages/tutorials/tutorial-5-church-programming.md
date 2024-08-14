---
content_type: page
description: This page presents a video-based tutorial on using the Church programming
  language.
draft: false
is_media_gallery: true
learning_resource_types:
- Tutorials
ocw_type: SupplementalResourceSection
parent_title: Tutorials
parent_type: SupplementalResourceSection
parent_uid: 1991b27f-a447-8dc0-a6a2-79748088784f
title: 'Tutorial 5: Church Programming'
uid: 32907aca-b7d5-1972-49b3-b36fb769ce08
video_metadata:
  youtube_id: null
videos:
  content:
  - 3953a4fd-a909-910d-c0f2-697c6200da75
  - 1af5546c-cd66-7684-1fc9-19a46a77ff9b
  website: res-9-003-brains-minds-and-machines-summer-course-summer-2015
---
## Tutorial Overview

{{< tableopen >}}{{< tbodyopen >}}{{< tropen >}}{{< tdopen >}}
{{< resource uuid="20b84384-fbe1-fff3-7d7e-31991157e720" >}}
{{< tdclose >}}{{< tdopen >}}
Josh Tenenbaum and colleagues propose that our intuitions about properties like the stability of a stack of blocks, may derive from "probabilistic programs" that can simulate, with some uncertainty, the physics that governs how objects behave in space and time. Such programs can be implemented and tested using probabilistic programming languages such as the Church language. (Image courtesy of Josh Tenenbaum, used with permission.)
{{< tdclose >}}{{< trclose >}}{{< tbodyclose >}}{{< tableclose >}}

The unit on modeling human cognition introduced a framework based on the creation of generative models of the physical and social worlds that enable probabilistic inference about objects, agents, and events. The Church programming language was designed to facilitate the implementation and testing of such models. In this tutorial, you will first learn the syntax and some basic primitives of the Church language, and how to define functions that implement simple probabilistic models and inference methods. The concepts are then explored through examples such as hypothesis testing in the domain of coin-flipping, and reasoning about the goals and beliefs of an agent.

## Unit Activities

### Useful Background

- Introductions to probability and probabilistic approaches to modeling behavior
- {{% resource_link "855d4e86-2ca9-e529-74f0-cdef3de9e9c0" "Video lectures" %}} on computational models of cognition by Josh Tenenbaum
- Introduction to computer programming

### Videos and Slides

{{< video-gallery "32907aca-b7d5-1972-49b3-b36fb769ce08" >}}

### Code

{{% resource_link "3a08df29-46c9-1378-cf03-d672fec3e037" "Church\_examples (RTF)" %}} contains the code examples described in the two-part tutorial video. These examples can be executed by copying the code into one of the following Church programming environments. Code can also be written from scratch and modified in these environments:

1. First edition of the [Probabilistic Models of Cognition](http://v1.probmods.org/) electronic text, cited in the section below on *Future Study*, which includes a separate [Play space](http://v1.probmods.org/play-space.html) where code can be copied, modified, and executed
2. [webchurch engine](https://github.com/probmods/webchurch) that runs Church code in a web browser, which is available on GitHub for download onto your local computer

### Further Study

Goodman, N. D., and J. B. Tenenbaum. [*Probabilistic Models of Cognition, First Edition*](http://v1.probmods.org/) (electronic).

- This interactive text introduces many probabilistic modeling techniques and contains an embedded Church programming environment with coding examples throughout the text that can be modified and executed in place. The text also includes a separate [Play space](http://v1.probmods.org/play-space.html) and [Church language reference](http://v1.probmods.org/webchurch/online/ref.html).

Goodman, N. D, and J. B. Tenenbaum. [*Probabilistic Models of Cognition, Second Edition*](https://probmods.org/) (electronic). With programming exercises written in the web-based probabilistic programming language, [WebPPL](http://webppl.org/).

Goodman, N. D., and A. Stuhlmüller. [*The Design and Implementation of Probabilistic Programming Languages*](http://dippl.org/). (electronic)

- This online text describes how probablistic programming languages (PPLs) can be embedded in other languages, and introduces the [WebPPL](http://webppl.org) language, a web-based PPL embedded in JavaScript.

[forestdb.org](http://forestdb.org/): A repository of probabilistic models implemented in the Church language

The Church language is one of several probabilistic programming languages. Learn more about such languages at the [Probabilistic-Programming wiki](https://en.wikipedia.org/wiki/Probabilistic_programming).
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

1. First edition of the {{% resource_link "dd11a75f-08cd-4a34-8b0a-47f1c57eb0da" "Probabilistic Models of Cognition" %}} electronic text, cited in the section below on *Future Study*, which includes a separate {{% resource_link "4f2c63f6-a63d-4043-acfc-5d68a36bb2ec" "Play space" %}} where code can be copied, modified, and executed
2. {{% resource_link "54fa8962-7b07-4f71-be3e-70c883b22872" "webchurch engine" %}} that runs Church code in a web browser, which is available on GitHub for download onto your local computer

### Further Study

Goodman, N. D., and J. B. Tenenbaum. {{% resource_link "dd11a75f-08cd-4a34-8b0a-47f1c57eb0da" "*Probabilistic Models of Cognition, First Edition*" %}} (electronic).

- This interactive text introduces many probabilistic modeling techniques and contains an embedded Church programming environment with coding examples throughout the text that can be modified and executed in place. The text also includes a separate {{% resource_link "4f2c63f6-a63d-4043-acfc-5d68a36bb2ec" "Play space" %}} and {{% resource_link "1d3e32aa-2f6a-4088-8789-32299bda42ec" "Church language reference" %}}.

Goodman, N. D, and J. B. Tenenbaum. {{% resource_link "cf9d6445-8d5b-43e0-bf7e-b88b92bb5ae2" "*Probabilistic Models of Cognition, Second Edition*" %}} (electronic). With programming exercises written in the web-based probabilistic programming language, {{% resource_link "6565fe12-b062-44dc-8406-87661e4c6aad" "WebPPL" %}}.

Goodman, N. D., and A. Stuhlmüller. {{% resource_link "e4c12c4d-43a1-4e41-9cfc-348befcd9ef8" "*The Design and Implementation of Probabilistic Programming Languages*" %}}. (electronic)

- This online text describes how probablistic programming languages (PPLs) can be embedded in other languages, and introduces the {{% resource_link "a6de9250-985b-4e38-85c5-4faeb7939ccf" "WebPPL" %}} language, a web-based PPL embedded in JavaScript.

{{% resource_link "b4a69d30-de31-4fca-b3f8-fd1adb55ec09" "forestdb.org" %}}: A repository of probabilistic models implemented in the Church language

The Church language is one of several probabilistic programming languages. Learn more about such languages at the {{% resource_link "b88f0d1a-6879-4d3e-89ab-8afa3ae0b158" "Probabilistic-Programming wiki" %}}.
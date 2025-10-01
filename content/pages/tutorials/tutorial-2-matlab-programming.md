---
content_type: page
description: This section contains a tutorial overview of MATLAB.
draft: false
learning_resource_types:
- Tutorials
ocw_type: SupplementalResourceSection
parent_title: Tutorials
parent_type: SupplementalResourceSection
parent_uid: 1991b27f-a447-8dc0-a6a2-79748088784f
title: Tutorial 2. MATLAB Programming
uid: 8cd0ca9a-ec53-9f73-3f4c-198c13784445
video_metadata:
  youtube_id: null
---
## Tutorial Overview

{{< tableopen >}}{{< tbodyopen >}}{{< tropen >}}{{< tdopen >}}
{{< resource uuid="6a56f248-a906-0b47-36be-54fe2d2df916" >}}
{{< tdclose >}}{{< tdopen >}}
One MATLAB{{< sup "®" >}} tutorial exercise explores how the retinal image (upper left) is processed by neurons in the early stages of the visual pathway. This processing can be modeled as convolution with spatial filters that incorporate Gaussian smoothing (upper right). The result of retinal processing can be described as convolution with the difference of two Gaussians that form a center-surround spatial structure (lower left). The spatial receptive fields of neurons in visual cortex can be described as an oriented Gabor filter, producing results such as that shown for an oblique orientation in the lower right.
{{< tdclose >}}{{< trclose >}}{{< tbodyclose >}}{{< tableclose >}}

MATLAB is a powerful technical computing environment that is used extensively in the research described in this course. MATLAB programs are used, for example, to conduct experiments and gather data, analyze and visualize data, and implement computational models. This tutorial is intended for students who already have computer programming background and want to learn some of the basic elements of the MATLAB language and how it can be applied to sample problems in computational neuroscience.

## Unit Activities

NOTE: There are no videos for this tutorial.

### Useful Background

- Introduction to computer programming, linear algebra
- The MATLAB technical computing environment can be purchased from {{% resource_link "1104dbb5-a199-4734-91a5-373ab81d352c" "MathWorks, Inc" %}}.
- The free {{% resource_link "12bbb110-e58e-4579-819e-ee3f5e1e98c9" "GNU Octave Scientific Programming Language" %}} is largely compatible with MATLAB and can be used to run the MATLAB examples in this tutorial.

### MATLAB Introduction

- The tutorial document below, which was originally prepared by Mark Goldman (UC Davis) and extended by Daniel Zysman (MIT), provides an introduction to aspects of MATLAB that are used in the programming exercises provided in this tutorial.

{{< tableopen >}}{{< tbodyopen >}}{{< tropen >}}{{< tdopen >}}
{{% resource_link "d82a14ff-eb24-f8c7-7cc2-2bf263ebc6b2" "MATLAB: Goldman / Zysman Introductory Tutorial (PDF)" %}}
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "52492f21-0c06-9355-cb77-f6deb63fd26c" "Code + data files for these tutorial examples (ZIP)" %}} (This ZIP file contains: 8 .m files and 1 .mat file)
{{< tdclose >}}{{< trclose >}}{{< tbodyclose >}}{{< tableclose >}}

Some additional resources for learning MATLAB are listed in the section on *Future Study*. You can also view a 5-minute video introduction to MATLAB by entering the following expression in the MATLAB Command window:

`playbackdemo('GettingStartedwithMATLAB', 'toolbox/matlab/demos/html')`

### MATLAB Programming Exercises

The table below provides descriptions of programming exercises, supporting code and data files, and solution code. They were prepared by Daniel Zysman and Ellen Hildreth, based on some material from the 2014 summer course originally developed by Emily Mackevicius.

{{< tableopen >}}{{< theadopen >}}{{< tropen >}}{{< thopen >}}
EXERCISES
{{< thclose >}}{{< thopen >}}
SOLUTIONS 
{{< thclose >}}{{< trclose >}}{{< theadclose >}}{{< tbodyopen >}}{{< tropen >}}{{< tdopen >}}
{{% resource_link "648f1cb2-7eae-f772-14a0-d25c5a8abe23" "Feedforward neural networks for digital character recognition (ZIP - 2.3MB)" %}} (This ZIP file contains: 1 .doc file and 1 .mat file)
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "ad9a22d9-d1c1-3e98-5072-17c27b01448c" "Solutions (ZIP)" %}} (This ZIP file contains: 2 .m files)
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
{{% resource_link "2dc82de9-7261-a579-c89b-1c4cebf23856" "Spatial processing in the visual pathway (PDF)" %}}
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "3c115c12-08c9-a715-8cac-8983b4250741" "Solutions (ZIP)" %}} (This ZIP file contains: 4 .m files)
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
{{% resource_link "bea7cfe5-2f23-5cc9-7c94-9990df7fb0e3" "Integrate and fire model of neural activation (PDF)" %}}
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "c06d530a-0768-8ecc-a294-e621a9a84687" "Solutions (ZIP)" %}} (This ZIP file contains: 6 .m files)
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
{{% resource_link "cb79871e-e4f1-4cd8-5caa-452f4a859f05" "Spike-triggered averaging of neural responses: Handout and data (ZIP - 2.1MB)" %}} (This ZIP file contains: 1 .doc file and 1 .mat file)
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "89182fc0-d992-b5e8-5789-2eeeff4803fe" "Solutions (ZIP - 1.9MB)" %}} (This ZIP file contains: 2 .m files and 1 .mat file)
{{< tdclose >}}{{< trclose >}}{{< tbodyclose >}}{{< tableclose >}}

## Further Study

Attaway, S. *MATLAB: A Practical Introduction to Programming and Problem Solving*. Butterworth-Heinemann, 2013. ISBN: 9780124058767. \[Preview with {{% resource_link "ba1ee9c0-da08-4c19-94d8-a30fec7702de" "Google Books" %}}\]

{{% resource_link "a80f8e45-c184-4ae5-9d74-5b71d082de78" "![Buy at MIT Press](/images/mp_logo.gif)" %}} Cohen, M. X. {{% resource_link "a80f8e45-c184-4ae5-9d74-5b71d082de78" "*MATLAB for Brain and Cognitive Scientists*" %}}. MIT Press, 2017. ISBN: 9780262035828.

Gilat, A. *MATLAB: An Introduction with Applications, Fifth Edition*. Wiley, 2014. ISBN: 9781118629864.

Goldman, M. *Tutorials in Computational Neuroscience*.

Gore, J., P. Blainey, E. S. Lander, E. Fraenkel, M. E. Wiltrout, N. Schafheimer. {{% resource_link "c03e8ad6-bcf6-4e99-af8e-220e6b4dd74f" "*Quantitative Biology Workshop*" %}}. Self-paced online course from MITx on edX.

Hanselman, D. C., and B. L. Littlefield. *Mastering MATLAB*. Pearson, 2012. ISBN: 9780136013303.

Mathworks, Inc. {{% resource_link "87c5c9a6-46fc-4599-8617-85334857fe42" "MATLAB tutorials, including MATLAB Onramp" %}}, and {{% resource_link "767ac739-1939-448f-be11-255573b47b62" "MATLAB documentation" %}}, including a {{% resource_link "a525a885-1a21-46d5-b892-1f7723256ccb" "MATLAB Primer (PDF - 2.4MB)" %}}.

Šćepanović, Danilo. {{% resource_link "d5b10cd5-405b-42ba-8d30-f834bac42d56" "*6.094 Introduction to MATLAB*" %}}, January 2010. MIT OpenCourseWare.

Science Education Resource Center, Carleton College. {{% resource_link "55d3f9a9-b6d3-450d-926d-f7ede8c36cec" "*Teaching Computation in the Sciences*" %}}.

Springer, M., and R. Born. {{% resource_link "24bde7c4-178a-4ef3-86c3-3352289ff949" "*Boot Camp in Quantitative Methods*" %}}, based on the course *Neurobiology 306qc: Quantitative Methods for Biologists* taught at Harvard University.

Wallisch, P., M. Lusignan, et al. *MATLAB for Neuroscientists: An Introduction to Scientific Computing in MATLAB\_*, Second Edition\_. Academic Press, 2008. ISBN: 9780123745514.
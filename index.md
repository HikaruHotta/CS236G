---
layout: default
keywords:
title: CS236G Generative Adversarial Networks (GANs)
description: GANs have rapidly emerged as the state-of-the-art technique in realistic image generation. Its applications span realistic image editing that is omnipresent in popular app filters, enabling tumor classification under low data schemes in medicine, and visualizing realistic scenarios of climate change destruction. You'll also get to examine key challenges of GANs today, including reliable evaluation, inherent biases, and training stability. After this course, students should be familiar with GANs and the broader generative models and machine learning contexts in which these models are situated. 
buttons: [syllabus, piazza, video]
micro_nav: true
add_gif: gans_demo_2.gif
add_webp: gans_demo_2.webp
show_lecture_time: true
---

## Course Information
- This quarter ({{ site.course.quarter }}), CS236G meets for in-class lecture {{ site.course.time}}, {{ site.course.venue }}.
- All class communication happens on the [CS236G Piazza forum]({{ site.course.piazza }}). For private matters, please make a private note visible only to the course instructors. For longer discussions with TAs and to get help in person, we strongly encourage you to come to office hours. If you need to contact us via email, please email individual TAs.
- The course content and deadlines for all assignments are listed in our [syllabus](/syllabus).
- For general inquiries, please contact <{{ site.course.qa }}>.

<!-- Course Staff -->
{% include staff.html %}


## Course Goals
- Learn and build generative adversarial networks (GANs), from their simplest form to state-of-the-art models. 
- Implement, debug, and train GANs as part of a novel and substantial course project.
- Gaining familiarity with the latest cutting-edge literature on GANs.
- Reward risk-taking and creative exploration.

## Course Components
* In class lectures - twice a week on {{ site.course.time}} (hosted on {{ site.course.venue }}). 
* Video lectures, programming assignments, and quizzes on Coursera
* [The final project](/project)

## Lecture Schedule <a name="table"></a>

| Date | Week | Title |     Resources    | Instructor |
|------|:----:|:-----:|:----------------:|------------|
| 01/12/2021 | 1 | **Introduction** | [Slides](https://drive.google.com/file/d/1Hm_EOtZm94C9OARpkfeALd7pLmp3B9_5/view?usp=sharing)<br /> [Video](https://stanford-pilot.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=37811af7-b22c-417a-85d0-acae01804b1a) |Sharon Zhou |
| 01/19/2021 | 2 | **Disentanglement** | [Slides](https://drive.google.com/file/d/1PdxqnUtSjwXZS3R-eK3T67IpUVbqup0l/view?usp=sharing)<br />[Video](https://stanford-pilot.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=f463c8e0-bc3a-4e41-9118-acb5017eb6c7) | Sharon Zhou |
| 01/21/2021 | 2 | **Artbreeder** | [artbreeder.com](https://www.artbreeder.com/)<br />[Video](https://stanford-pilot.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=856ca6b4-3ad2-4109-a8dd-acb800013d58) | Joel Simon |
| 01/28/2021 | 3 | **Medicine + GANs** | [Video](https://stanford-pilot.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=aa7885c2-d78e-4aab-944a-acbd00112be0) | Sharon's Research Group |
| 01/30/2021 | 3 | **Project Inspo** | | Sharon Zhou |
| 02/05/2021 | 4 | **Finding Project Partners** | | Sharon Zhou |
| 02/07/2021 | 4 | **How to Read a Paper** | [Slides](https://drive.google.com/file/d/1sV_wVEYQIQk4UVjkFZbka33z8KJONuUU/view?usp=sharing)<br />[Video](https://stanford-pilot.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=34486a24-962c-44ab-8aac-acc5017c7ad5) | Sharon Zhou |
| 02/09/2021 | 5 | **Reading Group** | [Paper](https://arxiv.org/abs/2007.15646)<br />[Video](https://stanford-pilot.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=9ac03b9a-6219-4270-bde5-acca01843fc4) | Sharon Zhou |
| 02/11/2021 | 5 | **PyTorch for GANs** Part 1 | [Notebook](https://colab.research.google.com/drive/1YkPs4N886UIeIKULWUidmRlqg67OddNd?usp=sharing)<br />[Video](https://stanford-pilot.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=63d07b90-5790-4fd7-a891-accc0182bae6) | Hikaru Hotta<br />Vincent Liu |
| 02/18/2021 | 6 | **PyTorch for GANs** Part 2 | [Notebook](https://colab.research.google.com/drive/1_V9KhDwM0x9cNzMarF7Yd6IJoUHhIkPo?usp=sharing)<br />[GAN Starter Notebook](https://colab.research.google.com/drive/1q2eX8jY4269ITK48OAA14d-qARcGoEAo?usp=sharing)<br />[AWS Instructions](https://docs.google.com/document/d/1JvNcl8WXPGt5rPqWYlIcIePd_ov0FveXyGZlXn3Vc2Y/edit?usp=sharing)<br />[Video](https://stanford-pilot.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=d61a4316-f7bd-47d3-9473-acd3018728f1) | Hikaru Hotta<br />Vincent Liu |
| 02/23/2021 | 7 | **Speech + GANs** | [Slides](https://drive.google.com/file/d/1yFxG5ivj1h3BNmbP_2wxSzS13y1QKG3j/view?usp=sharing)<br />[Video](https://stanford-pilot.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=a23ae515-2450-4081-9859-acd90064a411) | Vincent Liu |
| 02/25/2021 | 7 | **Differential Privacy** | [Slides](https://drive.google.com/file/d/11MOqUO7fuMBKL2rnVCsYRVSdoqbT8gna/view?usp=sharing)<br />[Video](https://stanford-pilot.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=7947a495-4635-456f-9f59-acdb00065b14) | Tim Gianitsos |
| 03/02/2021 | 8 | **Pix2PixHD** | [Notebook](https://colab.research.google.com/drive/11E-YhRUAMMdzjN70ee9N08q6eRAX338r?usp=sharing)<br />[Video](https://stanford-pilot.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=f46f57b3-9163-453f-960e-ace00120c732) | Hikaru Hotta<br />Silvia Gong<br />William Zhuk |
| 03/04/2021 | 8 | **Interim Project Showcase** | [Video](https://stanford-pilot.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=a14cc012-2bc5-47ae-b69d-ace200038969) | Sharon Zhou |
| 03/09/2021 | 9 | **Video + GANs** | | Sharon Zhou |
| 03/11/2021 | 9 | **Text + GANs** | | Sharon Zhou |
| 03/16/2021 | 10 | **Project Showcase** | | Sharon Zhou |
| 03/18/2021 | 10 | **Project Showcase** | | Sharon Zhou |

## Prerequisites
Students are expected to have the following background:
 * Familiarity with basic programming (CS106B or CS101)
 * Familiarity with basics of deep learning (CS230 or CS221)
 * Familiarity with the probability theory (CS 109 or STATS 116)
 * Familiarity with linear algebra (MATH 51)

## Grading
 
* 60%: Class project - creativity and equal participation within a group will be rewarded
* 35%: Programming assignments
* 5%: Midterm
* 0%: Attendance
* Extra credit: Your (or your GAN-generated) Memes. Requirements: Relevant and Appropriate with capital R and A there.

## Auditing

All students who are looking to audit the course should complete and submit the following [form](https://forms.gle/bynot3sy8smWKf2V8). You should receive an invitation to the course's Canvas and the Coursera course in your Stanford email within 24-48 hours of submitting this form. Make a private piazza post (preferred) or email <{{ site.course.qa }}> if you did receive get the invitations.

This site was forked from CS230: Deep Learning (https://CS230.stanford.edu).

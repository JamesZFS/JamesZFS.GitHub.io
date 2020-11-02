---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
Here's a pdf version of my [CV](xxx)

Education
======
Undergraduate at Tsinghua University(THU), Beijing, China
* Majored in Physics Department, 2016 - 2018
* Changed major into Computer Science and Technology Department, 2018 - 2021
* Expected to graduate in July, 2021
* Major GPA:   **3.91**  Rank: **2**/225
* Overall GPA: **3.89**  Rank: **4**/225

SCHOLARSHIP & AWARDS
======
* China National Scholarship (Top 1%), 10/2020
* Comprehensive Excellence Scholarship (Top 7%) at Computer Science and Technology Department, THU, 10/2019
* Comprehensive Excellence Scholarship (Top 10%) at Physics Department, THU, 10/2017
* National Silver Prize, National Olympiad in Physics, 2015
* Provincial Second Prize, National Olympiad in Informatics, 2014

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Internship Experience
======
### Graphics Programmer at Bytedance, Summer 2019
* Product RD and Infrastructure, Bytedance Game Department
* Implemented a mobile-phone next-generation water/pool graphics effect solution based on the Unity Engine independently
* Features: 
  - **Ray tracing** based water rendering
  - **GPU-level parallel** water wave simulation and real time caustics computation
  - Screen space underwater effects and water-ball interaction
  - Consistent with Unity's built-in shadowmap and lightmap
* Did a technical presentation among my leader and colleagues and received **supreme judgment**

Research Experience
======

### Graphics and Geometric Computing Group, THU
* Advised by [Prof. Kun Xu](https://cg.cs.tsinghua.edu.cn/people/~kun/), 10/2019 - Present
* Commercial project for Alibaba: enhancement to a renderer based on NVIDIA’s Optix library
  - Added useful features like accepting/casting shadows, primary visibility to the renderer
  - Parsed camera and scene geometric information from FBX files
  - Implemented a shadowmap computing algorithm
* Academic research: a consistent denoising algorithm for Monte Carlo rendering (on-going)
  - Derived the problem's mathematical formula
  - Did in-depth research and found a variant of conjugate gradient algorithm to solve the problem efficiently and effectively

### Pervasive Human-Computer Interaction Group, THU
* Advised by [Prof. Chun Yu](http://pi.cs.tsinghua.edu.cn/lab/people/ChunYu/), 01/2019 - 05/2019
* Published *ProxiTalk: Activate Speech Input by Bringing Smartphone to the Mouth* to IMWUT 2019
* Main duties:
  - Second student author
  - Handled part of the image/voice data processing and analyzing work
  - Tackle the gesture recognition problem with neural and tradition machine learning methods
  - Conducted a 20-user data collecting experiment and a 60-user evaluation experiment

Selected Course Performance
======

### Fundamentals of Computer Graphics (A)
* Implemented a C++ physically-based CPU renderer
* [Project repo](https://github.com/JamesZFS/Pharosa)
* Highlighted features:
  - Incorporates a vector/matrix math library without external library support
  - Supports the path tracing and the **stochastic progressive photon mapping** global illumination algorithm
  - Supports the KD tree scene acceleration structure and complex triangle mesh scene files
  - A flexible and extensible system strictly following object oriented principles

### Human-Computer Interaction Theory and Technology (A-)
* Proposed and researched on a mobile phone camera interaction app - *IntelliZoomer*
* [Project repo](https://github.com/JamesZFS/IntelliZoomer)
* Leader of a three-student group
* Core features:
  - Exploits the distance information from front camera to adjust the back camera's zoom ratio
  - Detects the smiling gesture of the user to trigger "capture"
  - Integrates iPhone 11's state-of-the-art multi-camera session and vision techniques
* Conducted a 14-user evaluation experiment and proved our proposed app's advantages over current camera apps.
* Enrolled in the most prestige science & innovation competition in THU - "**The Challenge Cup**" - and won the third prize

### Service Oriented Software Design and Development (A+)
* Designed and implemented an intelligent COVID-19 data visualizing & analyzing system - *AntiNCP*
* [Our website](http://129.204.207.38/#)
* In charge of backend construction, algorithm integration, operation & maintenance and UI framework design
* Highlighted features:
  - Collects pandemic data and news articles automatically and periodically
  - Extract trend words and topics from articles using Tf·Idf model and clustering algorithms
* Achieved the **highest completion** among all groups in the course
* Served **more than 6,000 users** till now

### Software Engineering (A)
* Implemented an online live teaching platform for Jisuanke Company
* Made core contribution in the group and impressed the clients
* [Project repo](https://github.com/JamesZFS/AwesomeCoding)
* Became one of the **teaching assistants** of this course in the second year
  - Helped my peer students learn the essence of software developing principles (git cooperation, code style, etc.)
  - Guided 5 groups on developing a cloud resource computing and task execution platform

### Computer Organization (A-)
* Designed a MIPS32 CPU in Verilog with 2 other students
* [Project repo](https://github.com/JamesZFS/MIPS-CPUer)
* Highlighted features:
  - Supports around 30 kinds of basic and interruptive MIPS32 instructions
  - Supports several peripherals including DVI video output and flash storage
  - Contains a fixed-point numerical system and a **three-body problem** simulator/visualizer in MIPS assembly

### Principles and Practice of Compiler Construction (A)
* Enhanced a decaf language compiler implemented in Rust
* [Project repo](https://github.com/JamesZFS/Decaf)
* Added **functional programming** features to the basic decaf grammar (such as lambda expressions and first-class functions)
* Added some compiling optimization actions along with an implementation of a renowned iterative global register allocation algorithm

### Foundation of Object-Oriented Programming (A)
* Designed and implemented two **physically-based** 2D games
* [Project 1 repo](https://github.com/JamesZFS/Warzone), [Project 2 repo](https://github.com/JamesZFS/Plongeur)
* Based on Qt and Google’s LiquidFun physics library

Skills
======
* Programming skills
  - Master C, C++, Python, JavaScript
  - Familiar with Go, Rust, MySQL, Swift, C#, Assembly, Mathematica, Unity
* Language skills
  - Mother tongue: Chinese
  - TOEFL xxx
  - GRE Verbal 156, Quantitative169, AW 4.0
  - A little French
* Hobbies & others
  - Swimming, fitness, diving, skiing
  - Saxophone, piano, chorus, a cappella, musical

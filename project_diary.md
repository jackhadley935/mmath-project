# Project Diary

## Week commencing - 5th October

### Tasks for the week:
1. Begin analysing the base paper. `*`
2. Gain an understanding of wave equations and the methods to solve them.

### Actions taken towards tasks:
1. Read the paper multiple times, gaining further insight after each iteration. Knowledge of the methods used in the paper has been extended, including modelling decisions and the main idea behind taking eigenvalues of the second order differential operator.
2. After watching videos and examining other online resources, I have a more fluent understanding of these equations, and am aware of methods to solve them, e.g. using Fourier series.

### Discussions during supervision meeting:
- Supervisor clarified some aspects of the paper, and some methods used, including the spectral method of obtaining eigenvalues of a differential operator.
- He provided resources to learn more about other methods and how to implement them in Python using the firedrake library.
- He gave a practical demonstration of the concept using a musical saw to illustrate the effect of tension on the frequency of a wave.

### Effect on coming weeks:
- Next week, I will be continuing to research and understand the base paper, but will also try to get a python program running to obtain eigenvalues using the firedrake library. 
- In the coming weeks, I will use this program to attempt to replicate the findings of the paper, using similar and different methods.
- I will decide on a direction to take this project, culminating to form the project description document.

<sup>`*` V.E Howle, Lloyd N Trefethen, Eigenvalues and musical instruments, Journal of Computational and Applied Mathematics, Volume 135, Issue 1, 2001, Pages 23-40,ISSN 0377-0427, https://doi.org/10.1016/S0377-0427(00)00560-4 <sup>

## Week commencing – 12th October

### Tasks for the week:
1. Investigate the finite element method.
2. Install and use firedrake to create a program to solve wave equations.
3. Set up a GitHub Repository to collate my work.

### Actions taken towards tasks:
1. I read through a guide to implementing the finite element method and understand in a loose capacity. The method seems possible to reproduce in python.
2. Due to a complication on my part, I could not install the library. I was unaware that the install was different to installing any other library, but firedrake is not officially supported on Windows.
3. The repository was created, and my supervisor has viewing access.

### Discussions during supervision meeting:
- Supervisor suggested the use of a docker to allow me to use firedrake without a lengthy installation process in the short term.
- He provided resources to learn more about the FEM, including training exercises to gain more experience with the implementation.
- We spoke of the direction of the project, with the project description document deadline in the next week. This could include implementing the FEM over multiple dimensions, but I would like to do more research before committing to a concrete plan.

### Effect on coming weeks:
- Next week, I will be continuing to research and understand the base paper, and FEM.
- I will investigate the use of a docker to utilise firedrake, or otherwise install it.
- Submit the project description document.
- Investigate implementation of FEM in python.

## Week commencing – 19th October

### Tasks for the week:
1. Understand the FEM and implement a small one-dimensional prototype.
2. Create and submit the project description document.

### Actions taken towards tasks:
1. The guide was read a few times, and I asked my supervisor to help clarify a couple of parts that were unclear. The prototype was started, with the basic building blocks implemented.
2. Completed and submitted.

### Discussions during supervision meeting:
- Supervisor clarified some notation that I was struggling with, and clarified a few steps that I wasn't grasping.
- He also gave helpful feedback to my code, critiquing a couple of the functions and the long term format of the program, suggesting a course to improve my coding structure. He suggested the use of `pytest` to test the functions automatically.

### Effect on coming weeks:
- Next week, I will continue to implement the FEM program, taking into account the feedback.
- I will investigate dockers for utilising firedrake.

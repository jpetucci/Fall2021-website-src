+++
title = "Exercises"
course_inst = "Penn State"
course_number = "Astro 528"
course_name = "High-Performance Scientific Computing for Astrophysics"
weight = 01110  #wwdpp

chapter= false
hidden = false

creatordisplayname = "Eric Ford"
creatoremail = "ebf11 at psu dot edu"
lastmodifierdisplayname = "Eric Ford"
lastmodifieremail = "ebf11 at psu dot edu"
+++


{{%excerpt%}}
**Tools, Floating Point Arithmetic, Functions, Tests**
(Due Aug 29)

- Exercise 1: Core development tools
    + [ICDS-ACI portal](http://portal.aci.ics.psu.edu/) 
    + [git](https://try.github.io/)
    + [GitHub.com](https://github.com)
    + [Julia](https://julialang.org/)
    + [Jupyter Notebooks](https://jupyter.org)
    + [Pluto Notebooks](https://github.com/fonsp/Pluto.jl)
- Exercise 2: Floating Point Arithmetic, Functions, Tests
- Exercise 3: Personal Goals (save at least 15 minutes for this one)
{{%/excerpt%}}
<!-- 
[Lab 1 Git Repository](https://github.com/PsuAstro528/lab1-start)  (Due Aug 29)
- [Exercise 1: Core development tools](https://nbviewer.jupyter.org/github/PsuAstro528/lab1-start/blob/master/ex1.ipynb) 
- [Exercise 2: Floating Point Arithmetic, Functions, Tests](https://nbviewer.jupyter.org/github/PsuAstro528/lab1-start/blob/master/ex2.ipynb) 
-->

If you're waiting on getting your account on ICDS-ACI, then I'd suggest that you start with exercise 3, since thinking about your goals does not require any accounts or special software.

If you're still waiting on getting your account on ICDS-ACI, then you could using a local installation of Julia.
If that gives you trouble, then you could use [mybinder.org](https://mybinder.org) to start tinkering on the assignments.  
<!-- 
(Links to: [Ex 1](https://mybinder.org/v2/gh/PsuAstro528/lab1-start/master?filepath=ex1.ipynb) and [Ex 2](https://mybinder.org/v2/gh/PsuAstro528/lab1-start/master?filepath=ex2.ipynb))
-->
However, you will not be able to save your work directly to a github repository when using mybinder.org.  Instead, you could use File.Download As.Notebook to download your notebook before exiting your session.  Then you could copy it into your github repository.  While this is workable for the first few labs, you'll need to get ACI working for later assignments where performance is actually important part of the assignment.


## Lessons / Resources
- [Getting Started with Julia on ACI](/lessons/week1/how-to-use-aci)
- [Julia Manual](http://docs.julialang.org/en/v1/)
- [Think Julia: How to Think Like a Computer Scientist](https://benlauwens.github.io/ThinkJulia.jl/latest/book.html)
- [Learn Julia in Y Minutes](https://learnxinyminutes.com/docs/julia/)
{{< children depth="1" >}}
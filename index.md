---
layout: lesson
---

{% include gh_variables.html %}

In [the Prenomics course](https://cloud-span.github.io/prenomics00-intro/) and in a [previous lesson](https://cloud-span.github.io/02genomics/01-writing-scripts/index.html), you learned how to use the bash shell to interact with your computer through a command line interface. In this 
lesson and the next, you will learn more about applying this new knowledge to begin a common genomics workflow - identifying variants among sequencing samples 
taken from multiple individuals within a population. In this lesson we will start with a set of sequenced reads (`.fastq` files) and perform
some quality control steps. You will also learn about organising a genomics workflow and why metadata is an important consideration.

As you progress through this lesson, keep in mind that, even if you aren’t going to be doing this same workflow in your research, you will be learning some very important lessons about using command-line bioinformatic tools. What you learn here will enable you to use a variety of bioinformatic tools with confidence and greatly enhance your research efficiency and productivity.

> ## Getting Started
>
> This lesson assumes no prior experience with the tools covered in the course. 
> However, learners are expected to have some familiarity with biological concepts,
> including the 
> concept of genomic variation within a population. Participants should bring their laptops and plan to participate actively. 
>
> This lesson is part of a course that uses data hosted on an Amazon Machine Instance (AMI). Course participants will be given 
> information on how
> to log-in to the AMI during the course. Information on preparing for the course is provided on the [Cloud-SPAN Genomics Course setup page](https://cloud-span.github.io/01genomics/setup.html).
{: .prereq}
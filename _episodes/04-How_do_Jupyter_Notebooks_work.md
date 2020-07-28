---
title: "How do Jupyter Notebooks work?"
teaching: 5
exercises: 10
questions:
- "How do Jupyter Notebooks work?"
objectives:
- "Understand how notebooks run and how they are different to the command line"
activity:
 - "Take a closer look at a notebook"
keypoints:
 - "You don't need anything special to run a notebook - just a browser will do!"
---

## How do Jupyter Notebooks work?

- Jupyter Notebooks use a “kernel”, which is kind of like an interpreter. This is what turns a programming language into instructions the computer understands so it can do the work. In regular computers a kernel connects the application software to the computer hardware. In the case of Jupyter Notebooks, this application permits displaying, editing and running program commands via a web browser.

- Different kernels can be installed for different types and versions of programming languages. The kernel in the notebook is a program that runs code written in a specific programming language.

- Notebooks use blocks of code to perform computational processes resulting in outputs, or results.

- In this workshop we will look at the two most used languages in data analysis, Python and R.

### What makes them different to other applications?

- Notebooks can run and store code and output with “Markdown” notes.

Let's break that down:

- Code
  - "Running code" means making the computer do what you are telling it to do. "Executing code" is the same thing.
- Output
  - In Jupyter Notebooks "output" is the result of the computational process, such as a visualisation, graph, model, equation and so on.
- Markdown
  - "Markdown" is the material you want to include that isn't code. It's just writing - "Markdown" is techie talk for what you do to turn plain text into formatted text so you can add headings, italics, quotes and other types of styling. It might be a description, a note, a question. These do not interact with the code, but are very useful in helping you understand the steps in your process and what you are trying to achieve.

- Jupyter notebooks are a series of “cells” containing executable code, or Markdown and outputs.

- Cells might contain code executed (through the kernel) or Markdown formatted text (including [LaTeX](https://www.latex-project.org/)) to embed the description of the work process next to the code.

>Jupyter Notebooks don't need much to get going. They are editable and viewable in a web browser. You can also run them on a local machine with no internet or a remote machine with internet. They are very flexible and free!
{: .callout}

### How are they different to the command line?

The [command line](https://en.wikipedia.org/wiki/Command-line_interface) does not include notes or show output. In Jupyter Notebooks you can go back and delete, insert or change code or text as you go, which you cannot do using the command line. Notebooks present Markdown and visualisations inline - meaning you can see the both at the same time and the parts that aren't code do not interfere with the code. It results in a highly flexible but user-friendly environment that can perform complicated tasks very quickly in an interactive way.

### What is the file type?

Jupyter Notebooks are saved as a JSON (JavaScript Object Notation) file with an **.ipynb** extension.

> ## Activity - Take a closer look at a notebook
>
> 1. In small groups, take a look at an example of a Jupyter Notebook. Open the [COVID-19 Analysis Dashboard](https://github.com/sarasrking/Introduction_to_Jupyter_notebooks/blob/master/notebooks/COVID-19%20Data%20Analysis%20with%20R.ipynb).
> 2. See if you can identify the cells, what is input and what is output, and what is Markdown. Discuss the types of output.
> 3. Examine the code. Different colours are used. Have you seen that before? Why do you think different colours are used?
> 4. If you have seen or used the command line before, can you think of any reasons why Notebooks might be easier to use? Discuss your ideas and experiences with the group. If you haven't used the command line before, have a think about why notebooks could be less daunting for beginners.
{: .challenge}

> ## Remember
>
> - Jupyter Notebooks can either run on a remote server via the internet or on your desktop with no internet
> - Jupyter Notebooks require a kernel (computational engine) to execute code e.g. Python or R
> - A notebook runs and stores the code and output, with Markdown notes
> - A notebook is an editable document with input and output cells
{: .callout}
{% include links.md %}

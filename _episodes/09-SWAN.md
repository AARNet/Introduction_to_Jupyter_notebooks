---
title: "Using data in CloudStor"
teaching: 5
exercises: 5
questions:
- "How do you work in Jupyter Notebooks with data stored in CloudStor?"
objectives:
- "Use data stored in Cloudstor in Jupyter Notebooks"
activity:
- "Bring a dataset into a notebook"
keypoints:
 - "This is where the fun begins!"
---

# Using data in CloudStor

CloudStor's SWAN (Service for Web-based Analysis) presents the [Jupyter Lab](https://towardsdatascience.com/jupyter-lab-evolution-of-the-jupyter-notebook-5297cacde6b) environment.

Once the SWAN session has started, a file navigator is shown on the left and a work area to the right. The work area allows you to open many notebook files and terminals in tabs and/or side by side to your liking.

When you open SWAN you are taken to the default location for your notebooks which is called a 'scratch' folder.

The file system in SWAN is a little different to your CloudStor folder. We recommend you use  the SWAN home folder (**/scratch**) as the default space to work in rather than your CloudStor  folder (**/scratch/cloudstor**). In SWAN you will see a sub-folder called “cloudstor” which connects to your CloudStor data.

Data in your SWAN home folder (**/scratch**) is routinely syncronised in your CloudStor account in a folder called “SWAN_SESSIONS”.

However, work outside of the home folder (**/scratch**) will not be backed up to CloudStor “SWAN_SESSIONS”. To mitigate the risk of losing this data we recommend that after completion, you save your work to the ‘cloudstor’ folder in SWAN.

> ## Activity - Find your scratch and CloudStor folders
>
> 1. Locate your **/scratch** folder (hint: look towards the top right hand side of the interface and hover over the folder icon).
> 2. Click on your CloudStor folder to check what you have in there.
{: .challenge}

## Reading in a dataset in Python using a public link

Jupyter Notebooks can work with an existing dataset. You need to refer to the dataset first, so that the notebook can then 'read' it.

Let's give it a go!

Make sure you are working in Jupyter Notebooks with the Python kernel running. We are going to use a software library called 'pandas', written for data manipulation and analysis in Python.

In a code cell type

~~~
import pandas
~~~
{: .language-python}

Execute the cell.

In a new code cell type

~~~
pandas.read_csv("")
~~~
{: .language-python}

and place this public link - https://cloudstor.aarnet.edu.au/plus/s/UAIvXO9S0LpYdG4 - between the quotes so it looks like this:

~~~
pandas.read_csv("https://cloudstor.aarnet.edu.au/plus/s/UAIvXO9S0LpYdG4")
~~~
{: .language-python}

Execute the cell.

You can change the file extension to match that of your dataset, eg .csv, .xml, .txt etc. The command is still the same. eg

~~~
pandas.read_xml("")
~~~
{: .language-python}

will read an xml file.

> ## Activity - Upload a dataset to CloudStor and your notebook
>
> 1. Upload your own dataset into Cloudstor. If you don't have one on your computer, you can search for a free dataset to download first:
>
> - [Health and medical data](https://www.aihw.gov.au/about-our-data/accessing-australian-government-data)
> - [General research data](https://researchdata.edu.au/)
>
> 2. Once you have uploaded your data, create a public link for it and, in a new notebook, repeat the instructions above with 'pandas', using the new link, and adjusting the file extension to match your dataset.
{: .challenge}

If you'd like to know more about 'pandas' try these pages:

- [Pandas (overview) - Pydata](https://pandas.pydata.org/pandas-docs/stable/getting_started/overview.html)

- [Pandas (software) - Wikipedia](https://en.m.wikipedia.org/wiki/Pandas_(software))

**Homework**: Watch ['What is pandas? (Introduction to the Q&A series)'](https://www.youtube.com/watch?v=yzIMircGU5I) on YouTube.

## Reading in datasets in R

If using R, you can import data like this:

In a code cell type

~~~
mydata <- read.csv("")
~~~
{: .language-r}

and place the link to the dataset saved in CloudStor between the quotes.

You can change the file extension to match that of your dataset, eg .csv, .xml, .txt etc. The command is still the same. eg

~~~
mydata <- read.xml("")
~~~
{: .language-r}

will read an xml file.
{% include links.md %}

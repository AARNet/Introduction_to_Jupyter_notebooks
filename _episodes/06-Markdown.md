---
title: "Getting started in Markdown"
teaching: 5
exercises: 5
questions:
- "What is Markdown and what is it for?"
objectives:
- "Open a notebook then use Markdown to create formatted text"
activity:
 - "Practicing with Markdown"
keypoints:
 - "Get started, be fearless!"
---

## Let's learn to use Markdown

Remember that [Markdown](https://en.wikipedia.org/wiki/Markdown) is how you can
make rich (or formatted) text in a plain text editor.

It is a lightweight markup language with plain text formatting syntax.
An example of a markup language is HTML.

In Jupyter Notebooks you use it to create the text you want to accompany your analyses.
 Remember that Markdown is for writing down comments outside of the code cells,
 so you can describe what you are doing as you go.

### Let's get hands on with Markdown

In Jupyter Notebooks the first thing you need to do is select the role of the cell
 you are typing into.

We are going to select 'Markdown' from the dropdown menu on the righthand side of
 the row of buttons showing the various icons (save, cut, copy etc).

### Headings

Let's start with a heading. To create a heading in Markdown you use a hash (#) and
 a space before the first word in the heading, type



`# Introduction to Jupyter Notebooks`



into the cell, making sure you have selected 'Markdown' from the dropdown menu
above where it shows 'Code' as the default.

![Select_Markdown]({{ site.baseurl }}/images/Select_Markdown.png)

Already here you can see how notebooks are flexible, as you can choose what kind
 of cell you are writing in (and toggle it at any time!)

Click on 'Run' - the button with the triangle next to a vertical line (it looks
   like a 'play' icon), or use the shortcut **Shift+Enter** to execute the cell.

You have just created a heading in your notebook! Hooray!

Now let's add a subheading. This time you use two hashes (##) before the words in your subheading.



  `## A lesson in Markdown`



Click on 'Run' - the button with the triangle next to a vertical line (it looks
  like a 'play' icon), or use the shortcut <kbd>Shift</kbd>+<kbd>Enter</kbd> to execute the cell.
   You now have a subheading.

### Body text

To write in your notebook in normal body text, you just have to type your text in
 the Markdown cell and press 'Run' or use the shortcut **Shift+Enter**. Try typing:

  `This is my first lesson in Markdown.`

Click on 'Run' or use the shortcut **Shift+Enter**.

You can now type your comments in your Jupyter Notebook.

### Editing a cell

Let's say we want to add some text to the cell you executed above.
Double-click on that line and you can open up the cell again.

After the first sentence, type



 `I'm doing really well!`



If you want to add a new cell you can click on the 'up arrow' icon from the buttons above.
 To delete or edit a cell, you can toggle up and down the cells.

### Adding a new cell

Let's add a new cell. Under your subheading, you can add another heading.
Go to your subheading 'A lesson in Markdown' and click on the 'plus' button.
This will create a new cell. Select 'Markdown' from the drop down menu. Type



`### Use it to create rich text in a plain text editor`



Press 'Run' or use the shortcut Shift+Enter.

You now have a level three heading.

### Bold

Now let's try bold font. In a new cell, select 'Markdown' from the dropdown menu again.
 Type



 `This is **really** interesting.`



Click on 'Run' or use the shortcut **Shift+Enter** to execute the cell.

Voila! Bold!

### Italics

Now let's try italics. In a new cell, select 'Markdown' from the dropdown menu again.
 Type



`This is really _interesting_.`


Click on 'Run' or use the shortcut **Shift+Enter** to execute the cell.

Voila! Italics!


> ## Activity - Practising with Markdown
>
> Spend a couple of minutes practicing these skills:
>
> - Headings
> - Plain text/bold/italics
> - Adding, removing and editing cells.
> - As a stretch goal try adding an image!
{: .challenge}


It can feel a little strange, as you already know how to do formatting in programs like Word.
 However, what we are doing here is 'speaking' directly to the computer, with a
 different kind of interface so you can also perform calculations, visualisations
 and use computational methods.

Remember that the reason Jupyter Notebooks is becoming so popular is because it
is a format that allows for commenting and text to sit within the same 'document'
 as code, mathematical equations and visualisations. You can tell the story of what
  you are doing as you go, and this is a really useful way of being about to reproduce
   your results.

If you want to know more about Markdown, take a look at these pages:

 - [Getting Started](https://www.markdownguide.org/getting-started/)
 - [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
 - [Markdown Cheatsheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)

{% include links.md %}

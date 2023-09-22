# University of Leeds Quarto thesis template

I generated this template to support other UoL students who may wish to write their PhD thesis in quarto. It meets the requirements for the UoL PhD thesis submission as of 2023.    

It was derived from the excellent quarto-thesis template created by Dr Eli Holmes.  Her original repo is here:   
https://github.com/nmfs-opensci/quarto-thesis

The pdf of the what these template files generate available in this repo as *"Put-your-Phd_title-here.pdf"*  

You need to follow her instructions below to get it to work on your laptop. 


## The below text is a copy of the text some of the held on her quarto-thesis repo on 21/03/2023.  You may wish to look at the repo to see if anything has changed.  

Quarto extension for a masters or PhD thesis based on Masters/Doctoral Thesis, LaTeX Template, Version 2.5 (27 Aug 2017). You can play with it on RStudio Cloud without installing anything: https://rstudio.cloud/content/4383755  Go to the Build tab (upper right panel) and click Render Book.

## Quick Start!

* Show me how to use this repo as a template and then clone to my computer with RStudio: [Video](https://youtu.be/smzNQtogSaI)


## Installing the extension

You will need to do this to get all the folders with tex files.

```bash
quarto use template nmfs-opensci/quarto-thesis
```

Once you do that you can render from within the folder.

```bash
quarto render
```

## Installation or updating for an existing document

You may also use this format with an existing Quarto project or document. But you will need to have all the tex folders already (see above).

```bash
quarto install extension nmfs-opensci/quarto-thesis
```

## Usage

Start adding Chapters to the Chapters folder.

## Getting and giving help

First try the Discussion link because there may be a solution there. Have a solution to post or want to show how you have used this template? Post to the discussion forum too! You'll find links to other Quarto thesis templates there too.

If you think it's a bug, then definitely post an issue and I'll look into it! 

## Contributors

[![Contributors](https://contrib.rocks/image?repo=nmfs-opensci/quarto-thesis)](https://github.com/nmfs-opensci/quarto-thesis/graphs/contributors)

This template is based on the [Masters/Doctoral Thesis, LaTeX Template, Version 2.5 (27 Aug 2017)](https://www.latextemplates.com/template/masters-doctoral-thesis). Other Quarto thesis examples:

## Warning. Chapter 1 has R code

Python and Julia users: After you install the extension, search for `{r}` in `Chapters/Chapter1.qmd` and get rid of the R code (for a table and a figure) or replace with Python or Julia code.

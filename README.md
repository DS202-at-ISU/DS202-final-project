
<!-- README.md is generated from README.Rmd. Please edit the README.Rmd file -->

# Final Project - Team XXX

This repository serves as a starter repo for your final project, and
this Rmd is supposed to serve as a starter file for your project report.

## Repo Structure

The structure sketched out below is an idea of what your repository
might look like. You can use it as a starting base and change according
to your needs. But think about the changes that you make!

    -- code
    |   |   -- any R scripts you need but don't want to include directly in the write-up
    -- data
    |   |   -- csv files (cleaned data)
    -- data-raw
    |   |   -- raw data files 
    |   |   -- data description files, origin
    |   |   -- Codebook
    -- final-project.Rmd
    -- images  # only images that are not created by the Rmd
    -- LICENSE
    -- README.md
    -- README.Rmd
    -- README_files # folder with files created during the knitting process

# Project report

## Title of your project

Authors: First Name Last Name, First Name Last Name, …

### Abstract (TL;DR)

An abstract is a quick summary of your work. Ideally it should motivate
someone to read the rest of the paper. Include one sentence each on

-   what is the project about?
-   what is the motivation for doing it?
-   what data is your work based on? and where does it come from? = what
    are your main findings? (one sentence each)

### Intro/Background/Motivation

What is the topic of your project, why is it relevant?

At the end of the Intro, write a sentence describing what each of the
(result) sections is about, e.g. in section 3 we show the relationship
between XXX and YYY, section 4 also considers the effect of variable
ZZZ. …

Somewhere at the beginning of your project, include a code chunk that
includes all of the R packages you are using throughout. In this
document, the setup code chunk is called `setup` (see line 8) Also make
sure to set defaults for the code chunks - like should they be visible?
(probably not: echo=FALSE). Do you want to automatically include
warnings? (probably yes, for creating the Rmd, to make sure that all
warnings are accounted for)

### Quick Data Summary

What are the variables that you will be using in the main part of the
report? What are their ranges? You could include a table with variable
names, a short explanation, and (very broad) summary statistics.

### Results

Each line of exploration is supposed to be featured in one of the
Results sections. Make sure to change to more interesting section
headers!

#### Results 1

In your write-up, make sure to refer to the figure. You can include a
hyperlink to @code-chunk-name using the name of the code chunk (make
sure, to give each code chunk a different name) by placing an `@` in
front of its name.

![This is the figure caption. Make sure to use the description we
practised in the homework: first sentence describes structure of the
plot, second sentence describes main finding, third sentence describes
outliers/follow-up.](README_files/figure-gfm/code-chunk-name-1.png)

#### Results 2

#### Results 3

…

### Data source

Where does the data come from, who owns the data? Where are all the
scripts that you need to clean the data?

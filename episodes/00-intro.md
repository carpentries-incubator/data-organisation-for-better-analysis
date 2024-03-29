---
title: Introduction
teaching: 15
exercises: 3
---

::::::::::::::::::::::::::::::::::::::: objectives

- Describe best practices for organizing data so computers can make the best use of data sets.

::::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::::::::::::::::::::::::::::::: questions

- What are basic principles for using spreadsheets for good data organization?

::::::::::::::::::::::::::::::::::::::::::::::::::

Good data organization is foundational to most projects. Anybody has data or does data entry in
spreadsheets. Spreadsheet programs are very useful graphical
interfaces for designing data tables and handling very basic data
quality control functions.

### Spreadsheet outline

After this lesson, you will be able to:

- Implement best practices in data table formatting
- Identify and address common formatting mistakes
- Understand approaches for handling dates in spreadsheets
- Utilize basic quality control features and data manipulation practices
- Effectively export data from spreadsheet programs

*Overall good data practices*

Spreadsheets are good for data entry. Therefore we have a lot of data
in spreadsheets.
It's usually in a 'shape' though that doesn't allow algorithms to assist us much, making the availability of a human to (try to) interpret it the bottleneck.
This 'shape' can be improved, if you understand the meaning and context of the data, by 'data wrangling'. The earlier in the process you do this, the less time it takes.
It's not the most fun, but it's necessary. We'll teach you how to think
about data organization and some practices for more effective data wrangling. Not only
will this save time and effort, it also paves the way for more equitable and inclusive
analysis. Making our work more accessible provides wider avenues for collaboration
and improvement!

### What this lesson will not teach you

- How to do *statistics* in a spreadsheet
- How to do *plotting* in a spreadsheet
- How to *write code* in spreadsheet programs
(If you're looking to do this, a good reference is
[Head First Excel](https://www.amazon.com/Head-First-Excel-learners-spreadsheets/dp/0596807694/), published by O'Reilly.)

- query your collection of Excel sheets; look into databases
- How to organize data in your organisation; look at http://datacentricmanifesto.org/ for that
- how to connect your data to other data elsewhere; look into Linked data and FAIR data

### Why aren't we teaching data analysis in spreadsheets

- Data analysis in spreadsheets usually requires a lot of manual
  work. If you want to change a parameter or run an analysis with a
  new dataset, you usually have to redo everything by hand. (We do
  know that you can create macros, but see the next point.)

- It is also difficult to track or reproduce statistical or plotting
  analyses done in spreadsheet programs when you want to go back to
  your work or someone asks for details of your analysis.

### Spreadsheet programs

Many spreadsheet programs are available. Since most participants utilize Excel as their primary spreadsheet program, this lesson will make use of Excel examples.

Free spreadsheet programs that can also be used are LibreOffice Calc, and even Google Sheets.

Commands may differ a bit between programs, but the general idea
is the same.

:::::::::::::::::::::::::::::::::::::::::  callout

## Exercise

- How many people have used spreadsheets in their work?
- How many people have accidentally done something that made them
  frustrated or sad (much) later?
  

::::::::::::::::::::::::::::::::::::::::::::::::::

Spreadsheets encompass a lot of the things we need
to be able to do as knowledge workers. We can use them for:

- Data entry
- Organizing data
- Subsetting and sorting data
- Statistics
- Plotting

We do a lot of different operations in spreadsheets. What kind of operations do you do in spreadsheets? Which ones do you think spreadsheets are good for?

## Problems with Spreadsheets

Spreadsheets are good for data entry, but in reality we tend to
use spreadsheet programs for much more than data entry. We use them
to create data tables for publications, to generate summary
statistics, and make figures.

Generating tables for publications in a spreadsheet is not
optimal - often, when formatting a data table for publication, we're
reporting key summary statistics in a way that is not really meant to
be read as data, and often involves special formatting
(merging cells, creating borders, making it pretty). Cutting and pasting from a spreadsheet
to a document software (like Word) can have unpredictable results.
We advise you to create tables within these document software
using the document's own table editing software.

The latter two applications, generating statistics and figures, should
be used with caution: because of the graphical, drag and drop nature of
spreadsheet programs, it can be very difficult, if not impossible, to
replicate your steps (much less retrace anyone else's), particularly if your
stats or figures require you to do more complex calculations. Furthermore,
in doing calculations in a spreadsheet, it's easy to accidentally apply a
slightly different formula to multiple adjacent cells. When using a
command-line based statistics program like R or SAS, it's practically
impossible to apply a calculation to one observation in your
dataset but not another unless you're doing it on purpose.
Luckily, many powerful combinations of both command-line and graphical interaction do exist, e.g. Rstudio, Jamovi, JASPstats and many more.

### Using Spreadsheets for Data Entry and Cleaning

However, there are circumstances where you might want to use a spreadsheet
program to produce "quick and dirty" calculations or figures, and data
cleaning will help you use some of these features. Data cleaning also
puts your data in a better format prior to importing into a
statistical analysis program. We will show you how to use some features of
spreadsheet programs to check your data quality along the way and produce
preliminary summary statistics.

In this lesson, we will assume that you are most likely using Excel as
your primary spreadsheet program - there are others (gnumeric, Calc
from OpenOffice), and their functionality is similar, but Excel seems
to be the program most used in many organizations.

In this lesson we're going to talk about:

1. [Formatting data tables in spreadsheets](01-format-data.md)
2. [Formatting problems](02-common-mistakes.md)
3. [Dates as data](03-dates-as-data.md)
4. [Quality control](04-quality-control.md)
5. [Exporting data](05-exporting-data.md)

:::::::::::::::::::::::::::::::::::::::: keypoints

- Good data organization is foundational to most projects and organizations.

::::::::::::::::::::::::::::::::::::::::::::::::::



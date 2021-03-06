Week One Instructions
================
Henry Renski

# Introduction

New code added here..

Welcome to the R practice class! Because of the limited amount of
in-class time, most of the work will be done outside of class and on
your own. We will use the class primarily for extra practice and group
trouble shooting.

Note: These instructions were created using the RMarkdown package.
RMarkdown is made for generating interactive reports where you can mix
text, code, charts, tables and other visual displays. Its very handy for
making interactive class materials.

# Goals for Week One

This week we will start with the basics:

1.  Make sure everything is working
2.  Explore the R Studio Interface (the four Windows)
3.  Installing and Loading R packages
4.  Entering and running some sample code in the editor
5.  Discuss object types and functions

# Key concepts from last time…

Last week I asked you to read the Intro Chapter of ModernDive. It
provides a nice overview of RStudio. Section 1.4 onward asked you to
play around with several libraries and datasets. Some of the most
important stuff includes:

> Install (if necessary) and load the packages: nycflights13, dplyr, and
> knitr

Here’s some sample code

``` r
install.packages("nycflights13")    ## for installing packages
library(nycflights13)               ## loading installed packages
```

> Do the same for the dplyr and knitr

> Check the packages window (on the lower right) to make sure they were
> installed.

Note: You only need to install a package once, unless you are working on
a new computer. But you do have to load the packages you want each time
you use them.

> Look at the Environment Window (upper right) to find the datasets that
> come with the nycflights13 package (R calls data frames)

> Examine the structure of the flights dataframe by typing its name in
> the console To show its contents in a seperate window type:

``` r
View(flights)
```

> Use glimpse (from the dplyr package) to see the different data types
> for the variables in the dataframe

> Access help files ?

## Readings and Assignments for next time

### YaRrr! The Pirates Guide to R:

Our instruction manual for next week will be to work through several
chapters from:

YaRrr! The Pirates Guide to R:

Available at:

&lt;<https://bookdown.org/ndphillips/YaRrr/the-four-rstudio-windows.html>

YaRrr! is an interactive tutorial. So as you read, have R open, type and
run everything in the highlighted areas into your own R studio editor.

Some of the intro materials may be redundant with Chapter 1 of
ModernDive (assigned for today), but redudancy is good practice.

#### Note: These chapters are very short - so don’t be intimidated

-   Chapter 2: Getting Started
    -   skip 2.1
-   Chapter 3: Jump In!
    -   Don’t worry if you don’t understand everything covered in
        Chapter 3. The purpose of the chapter is to have you try stuff
        that gets covered in more detail later
-   Chapter 4: The Basics
    -   Go ahead and asnswer the questions in section “Test your R might
        section” we will be reviewing the answers next time

### Swirl

Swirl is an package that provides an in-code itneractive tutorial to R.
It’s pretty basic, but very useful for extra hands on practice. To use
it you must first install the package, then load, then initiate. To
install the package type:

``` r
install.packages("swirl")  
```

into the console and enter.

Once the library is stalled on your machine, then you need to load it:

``` r
library(swirl)
```

Once loaded, then you need to start the swirl tutorial, by typing:

``` r
swirl()
```

Next week we will start with the first swirl tutorial “1: R
Programming…” lesson 1 “Basic Building Blocks” this covers some basic
calulcations and key concepts like objects, vectors, etc.

### Optional / Additional Materials

I found some decent (not great, but OK) Intro to R slides from Garrett
Grolemund at RStudio: Covers much of the basics in greater detail

<https://github.com/rstudio/Intro/blob/master/slides/02-The-R-Language-Part-1.pdf>

There are also many intro to R video tutorials on YouTube. Feel free to
explore. If you find any good ones, let me know. I’ll add them to our
repository.

## Good luck

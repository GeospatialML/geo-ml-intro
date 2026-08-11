---
title: "Introduction to geospatial data and analysis"
teaching: 10 # teaching time in minutes
exercises: 2 # exercise time in minutes
---

:::::::::::::::::::::::::::::::::::::: questions

- What are the different formats of geospatial data?
- How can geographic phenomena be represented in data formats?
- What is spatial-temporal data and how is it used?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- List different formats of geospatial data
- Describe geographic phenomena and their corresponding data formats
- Explain spatial-temporal data and its applications
- List data types and their properties for geospatial analysis

::::::::::::::::::::::::::::::::::::::::::::::::

## Introduction

Data is everywhere, and geospatial data is no exception. Geospatial data refers
to information that has a geographic component, meaning it can be mapped to a
specific location on the Earth's surface. Think of satellite imagery, aircrafts,
UAVs, GPS devices, mobile phones, and even social media platforms that collect
GPS coordinates. This type of data is crucial for understanding spatial
relationships and is invaluable for solving some of the greatest challenges,
including climate change adaptation, natural disaster monitoring, water resource
management, and food security for a growing global population.

![Observing the Earth: Greece continues to battle wildfires](fig/e01/Greece_continues_to_battle_wildfires_pillars.jpg){alt="Observing the Earth"}

Source: [The European Space Agency (ESA), Copernicus Sentinel-2 image](https://www.esa.int/Applications/Observing_the_Earth/FutureEO/Space_for_our_climate/Wildfires_drought_and_extreme_heat_2026)

But how do we represent geospatial data? This is what we will explore in this
lesson. We will discuss the different formats of geospatial data, how geographic
phenomena can be represented in these formats, and the concept of
spatial-temporal data.

To get started, we need to use a programming language that can read geospatial
data and visualize it. In this lesson, we will use Python, a popular programming
language that has a rich ecosystem of open-source libraries for data science and
geospatial analysis. In the sections that follow, we will introduce you to the
basics of geospatial data and analysis using Python. Make sure that you have
followed the setup instructions in the [lesson setup](../learners/setup.md) page
before proceeding.

::::::::::::::::::::::::::::::::::::: challenge

## Challenge 1: Can you do it?

What is the output of this command?

```r
paste("This", "new", "lesson", "looks", "good")
```

:::::::::::::::::::::::: solution

## Output

```output
[1] "This new lesson looks good"
```

:::::::::::::::::::::::::::::::::


## Challenge 2: how do you nest solutions within challenge blocks?

:::::::::::::::::::::::: solution

You can add a line with at least three colons and a `solution` tag.

:::::::::::::::::::::::::::::::::
::::::::::::::::::::::::::::::::::::::::::::::::

## Figures

You can use standard markdown for static figures with the following syntax:

`![optional caption that appears below the figure](figure url){alt='alt text for
accessibility purposes'}`

![You belong in The Carpentries!](https://raw.githubusercontent.com/carpentries/logo/master/Badge_Carpentries.svg){alt='Blue Carpentries hex person logo with no text.'}

::::::::::::::::::::::::::::::::::::: callout

Callout sections can highlight information.

They are sometimes used to emphasise particularly important points
but are also used in some lessons to present "asides":
content that is not central to the narrative of the lesson,
e.g. by providing the answer to a commonly-asked question.

::::::::::::::::::::::::::::::::::::::::::::::::


## Math

One of our episodes contains $\LaTeX$ equations when describing how to create
dynamic reports with {knitr}, so we now use mathjax to describe this:

`$\alpha = \dfrac{1}{(1 - \beta)^2}$` becomes: $\alpha = \dfrac{1}{(1 - \beta)^2}$

Cool, right?

::::::::::::::::::::::::::::::::::::: keypoints

- Use `.md` files for episodes when you want static content
- Use `.Rmd` files for episodes when you need to generate output
- Run `sandpaper::check_lesson()` to identify any issues with your lesson
- Run `sandpaper::build_lesson()` to preview your lesson locally

::::::::::::::::::::::::::::::::::::::::::::::::

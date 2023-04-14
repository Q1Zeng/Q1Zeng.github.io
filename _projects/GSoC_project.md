---
layout: page
title: Translate ERDDAP User Interface Into Different Languages
description: Google Summer of Code 2021 project with the U.S. Integrated Ocean Observing System (IOOS)
img: assets/img/GSoC-Vertical.png
importance: 1
category: "Open Source Projects"
---
<!-- 
Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    --- -->
# Translating ERDDAP Into Different Languages
## Overview
[ERDDAP](https://coastwatch.pfeg.noaa.gov/erddap/index.html) is a data server that allows scientists to share oceangraphic data, developed by [IOOS](https://ioos.noaa.gov/) and [National Oceanic and Atmospheric Administration (NOAA)](https://noaa.gov/) .
The objective of this project is to translate ERDDAP's user interface into other languages so it can provide oceangraphic data to people in non English-speaking countries.

The proposal can be found [here](https://docs.google.com/document/d/1IJc70YNpkkIYz4-eJzD9jHb4gagplC5FO6knZXk43N8/edit#).

This project was broken down into 4 milestones:

1.<del>Translate ERDDAP into one other language, but with some untranslated text.</del>

Finished.

2.Eliminate the hard-coded texts in ERDDAP.

Mostly finished. There were many hard-coded text across ERDDAP's files, I edited most of the large pieces of texts, but some smaller texts remain hard-coded.

3.<del>Complete the development of auto-translation tool.</del>

Finished.

4.Restructure ERDDAP so one ERDDAP can serve different users with different choice of language.

Half finished. This task is much more difficult and time-consuming than we previously expected. As 8/19/21, my ERDDAP system is able to display mutliple langauges for different local users, but it does not update the list of datasets properly. 

## What's next
- There are still some hard-coded text in ERDDAP's webpages to change.
- Bugs in the multilingual UI system need to be fixed.

## Code Links
[Repository Link](https://github.com/Q1Zeng/erddap)

- In the [1.4](https://github.com/Q1Zeng/erddap/tree/1.4) branch, it has a fully functioning translating system (translate.java) that will translate the messages.xml used in ERDDAP into any target langauges with the aid of Google Cloud Translator. This can be used by ERDDAP users to generate different languages of UI

- In the [1.2](https://github.com/Q1Zeng/erddap/tree/1.2) branch, the code enables one ERDDAP to serve multiple languages to different users, but there are some bugs to fix before putting it to work.

## Conclusion

This project was a wonderful experience to me. I learned a lot about Java Web App and how the IT professionals work. Although I did not complete all the milestones, I felt content on contributing to the scientific community and enhancing the data accessibility.

I would like to thank my mentor Bob for all the help he provided. Bob is a encouraging mentor, and patiently helped me a lot with my work. I learned a lot from him. I would also like to thank Google and IOOS for giving me this opportunity to work and learn on ERDDAP.

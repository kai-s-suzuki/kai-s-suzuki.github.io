# Kai Suzuki's Personal Website

Updated: June 2025.

## General information

This repository is for a Quarto website assignment in Spring 2025 for ENV S193DS, taught by An Bui at the University of California, Santa Barbara. The directions followed can be found [here](https://spring-2025.envs-193ds.com/assignments/choose-your-own_quarto-website).

## References

Inspiration was taken from the personal websites of former students of this course, [Ada Chibueze](https://adachibueze.github.io/) and [Evelyn Bermudez](https://evelynbermudez.github.io/).

[Directions](https://spring-2025.envs-193ds.com/assignments/choose-your-own_quarto-website) for this assignment were followed from An Bui. Guidance for website creation was followed from Sam Shanny-Csik's [slideshow](https://ucsb-meds.github.io/customizing-quarto-websites/#/title-slide).

Interactive running map was made with inspiration from [Sam's website](https://samanthacsik.github.io/about). Personal strava data, ArcGIS Pro, and ArcGIS Online were used to create the map.

### Packages

```
library(tidyverse) # general data tasks
library(here) # managing files
library(gt) # for table construction
library(janitor) # for data cleaning
library(readxl) # bringing excel files into R
library(dplyr) # for data cleaning
mydata <- read_csv("data/ENVS-193DS_caffeine_hw2.csv") # personal data for project tab
```

## Data and file information

Data found in the 'projects' tab is copied from myself and can be found [here](https://kai-s-suzuki.github.io/ENVS-193DS_homework-03/code/homework.html)

File structure:

```
.
├── website.Rproj
├── styles.scss                              # text size, color, font customization
├── _quarto.yml                              # website layout and formatting
├── README.md                                # readme text
├── index.qmd                                # rendered landing page and home tab text, photo code
├── aboutme.qmd                              # rendered about page text and photo code
├── project.qmd                              # rendered project page text, code, and pdf embedding
├── running.qmd                              # rendered running page text and interactive map code
├── resume.qmd                               # rendered resume page text and pdf embedding
│
├── docs                                     # code and text folder
│   ├── index.html                           # landing page and home tab text, photo code
│   ├── aboutme.html                         # about page text and photo code
│   ├── project.html                         # project page text, code, and pdf embedding
│   ├── running.html                         # running page text and interactive map code
│   └── resume.html                          # resume page text and pdf embedding
│
├── data                                     # data folder
│   └── ENVS-193DS_caffeine_hw2.csv          # personal data used in 'projects' tab
│
├── media
│   ├── elwood_mesa.jpg                      # jpg image of elwood mesa sunset
│   ├── kai_coffee.jpg                       # jpg image of me with coffee
│   ├── kai_escon.JPG                        # jpg image of me at Es Con Field
│   ├── kai_hike.jpg                         # jpg image of me on top of Gaviota Peak
│   ├── pasta.jpg                            # jpg image of a pasta dish
│   ├── profile.jpg                          # jpg image of me at the farm
│   └── tomatoes.JPG                         # jpg image of tomatoes
│
└── pdfs
    ├── ENVS-159_Written_Testimony.pdf       # pdf of paper used in 'projects' tab
    └── Suzuki_Kai_Resume.pdf                # pdf of resume used in 'resume' tab
```

All code is in the `docs` folder. The code analyzes data and creates data visualizations and data tables.

## Rendered output

The rendered output can be found [here](https://kai-s-suzuki.github.io/)  

Hanning Luo, Scraping Project

## Short Description
This project scrapes and analyzes the data from the Regular press conferences of China's Ministry of Foreign Affairs. It gets the questions and answers on the conference. It then conducts sentiment analysis to identify the variations in the discourses.

## Dependencies

This project utilized
1. R, 4.0.2

2. Packages: purrr, rvest, stringr, tidyverse, lubridate, tm, tidytext, textdata, ggpubr

## Files

#### /
1. Narrative.Rmd: Provides and overview of the project.
2. Narrative.pdf: A knitted pdf of Narrative.Rmd. 
3. Presentation.pdf
4. Scraping Data.Rmd: Code for scraping the websites.
5. Analysis.Rmd: Code for cleaning and analyzing the data.1. urls_English.RData: URLs to be scraped
6. all_texts_EN.csv: English language data frame of the conference questions and answers1. plot_date.jpg: ggplot scattered point that shows the average sentiments of every collected date
7. plot_individuals.jpg: box plot that shows the sentiments when responding to different political figures 
8. plot_region.jpg: box plot that shows the sentiments when referring to different countries
9. plot_speaker.jpg: box plot that shows the average sentiment of different spokespersons
10. plot_trigger.jpg: box plot that shows the average sentiment when commenting on different political issues
11. ttest speakers.csv: the result of a t test that compares the means of sentiments by speakers

#### Code/
1. Code for scraping the websites.
2. Code for cleaning and analyzing the data.

#### Data/
1. URLs to be scraped
2. English language data frame of the conference questions and answers

#### Results/
1. ggplot scattered point that shows the average sentiments of every collected date
2. box plot that shows the sentiments when responding to different political figures 
3. box plot that shows the sentiments when referring to different countries
4. box plot that shows the average sentiment of different spokespersons
5. box plot that shows the average sentiment when commenting on different political issues
6. the result of a t test that compares the means of sentiments by speakers



# News Analytics using R

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)

This repository contains R code for performing news analytics. The code uses various libraries for data analysis, visualization, and natural language processing to gain insights from a dataset of news articles.

## Getting Started

To get started, make sure you have the following R libraries installed:
1. readxl
2. ggplot2
3. RColorBrewer
4. scales
5. extrafont
6. tidyverse
7. tidygraph
8. wordcloud
9. wordcloud2
10. webshot
11. tm
12. igraph
13. ggraph
14. qgraph
15. networkD3
16. htmlwidgets
17. htmltools
18. IRdisplay
19. glue
20. cowplot
21. magrittr
22. plotly
23. widyr
24. hms
25. lubridate
26. tidytext

You can install these libraries using the `install.packages()` function in R.

## Data Loading

The code starts by loading a dataset from an Excel file, "Data Gabungan.xlsx," using the `read_excel` function from the `readxl` library.

## Line Chart: Number of News Articles per Day

The code then proceeds to create a line chart that displays the number of news articles per day. It converts the 'Tgl' column to a Date format, counts the occurrences for each date and 'Kanal Berita' (News Channel), and plots the data using `ggplot2`. It also sets a custom color scheme for each news channel.

## Heatmap: Frequency of News Reporting by Day of the Week

Next, the code generates a heatmap to display the frequency of news reporting by the day of the week. It extracts the day of the week from the date, rearranges the data for better visualization, and assigns custom colors to each day and news channel.

## Location Bar Chart

The code creates a stacked bar chart to visualize the frequency of news articles by location and news channel. It uses a custom color scheme for each news channel.

## Horizontal Bar Chart: Top 5 Writers

The code generates a horizontal bar chart to display the top 5 writers with the most articles. The color scheme is customized based on news channels.

## Horizontal Bar Chart: Top 5 Editors

Similar to the writers' chart, the code creates a horizontal bar chart to display the top 5 editors with the most edited articles. The color scheme is customized based on news channels.

## Top 5 Tags

The code analyzes and visualizes the top 5 tags in the news articles. It uses a stacked bar chart to display the frequency of tags by news channel.

## Word Cloud for Article Titles

The code creates a word cloud for article titles. It preprocesses the text data by removing stopwords, punctuation, and numbers, and then generates a word cloud for the most frequent words in the titles.

## Semantic Network for Article Titles

The code builds a semantic network for article titles. It preprocesses the text data, calculates the cosine similarity between titles, and visualizes the network of related titles.

## Modified Collin and Quillian Model

The code uses a modified Collin and Quillian model to analyze the co-occurrence of bigrams in the text data and visualize a network based on their weights.

## Network Diagram for Content

Finally, the code creates a network diagram based on bigrams in the content of the articles. It allows you to interactively explore relationships between words in the content.

## Usage

Each section of the code is self-contained and can be run independently for specific analyses. You can modify the threshold values and visual customization to suit your specific data and preferences.

Feel free to explore and adapt the code to your own datasets and research needs.

For any questions or issues, please refer to the code comments or contact the author.

# Diving Deep into Movie Recommendations: How Personality Traits Shape User Choices
This project analyzes how user personality traits relate to movie recommendations and preferences using RMarkdown. The dataset contains movie ratings and personality assessments from a survey of over 1800 users.

## Code
* movie-recommendations-and-personality-traits.Rmd: R Markdown document that loads data, performs analysis, and generates visualizations and report
* movie-recommendations-and-personality-traits.html: HTML output of analysis
* movie-recommendations-and-personality-traits.pdf: PDF output of analysis
## Analysis
The RMarkdown code conducts an exploratory analysis to examine:

* Which personality trait gives the highest average predicted movie ratings
* Which personality trait claims to enjoy watching movies the most
It generates boxplots to visualize the results.

## Results
The analysis found that certain personality traits like high extraversion, low emotional stability, low conscientiousness, and low openness generally give higher movie ratings and enjoyment.

## Data Source
The dataset is originally from the paper "User Personality and User Satisfaction with Recommender Systems" by Tien T. Nguyen et al. It was shared on Kaggle by Gabriel Atkin.

## Requirements
The analysis requires the R packages:

* tidyverse
* cowplot
## Reference
Author: Wilson Neira
Tien T. Nguyen, Pik-Mai Hui, F. Maxwell Harper, Loren Terveen, Joseph A. Konstan. 2014. Exploring the filter bubble: the effect of using recommender systems on content diversity. In Proceedings of the 23rd international conference on World wide web (WWW '14). ACM, New York, NY, USA, 677-686.

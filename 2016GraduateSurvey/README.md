# 2016 survey focussing on the graduates of the Faculty of a Japanese university
This is a dataset of an "opinion graph" for a survey focussing on the graduates of the Faculty of a Japanese university.


## Files and questions
The questions we asked are the following:
* What is your career? (Q1)
* What reason made you choose your current job? (Q2)
* What is the most valuable experience that you will take away with you from your time at the university? (Q3)

There are three graphml files for each question.

## graphml (data format)

+ Vertex attributes
  - id
  - PersonID
+ Edge attribute
  - Edge label ("+1", "-1")

PersonID indicates the respondent in the series of the questions.
The nodes whose PersonID is zero are the seed opinions that are initially set before the survey.

## Data collection details
The data were collected by an online survey system that one of the authors implemented.

- We announced the survey via postal mail to 3256 persons who graduated from the faculty between 2000 and 2016.
- The dataset contains no personal information of the respondents.

## Online survey system
http://voteclustering.org

This version of voteclustering is no longer updated. (A latter version is being actively updated elsewhere!)

## Citation
Please cite the following article when you use the datasets and contents herein. 

[1] Tatsuro Kawamoto and Takaaki Aoki, "Democratic summary of public opinions in free-response surveys," to appear (2019).

# Faculty survey (2016)
The datasets of opinion graphs of a survey focusing on the graduates of the Faculty of Education at a university in Japan.
The survey was conducted in 2016.

## Questions
Questions asked in the survey:
* What is your career? (Q1)
* What reason made you choose your current job? (Q2)
* What is the most valuable experience that you will take away with you from your time at the university? (Q3)

## graphml
Three `.graphml` files, corresponding to the three questions asked in the survey.

+ Vertex attributes
  - id
  - PersonID
+ Edge attribute
  - Edge label ("+1", "-1")

PersonID is an identifier of each respondent in the series of questions.
The nodes with PersonIDs equal to zero are the seed opinions that were initially set before the survey.

## Data collection details
The data were collected by an online survey system.

- We announced the survey via postal mail to 3256 persons who graduated from the faculty between 2000 and 2016.
- The datasets contain no personal information of the respondents.

## Citation
Please cite the following article when you use the datasets and contents herein. 

[1] Tatsuro Kawamoto and Takaaki Aoki, "Democratic summary of public opinions in free-response surveys," to appear (2019).

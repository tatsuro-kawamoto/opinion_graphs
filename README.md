# 2016 US presidential election dataset
This is a dataset of an "opinion graph" for a poll on the 2016 US presidential election.

## graphml & gml

+ Vertex attributes
  - id
  - Opinion text
  - Inferred group label
+ Edge attribute
  - Edge label ("+1", "-1", "0")

This is a dataset after the edges are "neutralized." 
"0" edges represent neutral edges, which were "-1" edges originally.

## Data collection details
The data were collected by an online survey system that one of the authors implemented.
- A significant fraction of data were collected from the people who visited University of Nevada, Las Vegas on Oct. 18th and 19th, which are the day before and the day of the final presidential debate.
- The dataset contains no personal information of the respondents.
- 12 opinions are the seed opinions that are initially set before the poll.
- The poll was conducted personally by one of the authors. No financial or political support was involved.

## Online survey system
http://voteclustering.org

This version of voteclustering is no longer updated. (A latter version is being actively updated elsewhere!)

## Citation
Tatsuro Kawamoto and Takaaki Aoki, "Graph-based classification of opinions in large-scale surveys" (2018).

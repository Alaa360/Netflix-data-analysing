# Netflix data analyzing

Netflix data has some of movies and tv-shows, that have rating, duration, country produced and category. 

Using Jupyter Notebook to dig deep in Netflix Dataset. Analyzed and interpreted data from 1000+ movies and TV series to identify audience preferences and optimize content recommendations.


## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) or use the [Conda](https://conda.io/en/latest/) package manager


```bash
pip install pandas
pip install matplotlib
pip install seaborn
```
```bash
conda install pandas
conda install matplotlib
conda install seaborn
```

## Usage

```python
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
```

## What does the Data show?

### Data Cleaning
+ Checking if there is any duplicate, and remove it.
+ Checking if there is any null value.

### Analyzing
+ The (Show_id) and (Director) for 'House of Cards'.
+ The highest number of movies and TV shows released in a Year.
+ Number of TV shows and Movies are in the Dataset.
+ All Movies that released in 2020.
+ Show all the Titles of all TV shows that are released in India
+ Top 10 Directors that have the highest number of movies and tv shows.
+ Show all the Records that their (Category) is Movie and the (Type) is Comedies or (Country) is UK.
+ Movies and TV shows that Tom Cruise was in the cast.
+ The Different Ratings defined by Netflix.
+ Movies that got the 'TV-14' rating, In Canada.
+ TV Show got the 'R' rating after 2018.
+ The maximum duration of a Movie/Show on Netflix.
+ The Country that has the Highest No. of TV Shows.
+ Sorting the Dataset by Year.
+ All the instances where:
Category is Movie and Type is Dramas
OR
Category is 'TV Show' and Type is 'Kids' TV'
 

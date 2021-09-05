
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing and Acknowledgements](#licensing)

## Installation <a name="installation"></a>
To run this project you need **Python 3+** installed along with **Jupyter Notebook** to work on the same.
Other python packages used for the analysis are:
* [numpy](https://numpy.org/)
* [pandas](https://pandas.pydata.org/)
* [scikit-learn](https://scikit-learn.org/)
* [matplotlib](https://matplotlib.org/)
* [seaborn](https://seaborn.pydata.org/)

## Project Motivation<a name="motivation"></a>
The sinking of the Titanic is one of the most infamous shipwrecks in history.
On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.
While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.


With this analysis, I wanted to confirm some thoughts I had after I watched the movie [Titanic](https://en.wikipedia.org/wiki/Titanic_(1997_film)).
1. In the movie it was shown that women and children were first sent on life boats when the Titanic sunk. I want to confirm whether the data gave the same outcome and that there was a better chance of survival if you were a female or a child.
2. Similar to the above one, whether there was a better chance of survival if you were from the first class?
3. What factors contributed most to the survival of passengers on the Titanic?
4. Given a new passenger on the Titanic, with what certainty can my model predict whether the passenger can survive or not?

## File Descriptions <a name="files"></a>
* **train.csv** - training dataset for this project
* **test.csv** - test dataset for this project
* **ground_truth.csv** - actual result for test dataset
* **titanic-dataset-exploration.ipynb** - Jupyter notebook that consists my analysis for the questions above. I have made sure that the notebook is readable and gives you an insight into my thought process during each step. 

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://www.priyankapalshetkar.com/post/would-you-have-survived-the-titanic-mishap).

## Licensing and Acknowledgements<a name="licensing"></a>
The information for this project can be found here - [Titanic - Machine Learning for Disaster](https://www.kaggle.com/c/titanic)

Licensing for the data and more information about the dataset in general can be found on the same link. I have also added the dataset to this repo just in case.

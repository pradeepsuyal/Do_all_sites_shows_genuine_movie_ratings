## Table of CONTENTS 
---------------------

 * [Introduction](#intro)
 * [Aim](#aim)
 * [Dataset used](#data)
 * [Exploring the Data](#viz)
   - [Matplotlib](#matplotlib)
   - [Seaborn](#seaborn)
 * [Conclusion](#conclusion)
 
 
 ## INTRODUCTION:<a name="intro"></a>
 
 on a weekend you and your friend plan to go out for a movie and but you were confused that which movie to watch so you check ratings from various site such as IMDB, rottentomatos, Fandango, yelp, etc. But how well can you trust online reviews and ratings? Especially if the same company showing the rating also makes money by selling movie tickets.  Do they have a bias towards rating movies higher than they should be rated?

one such thing was happend back in 2015 with a movie booking site named fandango you can read the full article [here](https://fivethirtyeight.com/features/fandango-movies-ratings/)

## AIM:<a name="aim"></a>

Does fivethirtyeight article and our goal to show that there was fraud or not, reaches to a similar conclusion?

## Dataset Used:<a name="data"></a>

This is the data behind the story Be Suspicious Of Online Movie Ratings, Especially Fandango’s openly available on 538's [github](https://github.com/fivethirtyeight/data). There are two csv files, one with Fandango Stars and Displayed Ratings, and the other with aggregate data for movie ratings from other sites, like Metacritic,IMDB, and Rotten Tomatoes.

## Exploring the Data:<a name="viz"></a>

Here I will use pandas and seaborn visualization skills to determine if Fandango's ratings in 2015 had a bias towards rating movies better to sell more tickets.

**Matplotlib:**<a name="matplotlib"></a>
--------
Matplotlib is a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms. Matplotlib can be used in Python scripts, the Python and IPython shells, the Jupyter notebook, web application servers, and four graphical user interface toolkits.You can draw up all sorts of charts(such as Bar Graph, Pie Chart, Box Plot, Histogram. Subplots ,Scatter Plot and many more) and visualization using matplotlib.

Environment Setup==
If you have Python and Anaconda installed on your computer, you can use any of the methods below to install matplotlib:

*pip: "pip install matplotlib"*

*anaconda: " conda install matplotlib"*

for more information you can refer to [matplotlib](https://matplotlib.org/) official site

**Seaborn:**<a name="seaborn"></a>
------
Seaborn is built on top of Python’s core visualization library Matplotlib. Seaborn comes with some very important features that make it easy to use. Some of these features are:

**Visualizing univariate and bivariate data.**

**Fitting and visualizing linear regression models.**

**Plotting statistical time series data.**

**Seaborn works well with NumPy and Pandas data structures**

**Built-in themes for styling Matplotlib graphics**

**The knowledge of Matplotlib is recommended to tweak Seaborn’s default plots.**

Environment Setup==
If you have Python and Anaconda installed on your computer, you can use any of the methods below to install seaborn:

*pip: "pip install seaborn"*

*anaconda: " conda install seaborn"*

for more information you can refer to [seaborn](https://seaborn.pydata.org/) official site.

## CONCLUSION:<a name="conclusion"></a>

![final_plot](https://user-images.githubusercontent.com/86251750/135658446-df7989d4-5e70-4084-bff6-00044ba1ef5b.png)

From above plot we can see that Fandango has an uneven distribution. We can also see that RT critics have the most uniform distribution so we can say that Clearly Fandango is rating movies much higher than other sites, especially considering that it is then displaying a rounded up version of the rating.

**Final thoughts: Fandango is showing around 3-4 star ratings for films that are clearly bad! from the notebook you can Notice the biggest offender, Taken 3!. Fandango is displaying 4.5 stars on their site for a film with an average rating of 1.86 across the other platforms!**

***language used***
--------------------------
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

**Tools**
-----------------------
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)    ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)   ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)  ![Made with matplotlib](https://user-images.githubusercontent.com/86251750/132984208-76ce70c7-816d-4f72-9c9f-90073a70310f.png)  ![seaborn](https://user-images.githubusercontent.com/86251750/132984253-32c04192-989f-4ebd-8c46-8ad1a194a492.png)


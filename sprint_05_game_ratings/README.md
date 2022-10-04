<div align="center">

<div>  
  &nbsp; 
</div>

# Sprint 05 Video game success patterns

[![Telegram support](https://img.shields.io/badge/Support-Telegram-blue)](https://t.me/anton_siluyanov)
[![Facebook](https://img.shields.io/badge/Facebook-1877F2?logo=facebook&logoColor=white)](https://www.facebook.com/AntonSiluDS/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/siluyanov/)

<div>  
  &nbsp; 
</div>
	
  :star: **Star me on GitHub — it motivates me a lot!** :star:
	
<div>  
  &nbsp; 
</div>
</div>

<blockquote>
  &nbsp;
	
  *“Anton, as always, the project is gorgeous. The hand of a future professional is felt. 😄 Keep it up! 😄”*  

 Reviewer's comment when submitting the project.

  &nbsp;

</blockquote>

## :book: &nbsp; Table of Contents

* [Project Composition](#clipboard--project-composition)
* [File Structure](#file_cabinet--file-structure)
* [Dependencies](#notebook_with_decorative_cover--dependencies)
* [JSight API Language](#trophy--acknowledgments)

## Project Description

Online store "Streamchik", sells computer games all over the world. 
Historical data on game sales, user and expert ratings, genres and platforms (for example, Xbox or PlayStation) are available from open sources. 
It is necessary to identify patterns that determine the success of the game. This will allow you to bet on a potentially popular product and plan advertising campaigns.

## :clipboard: &nbsp; Project Composition

1. Project Description
1. **Step 0**. Getting ready for work
    1. Importing libraries
    1. Setting project parameters
    1. Project Functions
    1. Loading Data
1. **Step 1**. A general look at the data
   1. Study of general information
      1. Getting to know the games data
      1. Expectations by data types games
1. **Step 2**. Data Preparation
   1. Renaming columns
   2. Explicit duplicates
   1. Implicit duplicates
   1. Omissions
   1. Type conversion
1. **Step 3**. Preparing the data structure
   1. Preparation of `games`
   1. Emissions
      1. DS emissions.
      1. DC emissions
1. **Step 4**. Exploratory Data Analysis
   1. Games in different years.
   1. Sales by Platform
      1. Platforms with the highest total sales
      1. Distribution by year
      1. How long before new platforms appear
      1. For how long do the old platforms disappear
      1. Data for the current period
      1. Potentially profitable platforms
         1. Sales Leaders 2013 - 2016
         1. Sales Growth and Decline Leaders 2013 - 2016
      1. Global Sales by Platform
      1. Dependence of sales on ratings for PS4
      1. Dependence of sales on ratings comparison of platforms
      1. Game genres
         1. Distribution of games by genre
         1. The most profitable genres
1. **Step 5**. User Portraits
   1. Popular Platforms
   1. Popular genres
   1. The impact of the ESRB rating on sales
1. **Step 6**. Hypothesis testing
      1. Xbox One and PC
      1. Ratings 9.2 Genre Ratings
1. **Step 7**. General conclusions
1. Appendix 1: The original assignment of the project work
1. Appendix 2: Data description

## :file_cabinet: &nbsp; File structure
```
└── datasets/                 ## Project data sets 
    ├── games.csv             ## Video games data table
    ├── games.xlsx            ## Excel data table for quick analysis
└── sprint_task/              ## Original project assignments
    ├── games.csv             ## Data table
    ├── sprint_05_task.pdf    ## Project assignment text
└── 05-02 Games.ipynb         ## The result of project work in Jupiter Notebook
```
## :notebook_with_decorative_cover: &nbsp; Dependencies

- [pandas](https://github.com/pandas-dev/?ysclid=l8u11r14a6299027)
- [numpy](https://github.com/numpy/numpy)
- [matplotlib.pyplot](https://github.com/matplotlib/matplotlib?ysclid=l8u12brkax692179597)
- [seaborn](https://seaborn.pydata.org/)
- [pathlib](https://docs.python.org/3/library/pathlib.html)
- [scipy](https://github.com/scipy/scipy?ysclid=l8u13try9u12674764)
- [IPython.display](https://ipython.org/ipython-doc/3/api/generated/IPython.display.html)

## :trophy: &nbsp; Acknowledgments

I sincerely thank those without whom this project would not have been possible

- [Anaconda](https://www.anaconda.com/)
- [Jupiter Interactive Notebook](https://github.com/jupyter/notebook)
- [Cloudshot](https://www.cloudshot.com/)
- [Geeks for Geeks](https://www.geeksforgeeks.org/)

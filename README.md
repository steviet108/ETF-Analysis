# ETF-Analysis



![fintech-image](etf-image.png)



This is an analysis of 4 securities, PayPal, Square, Green Dot and Goldman Sachs. What is fun about this analysis is I have written some SQL queries and that was new for me. I created a temporary database with sqlite and read in some data to popl]ulate the database, then I created the engine that would interact with the database. Than I wrote a few queries to pull specific data from the database and read it into a pandas dataframe. Once I had the pandas dataframes I went on to do some standard analysis of the data to see what we could interpret. 


## Technologies

This Analysis uses Python 3.7 with the following packages and libraries :

- Pandas
- Numpy
- Hvplot
- SQLalchemy


## Installation Guide

This analysis was done with Pandas in Jupyter Lab. If the User wants to interact with the functions, first install the following:
  To get started using this application please go to [Python Download](https://www.python.org/downloads/) and select the version for your operating system. Then install the following libraries and packages.


``` sudo apt install python3-pip ```. This will install the pip that will make it easier to install the libraries.

``` pip install pandas ```

``` pip install numpy ```

``` pip install jupyter lab ```

``` pip install SQLAlchemy ```


## Usage

The file of interest is labaled ``` etf_analyzer.ipynb ```

This analysis is meant to be read and its a basic analysis of 4 securities. It is possible to replicate these functions for different data, but that would require borrowing the functions, or cloning the repository to your local computer and then using my examples of sql queries and function in the way the user wants.


## Contributors

Stephen Thomas

[Trilogy Education Services](https://www.trilogyed.com/)

[UC Berkeley Extension ](https://extension.berkeley.edu/)


## License

MIT

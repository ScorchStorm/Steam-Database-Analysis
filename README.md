## Overview
This project is an analysis of the correlation of players vs time graphs for some of the most popular games on Steam on 2/8/2025

**Project Title**:
Steam Database Analysis

**Project Description**:
Thsi project took inputs from many player vs time graphs on the steam database and found correlations between those graphs for 15 different games from the top charts on 2/8/2025. The graphs take data from a week of how many players were logged onto the game at 192 different points in time.

**Project Goals**:
1. Obtain data from the steam database for the most popular games
2. Clean and parse the data so that only the player vs time data is saved
3. Make graphs of the data
4. Find the correlations of players vs time for the different games
5. Make graphs of those correlations
6. Make graphs of players vs time for the most correlated games
7. Find Aggregations of games that are similar to each other

## Instructions for Build and Use

Steps to build and/or run the software:

1. Download and install Python
2. Download and install Anaconda
3. Download and install Jupyter Notebook from Anaconda
4. Download the .ipynb file from this GitHub repository
5. Open the file in Jupyter Notebook

Instructions for using the software:

1. Open the file in Jupyter Notebook
2. Run the software cell by cell to see the individual outputs.
3. Additional data can be obtained form the steam database at https://steamdb.info/charts/?sort=24h

## Development Environment 

To recreate the development environment, you need the following software and/or libraries with the specified versions:

* Python version 3.11.2 - 64 bit
* Anaconda3 2021.11 (Python 3.9.7 64-bit)

## Useful Websites to Learn More

I found these websites useful in developing this software:
* GitHub https://nik-davis.github.io/posts/2019/steam-data-exploration/
* GitHub https://nik-davis.github.io/posts/2019/steam-data-collection/

## Future Work

The following items I plan to fix, improve, and/or add to this project in the future:

* [ ] Get the data for many more games maybe 100-200 or so
* [ ] Speed up the data downloading process to avoid errors caused by the passage of time from downloading the data from one game to downloading the data for the next game

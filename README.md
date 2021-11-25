>**Note**: Please **fork** the current Udacity repository so that you will have a **remote** repository in **your** Github account. Clone the remote repository to your local machine. Later, as a part of the project "Post your Work on Github", you will push your proposed changes to the remote repository in your Github account.

### Date created
November 23,2021

### Project Title
US Bikeshare Data Analysis Project

### Description
In the bikeshare project, Python was used to explore data related to bike share systems for three major cities in the United States — Chicago, New York City, and Washington. A code was written to import the data and answer interesting questions about it by computing descriptive statistics, and write a script that takes in raw input to create an interactive experience in the terminal to present these statistics.
The developed CLI program allows to explore an US bikeshare system database and retrieve statistics information from the database. It is able to filter the information by city, month and weekday, in order to visualize statistics information related to a specific subset of data. We are able to view raw data and sort this data by columns, in ascending or descending order.

### DETAIL EXPLANATION OF THE CODE:

# How the program for the project worked:
The code developed takes in raw input to create an interactive experience in the terminal that answers questions about the dataset. The experience is interactive because depending on a user's input, the answers to the questions will change! There are four questions that will change the answers:
• Would you like to see data for Chicago, New York, or Washington? • Would you like to filter the data by month, day, or not at all? • (If they chose month) Which month - January, February, March, April, May, or June? • (If they chose day) Which day - Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, or Sunday?

The answers to the questions above will determine the city and timeframe on which you'll do data analysis. After filtering the dataset, users will see the statistical result of the data, and choose to start again or exit.

# The Datasets for the Bikeshare Project:
Randomly selected data for the first six months of 2017 are provided for all three cities. All three of the data files contain the same core six (6) columns: • Start Time (e.g., 2017-01-01 00:07:57) • End Time (e.g., 2017-01-01 00:20:53) • Trip Duration (in seconds - e.g., 776) • Start Station (e.g., Broadway & Barry Ave) • End Station (e.g., Sedgwick St & North Ave) • User Type (Subscriber or Customer) The Chicago and New York City files also have the following two columns: • Gender • Birth Year

# Statistics Computed:
The code helps user to tell about bike share use in Chicago, New York City and Washington by computing a variety of descriptive statistics. In this project, the code output will provide the following information:
• Popular times of travel (i.e., occurs most often in the start time): o most common month o most common day of week o most common hour of day
• Popular stations and trip: o most common start station o most common end station o most common trip from start to end (i.e., most frequent combination of start station and end station)
• Trip duration: o total travel time o average travel time
• User info: o counts of each user type o counts of each gender (only available for NYC and Chicago) o earliest, most recent, most common year of birth (only available for NYC and Chicago)


### Files used
Installing GIT tool : https://git-scm.com/downloads.
The following file contains necessary commands used to do tasks:
Git Commands Documentation.pdf
The following files helps to understand the Git key terms:
Git-KeyTerms.pdf

Files used for Project 2 are:
washington.csv
new_york_city.csv
chicago.csv

Requirements for Project 2
This program was written in Python (version 3.8.8) and relies on the following libraries(Pandas:1.2.4,NumPy:1.20.1)

### Credits

• Richard Kalehoff https://github.com/richardkalehoff https://twitter.com/richardkalehoff 

• Juno Lee (Udacity Team Mentor) https://github.com/junolee



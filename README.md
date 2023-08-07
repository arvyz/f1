# f1
Formula 1 Data analysis

The Data for this project is downloaded from Kaggle dataset on F1.  Details below.

The F1 data is structured across 14 files from [Kaggle](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020)

+ Circuits - Descriptive Information about F1 Circuits from 1950 - 2023
+ Seasons - Just a simple file of each season year
+ Races - Information on each race and date it was held and circuit it was held on.
+ Constructors - Descriptive Information about each F1 Team
+ Constructor Results - Race results for each Constructor (Manufacturer).
+ Constructor Standings - The positional standing of the constructor after each race; cyclical - repeats every year.
+ Drivers - A descriptive file about the Drivers, including name, dob, nationality
+ Results - Results of each driver for every race, including fastest times, speed, laps and race result.
+ Drivers Standings - The positional standing of drivers after each race, including number of wins; cyclical - resets and repeats every year
+ Qualifying - Results of qualitfying for each driver, for each race or each of Q1, Q2 and Q3 sessions.
+ Lap Times - Time and position for each lap of every race
+ Pit Stops - Pit Stops for most races; Stop number and stop times (not for all races)
+ Sprint Results - A short format race on the day of qualifying; generally orthogonal to the rest of the data (*we won't use it for our analysis*)
+ Status - Description of Race status codes for driviers (Finished, DNF, Mech Failure etc.)

In addition to the above, we created a new file from a different data source on Wikipedia - [List of Formula 1 Circuits](https://en.wikipedia.org/wiki/List_of_Formula_One_circuits) to get more details on the circuit type information.  This will be used to predict if a circuit is **Street Circuit** or a **Track Circuit** based on various characteristics that we can observe.  This data is represented in the following file:
+ Circuits Info - Additional Descriptive Information about Formula 1 Circuits including whether a circuit is a street or a track circuit

This project is a machine learning analysis of the F1 dataset.
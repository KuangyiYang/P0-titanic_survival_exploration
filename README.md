# Project 0-titanic_survival_exploration
This repository contains project files for Udacity: Machine Learning Nanodegree, Project 0

**Project Description**

In 1912, the ship RMS Titanic struck an iceberg on its maiden voyage and sank, resulting in the deaths of most of its passengers and crew. In this introductory project, we will explore a subset of the RMS Titanic passenger manifest to determine which features best predict whether someone survived or did not survive. To complete this project, you will need to implement several conditional predictions and answer the questions below. Your project submission will be evaluated based on the completion of the code and your responses to the questions.


### Run Instruction
Open the template iPython notebook titanic_survival_exploration.ipynb and follow along.

To begin working with the RMS Titanic passenger data, we'll first need to import the functionality we need, and load our data into a pandas DataFrame.
Run the code cell below to load our data and display the first few entries (passengers) for examination using the .head() function.

> Tip: You can run a code cell by clicking on the cell and using the keyboard shortcut Shift + Enter or Shift + Return. Alternatively, a code cell can be executed using the Play button in the hotbar after selecting it. Markdown cells (text cells like this one) can be edited by double-clicking, and saved using these same shortcuts. Markdown allows you to write easy-to-read plain text that can be converted to HTML.


Load the dataset:
```
  in_file = 'titanic_data.csv'
  full_data = pd.read_csv(in_file)
```

## Software and Libraries
- Python 2.7
- NumPy
- pandas
- iPython Notebook

## Dataset
Attributes for student-data.csv:
- From a sample of the RMS Titanic data, we can see the various features present for each passenger on the ship:
- Survived: Outcome of survival (0 = No; 1 = Yes)
- Pclass: Socio-economic class (1 = Upper class; 2 = Middle class; 3 = Lower class)
- Name: Name of passenger
- Sex: Sex of the passenger
- Age: Age of the passenger (Some entries contain NaN)
- SibSp: Number of siblings and spouses of the passenger aboard
- Parch: Number of parents and children of the passenger aboard
- Ticket: Ticket number of the passenger
- Fare: Fare paid by the passenger
- Cabin Cabin number of the passenger (Some entries contain NaN)
- Embarked: Port of embarkation of the passenger (C = Cherbourg; Q = Queenstown; S = Southampton)

## Questions:
- Question1: Using the RMS Titanic data, how accurate would a prediction be that none of the passengers survived? 
- Question2: How accurate would a prediction be that all female passengers survived and the remaining passengers did not survive?
- Question3: How accurate would a prediction be that all female passengers and all male passengers younger than 10 survived?
- Question4: Describe the steps you took to implement the final prediction model so that it got an accuracy of at least 80%. What features did you look at? Were certain features more informative than others? Which conditions did you use to split the survival outcomes in the data? How accurate are your predictions?
- Question5: Can you think of an example of where supervised learning can be applied?

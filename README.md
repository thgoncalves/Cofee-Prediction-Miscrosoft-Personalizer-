# Cofee Prediction Miscrosoft Personalizer


This is a Proof of Concept in how to use Microsoft Personalizer

On this project, I use Azure to make predictions on Coffee preferences of a fictional person based on:
* Coffee features
* Person Preferences
* Weather Condintions
* Time of the day


On the notebook, I'll go througth the following steps:
1. Import Libraries
2. Define Azure Key and Personalizer base URL
3. Define function to update model and check settings
4. Import json files with persons, coffee types, weather conditions
5. Create an unique EventID
6. Create randomizer to generate an unique Person/Coffee/Weather/Time variable
7. Define function to get Rank and Reward
8. Main function that will run all entries on Azure and evaluate them
9. Plot it on a chart to check results
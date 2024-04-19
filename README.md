# Predicting-NFL-contracts

Final project for 3162 - Introduction to Data Mining.

Group members: Andrew Green, Emerson Jones, Eric Sheehan, Luke Hopson, Tacoma Jones

Each year football teams make massive investments in each player they sign in hopes that it will be beneficial to the team. The goal of this project is to use data to determine what free agents should be paid based on their previous years production and how likely they are to perform in the coming years based on their age.

We plan on using player statistics for certain NFL skill positions along with player salaries that were received following that season. For this project, we will be merging contract data from overthecap.com  with player statistics with pro-football-reference.com through Excel Power Queries. Once the data is properly merged together, we will upload it to a shared Google Drive folder and perform our pre-processing and data analysis in a shared Google Colab python notebook file.

In order to answer our research question on what upcoming free agents should be paid, we will be building a linear regression model using data from their last season before their current contract expires. Not only will we be using the model to predict the contract value, but we will also be looking at specific variables and what variables are important in influencing the value of each player’s next contract.

To evaluate our data analysis, we will be using typical evaluation techniques like using R-squared, adjusted R-squared, and even looking into standard errors and p-values of specific variables to see if there’s room for improvement as we create different linear regression models.

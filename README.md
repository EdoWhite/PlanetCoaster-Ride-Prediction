<p align="center">
  <img width="70%" height="70%"src="/assets/coaster.jpg">
</p>

# Planet Coaster Ride Rating Prediction
Planet Coaster is a famous computer and console video game developed by Frontier. In this game the user creates and manages theme parks, from staff hiring to marketing campaigns. Basically the main goal is make guests happy, and in order to do so building attractive roller coasters is one of the most important tasks. When the user builds a new ride, this ride is tested by the artificial intelligence of the game, that simulates real riders, and then a final rating is shown.

The rating system consists of three metrics: Excitement, Fear and Nausea, all this metrics must be in a certain interval to classify a ride as "good" in the game.

The goal of this project is to build a model to **predict whether guests will like a roller coaster before actually building it**. In the game, but also in the real life, building a new roller coaster is very expensive and time consuming for a theme park, so the ability to know in advance if the visitors will enjoy the new ride or not is very important.

In the roller coaster industry the design phase of a ride is important, and thanks to computer softwares and computer graphics it is possible to simulate with high details of realism how a coaster project will be once built. Also the analysis of the technical specs must be conducted properly in order to respect all the safety laws, for example G-forces cannot be over a certain threshold. As the result of a so detailed design, a project of a new ride consists of all the technical deatils the ride will have and starting from this details **the algorithm will classify a ride as "good" or "not good"** for the theme park visitors in the game. 

**In the jupyter notebook it is reported the _complete project_ with descriptions and comments.**

## Main Steps of the Project
The project consist of different steps, the most important are reported here.
1. Data Reading
2. Exploratory Data Analysis and Data Cleaning
3. Some Visualization
4. Feature Engineering
5. Feature Importance and Selection
6. Feature Normalization
7. Choosing the Algorithm and Hyperparameter tuning
8. Performance of the model
9. ROC, AUC, Precision-Recall Curve
10. Threshold Tuning

## Data Set
The dataset it's been created by myself, and consists of **142 rows and 23 columns.** A new column will be added and will contain the **coaster class (response variable).** Each row is a rollercoaster created in the game, not all the rides are created by me. The majority of the columns **represent technical specification of the ride.** The definition of all the columns it is presented in the following sections. The dataset also **contains the values of the three scoring metrics: excitement, nausea and fear.**



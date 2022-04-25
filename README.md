# Prediction_Transported_Spaceship_Titanic
### Kaggle Competition Predict which passengers are transported to an alternate dimension.
### Author :- Pavan Wanjari
### Data Description
In this competition your task is to predict whether a passenger was transported to an alternate dimension during the Spaceship Titanic's collision with the spacetime anomaly. To help you make these predictions, you're given a set of personal records recovered from the ship's damaged computer system.


#### Dataset Link:- https://www.kaggle.com/competitions/spaceship-titanic/data

<img src="Titanic.jpg" style= "width:400px; height:250px">


### Problem Summary

* We are in the year 2912 and a spaceship called Titanic started off from the Earth to emigrate about 13,000 passengers to three newly habitable exoplanets.
* Before reaching it's first destinantion it collided with a spacetime anomaly and almost half of the passengers were transported to an alternate dimension.
* To help rescue crews and retrieve the lost passengers, you are challenged to predict which passengers were transported by the anomaly using records recovered from the spaceship’s damaged computer system.

* Help save them and change history!

### File and Data Field Descriptions
**train.csv** - Personal records for about two-thirds (~8700) of the passengers, to be used as training data.
* `PassengerId` - A unique Id for each passenger. Each Id takes the form gggg_pp where gggg indicates a group the passenger is travelling with and pp is their number within the group. People in a group are often family members, but not always.

* `HomePlanet` - The planet the passenger departed from, typically their planet of permanent residence.

* `CryoSleep` - Indicates whether the passenger elected to be put into suspended animation for the duration of the voyage. Passengers in cryosleep are confined to their cabins.

* `Cabin` - The cabin number where the passenger is staying. Takes the form deck/num/side, where side can be either P for Port or S for Starboard.

* `Destination` - The planet the passenger will be debarking to.

* `Age` - The age of the passenger.

* `VIP` - Whether the passenger has paid for special VIP service during the voyage.
* `RoomService`, `FoodCourt`, `ShoppingMall`, `Spa`, `VRDeck` - Amount the passenger has billed at each of the Spaceship Titanic's many luxury amenities.
* `Name` - The first and last names of the passenger.
* `Transported` - Whether the passenger was transported to another dimension. This is the target, the column you are trying to predict.
**test.csv** - Personal records for the remaining one-third (~4300) of the passengers, to be used as test data. Your task is to predict the value of Transported for the passengers in this set.

**sample_submission.csv** - A submission file in the correct format.

**PassengerId** - Id for each passenger in the test set.

**Transported** - The target. For each passenger, predict either True or False.

#### Steps

1. Import Libraries
2. Read Datasets
3. Data Exploration
4. Exploratory Data Analysis (EDA)
5. Data Cleaning
6. Data Scaling 
7. Model Building
8. Model Testing
9. Submission

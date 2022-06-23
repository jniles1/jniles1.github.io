## Energy Efficiency Linear Regression

**Project description:** 

We have been tasked with creating a predictive model of a buildings heating and cooling loads (Energy Efficiency). Our client, ABC Commercial Real Estate holdings has asked us to provide them with this predictive model so they can get and idea of the heating and cooling load of their entire portfolio without actually having to rate each building. There is a huge $ saving potential if we can provide them with an accurate way of predciting these metrics based off of the existing building characteristics they already have.

We have been provide with the building characteristics and the Heating and Cooling loads of 768 buildings in their portfolio which have already been rated. We will use this data to come out with our predictive model to help ABC Commercial Real Estate estimate their remaining 1,500 buildings in their portfolio.

Link for Jupyter Notebook : (https://github.com/jniles1/jniles1.github.io/blob/main/Projects/Energy%20Efficiency%20Model.ipynb)

**Executive Summary:**

From our exploration of the data we concluded that many of the variables do correlate well to the heating and cooling loads of the buildings and thus would be suitable to build a multiple linear regression model in order to predict the heating and cooling loads of ABC's other buildings.

After runing our model we can conclude that it scores very well in predicting the actual heating a cooling loads of a building and would thus be suitable for use to assess ABC's remaining 1,500 buildings. The models R2 scores, which rates the accuracy of the load predictions vs actual loads, rated at 0.93 for heating and 0.88 for cooling out of the highest possible score of 1. These more then meet the typical threshold of 0.8 so we can conclude that this model is viable for the clients requirements.

Although our model is accurate in predicting a buildings heating and coling loads it needs to be understood that the model does have some faults. Based on our analysis of the results, it tends to under rate the heating and cooling loads by an average of 1.5 points and almost always under rates a buildings loads when the predicted heating or cooling load is 20 or less.

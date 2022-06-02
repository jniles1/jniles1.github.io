## Energy Efficiency Linear Regression

**Project description:** 

We have been tasked with creating a predictive model of a buildings heating and cooling loads (Energy Efficiency). Our client, ABC Commercial Real Estate holdings has asked us to provide them with this predictive model so they can get and idea of the heating and cooling load of their entire portfolio without actually having to rate each building. There is huge $ saving potential if we can provide them with an accurate way of predciting these metrics based of of the existing building characteristics they already have.

We have been provide with the building characteristics and the Heating and Cooling loads of 768 buildings in their portfolio which have been rated. We will use this data to come out with our predictive model to help ABC Commercial Real Estate out so they can estimate their remaining 1,500 buildings in their portfolio.

Link for Jupyter Notebook : (https://github.com/jniles1/jniles1.github.io/blob/main/Projects/Energy%20Efficiency%20Model.ipynb)

**Executive Summary:**

From our exploration of the data we concluded that many of the variables do correlate well to the heating and cooling loads of the buildings we have data for and thus would be suitable to build a linear regression model. 

From the analysis, our model will be able to provide a fairly accurate view of their buildings heating and cooling loads. Our models for heating and cooling loads had a Root Mean Squared Error or difference between predicted and actual values of ~13%. While this isn't as accurate as we would have liked it will still provide the company with an accurate estimation of the energy efficency of their buildings if they are looking at an aggregated view of their entire portfolio. Because of the inidividual differences in actual vs predicted this model should to not be used to accurately assess the heating and colling loads of individual buildings.

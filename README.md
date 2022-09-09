# SpaceX Booster Landing Success Prediction
This project is final requirement for the completion of the **IBM Data Science Certification**. 
## The Scenario
You are a data scientist at SpaceY, a competitor of SpaceX. SpaceX advetises their Falcon 9 rocket launches with a cost of 62 million dollars compared to other providers with a cost of at least 165 million dollars. However, this descrepancy in cost is largely dependent on the reusage of the rocket boosters. If one can predict if the booster/s will land successfully or not, then they can determine whether the cost will be 62 million dollars or greater. When it is predicted that the cost is more expensive, SpaceY could approach the customers with a more affordable launch.

**The project entailed the following:**
- Data Collection through the SpaceX REST API.
- Data Collection by Webscraping Wikipedia HTML Tables.
- Data Wrangling using Pandas Library.
- Exploratory Data Analysis using Visualisation Libraries in Python.
- Exploratory Data Analysis using SQL.
- Interactive Visualisation using Folium.
- Dashboard creation using Dash and Plotly.
- Machine Learning Model tuning, comparison, and selection using scikit-learn.
- Final Powerpoint Presentation for peer assessment*

**not included in this repository*

## Results and Conclusion
A decision tree model was found to be the most successful at classifying whether a booster will successfully land or not with a 90.27% accuarcy on the training data, and a 83.33% accuracy on the testing data. It successfully predicted all successful landings from the testing data. Unfortunately, 50% of the failed landing were false positives.

<p align="center">
  <img width="600" height="600" src="https://github.com/Quantanovo/SpaceX-Booster-Landing-Success-Prediction/blob/main/Decision_Tree_Confusion_Matrix.png">
</p>
The Confusion Matrix for The Final Model on the Testing Dataset

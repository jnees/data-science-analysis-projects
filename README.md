# data-science-projects
A collection of data analysis, machine learning and data visualization projects.

## Machine Learning Projects

### [Predicting LendingClub P2P Loan Defaults](https://github.com/jnees/data-science-projects/tree/master/Predicting_Lending_Club_Loan_Defaults)

[LendingClub](https://www.lendingclub.com/) is a peer-to-peer lending platform in which individuals can apply for personal loans up to $40,000. LendingClub first reviews these applications to make sure that they meet a minimum standard for borrowing and assigns an interest rate. If the borrower agrees to the terms, Lending Club then passes the applications on to individual investors who can decide whether or not to invest $25 or more to fund the loan. If the loan is fullly funded, Lending club distributes the money to the borrower, then collects payments from them over the term of the loan and distributes cash back to the borrowers.

As in traditional banking, not every Lending Club loan actually gets repaid; some loans go into default. In this situation, the investors who backed the loan lose any principle left outstanding. This project develops a classification model to identify which loans are likely to default using all information provided to investors prior to the loan funding decision. Additionally, it demonstrates that loan screening can be used to reduce risk without reducing an investor's expected rate of return.

### [Predicting Used Car Prices by Features](https://github.com/jnees/data-science-projects/tree/master/Predicting%20Car%20Prices%20-%20KNeighbors%20Regression)

This notebook steps through the use of the k-nearest neighbors regressor to predict the listing prices of used automobiles. This technique could be used practically to estimate the actual value of a vehical, or any other product by extension, to either maximize the return on a sale or to find a bargain listing. The dataset used comes from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/automobile).

### [Predicting House Sale Prices](https://github.com/jnees/data-science-projects/tree/master/Predicting%20House%20Sale%20Prices)

Analysis project with the goal of developing a multiple regression linear model to predict the sale prices of homes using a detailed set of home features. This project requried extensive data cleaning and feature engineering.

The [dataset](https://www.tandfonline.com/doi/abs/10.1080/10691898.2011.11889627) used includes 2930 observations and 80 variables describing homes in Ames, Iowa which sold between 2006 and 2010. A description on how and why it was created can be found here and descriptions of the features in the dataset can be found [here](https://s3.amazonaws.com/dq-content/307/data_description.txt).


### [Forecasting Hourly Bike Rentals - Model Comparison](https://github.com/jnees/data-science-projects/tree/master/Predicting%20Bike%20Rentals)

A comparison of linear regression, decision tree, and random forest models on the forecasts of hourly bike share rentals. 

Forecasting sales at the hourly level for a bike share is a difficult task due to the seasonal and weather dependent nature of the business. Wind, precipitation, and unseasonably cold weather will each impact ridership negatively. It is essential to improve forecasts as much as posible in order to gain operational efficiencies and to make sure that the right number of bikes is available to meet demand. This project demonstrates that moving from Linear Regression to Decision Tree modeling yields significant gains in accuracy and that accuracy can be imporoved upon further through an ensemble method like Random Forest.

The dataset for this forecasting exercise contains 17380 observations of hourly bike share data from Washington, DC. In addition volume data, features include information about the local weather, the rider, and the day. The dataset was compiled by [Hadi Fanaee-T ad the University of Porto](http://www.liaad.up.pt/area/fanaee) and can be downloaded [here](http://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset).

# Rossman-Retail-sales-prediction
Project Summary -
Rossman Sales Prediction data is a data set that contains historical sales data for a retail store chain. The data includes information about the store, such as Competitiors Details, type, and holidays, as well as number of the customers and sales transactions, such as the date, time, and amount of each sale.

To build a machine learning model on this data, we first gathered and clean the data, and handled the null values, then we performed indepth EDA with 15 visuals and we gathered many insights from our EDA. Then further on, we did data preprocessing.

Then we split it into training and testing sets. Next, we choose a machine learning algorithm and use the training data to train the model. Finally, you we evaluated the model's performance on the testing data to see how well it is able to predict sales.

There are many different machine learning algorithms that we used for this task, including linear regression, decision trees, and random forests. It is also possible to use more advanced techniques, such as deep learning, to build a model on Rossman Sales Prediction data.

Overall, while building a machine learning model on Rossman Sales Prediction data we applied combination of data processing, machine learning techniques, and model evaluation skills. It was a challenging task, but with the right approach, we were able to create a model that can accurately predict sales for a retail store chain, and Random Forest Regression gave the best accuracy as compared to other 3 models that we trained.
Data fields
Most of the fields are self-explanatory. The following are descriptions for those that aren't.
Id - an Id that represents a (Store, Date) duple within the test set
Store - a unique Id for each store
Sales - the turnover for any given day (this is what you are predicting)

Customers - the number of customers on a given day

Open - an indicator for whether the store was open: 0 = closed, 1 = open

StateHoliday - indicates a state holiday. Normally all stores, with few exceptions, are closed on state holidays. Note that all schools are closed on public holidays and weekends. a = public holiday, b = Easter holiday, c = Christmas, 0 = None

SchoolHoliday - indicates if the (Store, Date) was affected by the closure of public schools
StoreType - differentiates between 4 different store models: a, b, c, d

Assortment - describes an assortment level: a = basic, b = extra, c = extended

CompetitionDistance - distance in meters to the nearest competitor store

CompetitionOpenSince[Month/Year] - gives the approximate year and month of the time the nearest competitor was opened

Promo - indicates whether a store is running a promo on that day

Promo2 - Promo2 is a continuing and consecutive promotion for some stores: 0 = store is not participating, 1 = store is participating
Promo2Since[Year/Week] - describes the year and calendar week when the store started participating in Promo2

PromoInterval - describes the consecutive intervals Promo2 is started, naming the months the promotion is started anew. E.g. "Feb,May,Aug,Nov" means each round starts in February, May, August, November of any given year for that store

Conclusion
The Rossmann dataset is a large dataset of sales data for a chain of German pharmacies. The dataset includes over a million rows of data, with various features such as store location, type of product sold, and various sales metrics. In a machine learning project using the Rossmann dataset, you would likely start by exploring the data and trying to understand the relationships between different features and sales outcomes. You might also want to perform some data cleaning and preprocessing to ensure that the data is ready for modeling. Once you have prepared the data, you could use a variety of machine learning algorithms to build models that predict sales outcomes based on the available features. Some common approaches might include linear regression, decision trees, or random forests. You could also use more advanced techniques such as gradient boosting or neural networks whcih are beyond the scope of this present project and surely be included in future. Ultimately, the conclusion of a machine learning project using the Rossmann dataset would depend on the specific goals and objectives of the project. However, a common goal might be to build a model that is able to accurately predict sales outcomes based on the available features, and to use that model to make informed decisions about how to optimize sales and improve business performance.

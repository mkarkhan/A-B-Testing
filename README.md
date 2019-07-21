# A-B-Testing
We will perform A/B Testing on a new web page for a company to understand if the new page helps the company get more users to convert or pay for their service. A/B tests are commonly performed in companies to test how a new page does as compared to an old page in terms of a tangible result. TData regarding the new page has been provided to us in a csv file.

First we will view and observe the data for any data quality issues. Then we will quickly clean the data to ensure all data has correct values. Following this, we will compute some probabilities such an probability an individual converts with either page present, probability if person will convert for old page or new page, etc. The people that receive the old page are in the control group. Those who receive the new page are in the treatment group.

We next conduct hypothesis testing on the data, stating a null and alternative hypothesis and then rejecting or failing to reject the null based on the results of the test. We will compute similar test statistics using statsmodels.api library. We then run the stats.proportions_ztest to get the p-value.

The results that we achieve using the A/B Tests can similarly be achieved using Regression approach. In the final part, we will use statsmodels to fit the regression model to see if there is a significant difference in conversion based on which page a customer receives.

<b> Installation </b> : You need to be able to open a Jupyter notebook and work in it on your computer. You will need to ensure the following packages are instaled on it:

NumPy
pandas
statsmodel.api

We can install these packages using pip or conda. 

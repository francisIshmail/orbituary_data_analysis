# orbituary_data_analysis
#Tasks on the data are:
1. Create a Kaplan-meier survival curve using one of the following variables; gender, colour, fundraising, spouse alive, spouse gender. Explain the difference/significance of the result. 

2. Predict deaths that are likely to need fundraising. Use algorithm of your own choice. Include the confusion matrix, F1 score, sensitivity, and specificity.

Conclusion:

The classifer is using a total of 455 predictions. 

From the data above, we can see that we had predicted that the people who will require fundrasing are 350 and those that don't
require fundraisng were 105 cases out of the total of 455 people.

After running the confusion matrix of the actual data, we get the actual no of people who need fundraising to be 278 and the 
people who do not need fundraising are actually 177 cases.

Therefore from the total predictions: 
    
true positives (TP) are 207 cases: These are cases in which we predicted yes (they have the fundraiser), and they do have the fundraiser.

true negatives (TN) are 71 cases: We predicted no, and they don't fundraisers

false positives (FP) are 143 cases: We predicted yes, but they don't actually have the fundraiser i.e: "Type I error."

false negatives (FN) are 34 cases: We predicted no, but they actually do have the fundraiser. "Type II error."


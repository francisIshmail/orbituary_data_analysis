# orbituary_data_analysis

NB: The data contains the explanations. 

#Tasks on the data are:
1. Create a Kaplan-meier survival curve using one of the following variables; gender, colour, fundraising, spouse alive, spouse gender. Explain the difference/significance of the result. 

Brief Analysis

From the above curve, of Kaplan Meier using Gender, we come with the conclutions:
    
    1. The data is not extremelty clean and we have negative days from the date of death. This essentially means that a person
    was burried before they died which is impossible. 
    This explains why we have -100 in the graph above.
    
    2. The Average number of days of ones burial after death is 7.0 days.
    
    3. We have extreme cases of people who are buried after more than a year which creates the extreme ends in the cahrt.
    
    4. The probability of burial after death is 0.378490,  which essentially is 37%.
    

2. Predict deaths that are likely to need fundraising. Use algorithm of your own choice. Include the confusion matrix, F1 score, sensitivity, and specificity.

Conclusion from using the Confusion Matrix (Refer to code in the Obituaries_Dataset.ipynb):

The classifer is using a total of 455 predictions. 

From the data above, we can see that we had predicted that the people who will require fundrasing are 350 and those that don't
require fundraisng were 105 cases out of the total of 455 people.

After running the confusion matrix of the actual data, we get the actual no of people who need fundraising to be 278 and the 
people who do not need fundraising are actually 177 cases.

Therefore from the total predictions: 
    
true positives (TP) are 207 cases: These are cases in which we predicted yes (they have the fundraiser), and they do have the fundraiser.

true negatives (TN) are 71 cases: We predicted no, and they did not do fundraising 

false positives (FP) are 143 cases: We predicted yes, but they did a fundraiser i.e: "Type I error."

false negatives (FN) are 34 cases: We predicted no, but they actually did not have the fundraiser. "Type II error."


 **Question-1**  
What is one reason False Positive classifications were expensive in the Battle of Britain?  
* Pilots needed more practice.  
* German bombers were always present.  
* German bombers would expect to be intercepted.  
* **Aviation fuel for fighter planes was scarce.**  

**Question-2**  
The portion of test outcomes that are True Negatives plus the portion that are False Negatives must equal  
* **One, minus the classification incidence/test incidence**  
* The Negative Predictive Value (NPV)  
* One, minus the condition incidence   
* The False Negative (FN) Rate  

#### ***Use the Cancer Diagnosis Spreadsheet to answer Questions 3 and 4.***

**Question-3**   
This spreadsheet gives 10,000 pairs of scores – the level of a (fictional) cancer diagnostic protein in Column A - along with the actual condition: 1 = cancer, 0 = no cancer in Column C.  
Change the cost per False Negative classification to $20,000 [cell G3]. Change the cost per False Positive classification to $1,000 [cell H3].  
Question: What is the new minimum cost per event/cost per test (rounded to the nearest dollar)?  
* **$183**  
* $181  
* $185  
* $187  

**Question-4**  
What is the lowest level of protein that should be classified "Positive" to achieve the minimum cost per test at the new costs per error given above?  
* **18204.498** 
*  18204.545
*  18202.407
*  18213.7  

**Question-5**  
Can a change in classification threshold change a diagnostic test's True Positive Rate? Use logic - no need to calculate any numbers.  
* **YES**  
* NO  
(Yes Because,The number of Condition Positives is constant. But by moving one or more positive outcomes above or below the threshold the number of True Positive classifications changes. This changes the True Positive Rate, which is the ratio of True Positive classifications to total Condition Positives.)  

**Question-6**  
"Condition Incidence" is the portion of a population that actually has the Condition being studied. Can a change in threshold change the Condition incidence? Use logic - no need to calculate any numbers.  
* YES  
* **NO**   
(answer is 'NO' because,Moving the threshold changes only classifications, not actual Conditions.)  


**Question-7**  
Does the change in threshold change the test’s “classification incidence” (also called “test incidence”)? Use logic - no need to calculate any numbers.  
* **YES**  
* NO  
(YEs because,Moving the threshold down increases the proportion of outcomes classified as positive. Moving the threshold up reduces the proportion of outcomes classified as positive)  

**Question-8**  
Does the change in threshold change the test's Area under the ROC Curve? Use logic - no need to calculate any numbers.  
* **NO**  
* YES  
(NO because,Points on the ROC curve represent the false positive rate and true positive rate at each possible threshold. Changing the threshold signifies a different point on the ROC Curve, but does not change the overall shape of the curve.)  

**Question-9**  
Use the Forecasting Soldier Performance Spreadsheet to answer this question:  

What is the False Positive Rate if we use the sum of standardized height and standardized weight as the score; and set a threshold at -1.28?  
*  0.6
* **0.67** 
*  0.4
*  0.33  
(answer is 0.67 because,At the threshold given, there are 5 TPs, 1 FN, 4 FPs and 2TNs. Six soldiers have condition negative, so the FP rate would be 4/6 or 2/3 = .67)  





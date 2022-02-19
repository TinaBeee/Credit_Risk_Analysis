# Supervised Machine Learning
Assessment of credit risk using different imbalanced-learn and scikit-learn libraries

## Resources
- Data: LoanStats_2019Q1.csv - dataset from peer-to-peer lending company LendingClub
- Software: Jupyter Notebook 6.3.0, imbalanced-learn, scikit-learn, Numpy and Pandas libraries

## Overview
Analysis of credit risk of an imbalanced dataset containing 115,000+ rows of loan data, including loan amount, interest rate, applicant income, etc.
Set the loan status column as the target variable, with all other variables set as features. Loan status column was cleaned to only include "low risk" and "high risk" as selection criteria. The original dataset conatained 68,470 instances of "low risk" and 347 instances of "high risk" - or 99.49% of the target dataset contained low risk loan applicants.

Use of the following six machine learning models to assess the balanced accuracy, precision and recall scores: random oversampling, synthetic minority oversampling technique (SMOTE), undersampling with cluster centoid, combination sampling using SMOTE and Edited Nearest Neighbors (SMOTEENN),balanced random forest, and AdaBoost.

## Results
- Random Oversampling
   - Around 64% accuracy 
<img width="300" alt="Screen Shot 2022-02-19 at 13 13 54" src="https://user-images.githubusercontent.com/90064437/154815565-808c08c7-bb0a-4a2f-81d6-96a2202b2fe8.png">

  - 
<img width="500" alt="Screen Shot 2022-02-19 at 13 14 55" src="https://user-images.githubusercontent.com/90064437/154815605-f4925f23-7159-46d6-8eb3-7144fc011ccf.png">

- SMOTE
<img width="300" alt="Screen Shot 2022-02-19 at 13 16 05" src="https://user-images.githubusercontent.com/90064437/154815669-4f5e6608-2b9f-4634-a0a4-232cca74c2ee.png">

<img width="500" alt="Screen Shot 2022-02-19 at 13 16 38" src="https://user-images.githubusercontent.com/90064437/154815675-b5d70757-1808-4fd4-8b26-fa5b35b99730.png">

- Undersampling Cluster Centoid
<img width="300" alt="Screen Shot 2022-02-19 at 13 17 47" src="https://user-images.githubusercontent.com/90064437/154815714-9a0d709b-812a-456e-b30d-c14e9a4693fb.png">

<img width="638" alt="Screen Shot 2022-02-19 at 13 17 56" src="https://user-images.githubusercontent.com/90064437/154815726-d3b9ab8f-4298-4cb7-b6a1-e5c091ce1202.png">

- SMOTEENN
<img width="391" alt="Screen Shot 2022-02-19 at 13 18 50" src="https://user-images.githubusercontent.com/90064437/154815770-fe212f36-525c-4786-aa7b-116fe8e14e51.png">

<img width="645" alt="Screen Shot 2022-02-19 at 13 18 59" src="https://user-images.githubusercontent.com/90064437/154815776-1ba23c12-d70c-4e93-9bc8-1ba02bfecac3.png">

- Balanced Random Forest
<img width="300" alt="Screen Shot 2022-02-19 at 13 23 42" src="https://user-images.githubusercontent.com/90064437/154815911-f60cea18-8eee-49b7-a1ba-1ab308fefcb3.png">

<img width="500" alt="Screen Shot 2022-02-19 at 13 23 52" src="https://user-images.githubusercontent.com/90064437/154815921-ec18a0a0-cfb0-4ec0-a3e9-0d02b1dcce34.png">

- AdaBoost
<img width="300" alt="Screen Shot 2022-02-19 at 13 25 03" src="https://user-images.githubusercontent.com/90064437/154815947-641e09a3-9426-408f-a2f3-0ab46876411c.png">

<img width="500" alt="Screen Shot 2022-02-19 at 13 25 13" src="https://user-images.githubusercontent.com/90064437/154815950-6902d0eb-16c5-4951-9703-7966f71fd279.png">



  

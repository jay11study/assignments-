Task 1

Label:
repeat_purchase_flag
Justification: This is the target variable because it represents the outcome we are trying to predict (whether a customer makes a repeat purchase within 30 days).

Data Leakage Feature:
discount_used_on_repeat_order
Justification: This feature uses information that is only available after the repeat purchase happens, so including it would leak future information into the model.


Task 2

Step 1: Having a Baseline Model
Explanation: A simple baseline helps us understand the minimum performance level and whether a complex model actually adds value.

Step 2: Data Splitting (Train/Test/Validation Split)
Explanation: Splitting the data ensures that model performance is evaluated on unseen data, preventing overfitting and giving a realistic measure of how the model will perform in production.

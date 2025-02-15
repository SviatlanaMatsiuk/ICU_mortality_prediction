Introduction

ICU Care is expensive, and critical and the last line of defense. Predicting mortality or the development of other morbidities in the ICU is critical to staying ahead of developments and ensuring survival, or triaging resources to ensure effective allocation. 

Tasks

Use the dataset linked below, to predict whether or not a patient will survive in the ICU. All details of the dataset can be found at the link. You might need to create an account, and sign a Data Use Agreement to get access. 

https://physionet.org/content/widsdatathon2020/1.0.0/data/#files-panel Links to an external site.

Important:

1. Use the submission template provided. Provide documentation and an explanation for every step. 

2. Provide all details of any data cleaning and data exploration you performed, including number of rows deleted, columns deleted or merged etc. Motivate your reasoning for why you performed any cleaning/pre-processing. 

3. Use imputation for missing values. You can choose any imputation strategy, but motivate your reasoning for your strategy. 

4. Understand the class balance, and handle imbalances, if any. Tune your model to perform equally well on all classes. 

4. Test atleast two different models, several is preferred, and specify your best performing model. 

5. Compare your (best) model performance not only against each other, but against your choice of imputation strategy. Do the same for class imbalance. Does your model perform better or worse with or without imputation? Similarly, is it better to impute missing data or to throw it out? 

6. Use feature importance techniques to describe which features best predict mortality. 

7. Explore the time dimension to determine if there is adequate data to perform framing, or windowing to estimate trends of risk. For instance, if there is time series data available in the dataset, can you use windowed chunks to observe how risk of mortality changes over time? Motivate your answer. 
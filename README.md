# Prediction-of-skills-and-job-profile-based-on-Description
The given data comprises of the “Title” and “Description” using which you will create a multilabel classification system. Preferably implementing Deep Neural Networks to classify skills based on the description of the job title. Input will be the “Description” of any job and required output is the skill set, domain &amp; job title pertaining to the input description by the user.


Steps Followed to solve the case study :
1. Created a data frame which contains Description along with job title and
corresponding skills.
2. Independent variable - Description
 Dependent variable - Job title and Skills
3. Performed preprocessing on Description (removed stop words and performed
lemmatization)
4. Performed one hot encoding and embedding on Description.
5. Created a column containing index of job title which will is output feature to
be predicted by model.
6. Created sequential model by adding the layers and optimizer by using hit and
trial method, picked that model which resulted in higher accuracy.
7. Output of the model is the index with which I was able to get the corresponding
job title and skill.
8. Accuracy of test_data is 92.97%

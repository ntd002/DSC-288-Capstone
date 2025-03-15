# DSC-288-Capstone
- This GitHub is a collection of our work throughout this quarter.
- Usage Note: All notebooks can be run in Google Colab after uploading the required dataset.

## Final Report 
### Instructions
For those reviewing our project, please download our [dataset](https://github.com/ntd002/DSC-288-Capstone/blob/main/Milestone%204%3A%20Final%20Report/DSC%20288%20Processed%20Reddit%20Dataset.csv) and upload to the various notebooks to examine our ouputs. 

"[Folder: Milestone 4: Final Report](https://github.com/ntd002/DSC-288-Capstone/tree/main/Milestone%204%3A%20Final%20Report)" contains the most up to date models used in our final report:
- Final Report [Document](https://github.com/ntd002/DSC-288-Capstone/blob/main/Milestone%204%3A%20Final%20Report/04-Report.pdf)
- Preprocessed [Dataset](https://github.com/ntd002/DSC-288-Capstone/blob/main/Milestone%204%3A%20Final%20Report/DSC%20288%20Processed%20Reddit%20Dataset.csv) (.csv) 
- "[DSC_288_MultinomialNB_Final](https://github.com/ntd002/DSC-288-Capstone/blob/main/Milestone%204%3A%20Final%20Report/DSC_288_MultinomialNB_Final.ipynb)" and "[DSC_288_Latent_Dirichlet_Allocation_Final](https://github.com/ntd002/DSC-288-Capstone/blob/main/Milestone%204%3A%20Final%20Report/DSC_288_Latent_Dirichlet_Allocation_Final.ipynb)" have extra metrics added and some new plots compared to previous iterations. (Note: the LDA model may take upwards of 30 minutes to run.)
- "[DSC_288_Application](https://github.com/ntd002/DSC-288-Capstone/blob/main/Milestone%204%3A%20Final%20Report/DSC_288_Application.ipynb)" is a barebones attempt at creating a recommendation tool. After adding the dataset, one could type into the question variable and receive a couple mental health website recommendations.



### Final Report: Abstract
Identifying and categorizing mental health discussions on popular internet forums like Reddit can help improve accessibility to support resources and contribute to automated mental health assistance. This study applies machine learning techniques to classify Reddit posts into key mental health topics, facilitating potential future resource recommendation systems. We scraped and preprocessed a dataset of 12,951 Reddit posts, implementing two models: Multinomial Naïve Bayes (MultiNB) for classification and Latent Dirichlet Allocation (LDA) for topic modeling. Our results demonstrated that MultiNB, using both title and body text, achieved the highest classification accuracy, while LDA was ineffective for predefined topic classification. We also explored hyperparameter tuning and preprocessing techniques, which improved MultiNB’s performance by 14.1%. Despite promising results, limitations such as data bias, ethical concerns around misclassification should be considered. Future work should explore transformer-based models (e.g., BERT) and integrate classification outputs into practical mental health support applications.

Continue viewing full report: Final Report [Document](https://github.com/ntd002/DSC-288-Capstone/blob/main/Milestone%204%3A%20Final%20Report/04-Report.pdf)


## All Milestones and Materials
- The Team Contract and Project Abstract are self-explanatory.

### M2
 "Milestone 2: 1st Progress Report" contains all coding related to that including:
- "Step 1: Scraping Reddit" includes code for accessing Reddit's API and assembling the raw dataset.
- "Step 2: Preprocessing Data" includes code for preprocessing the raw data into a dataset we would use from here on out.
- "Step 3: Initial Modeling" includes an early Multinomial Naive Bayes model, Exploratory Data Analysis, and our 1st Progress Report.

### M3
"Milestone 3: 2nd Progress Report" includes:
- "DSC_288_MultinomialNB_Optimization" notebook which is a more up to date and optimized model.
- "DSC_288_Latent_Dirichlet_Allocation" notebook which is the attempt to use LDA modeling.
- The PDF version of the 2nd Progress Report powerpoint.
- The video presentation is not here as there was trouble uploading a file of that size. See the [course folder](https://drive.google.com/drive/folders/110CcHE6brXFoLajaCoHHTkSpnWU8PUcy).

### M4
"Milestone 4: Final Report" contains the most up to date models used in our final report:
- "DSC_288_MultinomialNB_Final" and "DSC_288_Latent_Dirichlet_Allocation_Final" have extra metrics added and some new plots compared to previous iterations.
- "DSC_288_Application" is a barebones attempt at creating a recommendation tool. After adding the dataset, one could type into the question variable and receive a couple mental health website recommendations.

# DSC-288-Capstone
This GitHub is a collection of our work throughout this quarter.

**Usage Note**
- All notebooks can be run in Google Colab after uploading the required dataset.
- The LDA model may take upwards of 30 minutes to run.** 

## Abstract
In seeking to identify core mental health topics within Reddit posts via classification into key treatment or support domains, we aim to pave the way for future systems that recommend mental health resources. We scraped and preprocessed a dataset of 12,951 Reddit posts and implemented two primary models: Multinomial Naïve Bayes (MultiNB) for classification and Latent Dirichlet Allocation (LDA) for topic modeling. Our results showed that MultiNB with both title and body text provided the highest accuracy, while LDA abstracted topics but was not useful for classification. We explored hyperparameter tuning, common word removal, and model evaluation, concluding that optimizing MultiNB significantly improved performance while LDA was less effective. Future work could incorporate more advanced NLP models and applications for connecting users to tailored resources.


## Milestones and Materials
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

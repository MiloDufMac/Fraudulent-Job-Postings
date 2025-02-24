## Description
This dataset contains listing information for legitimate and fradulent job postings from a variety of industrys. With the job market increasingly shifting online, this dataset offers a wealth of information capable of building machine learning models (MLM).

### Dataset Context and Purpose
With job hunting becoming an increasingly online activity, it's more important than ever to remain cognizant of fake job postings. This dataset thus allows analysts and researchers employed by popular online job markets create models using text data and key traits/features to predict real versus fake job descriptions.

### Content
Included in this section are brief descriptions of the columns included in the dataset
* **location** - geographical location of the job ad.
* **department** - coporate department (i.e. sales)
* **salary_range** - indicative salary range (e.g. \$50,000 - \$60,000)
* **company_profile** - brief company description
* **description** - details description of the job ad
* **requirements** - enlished requirements for the job opening
* **benefits** - enlishted offered benefits by the employer
* **telecommuting** - true (1) for telecommuting positions
* **has_company_logo** - true (1) is company logo is present
* **has_questions** - true (1) if screening questions are present
* **employment_type** - full-time, part-time, contract, etc.
* **required_experience** - executive, entry level, intern, etc.
* **requred_education** - doctorate, masters, bachelor's degree, etc.
* **industry** - automotive, IT, health care, real estate, etc.
* **function** - consulting, engineering, research, sales, etc.
* **fradulent** - target-classification attribute. (~800 [4.47%] listings in this dataset are fake)

## Questions about the Data
The following questions will help team members gain an understanding of the dataset, identify common characteristics of fradulent listings, and build a predictive model with the goal of providing more context to the question, "how can we spot a fake job description?"

#### Familarizing Ourselves with the Dataset:
* What are the most common department, salary range, employment type, industry, and function of the dataset? Does this different between legitmate and fradulent listings?
* Where are real and fake job listings coming from? (location and company)
* What is landscape of benefits, required experience, required education, and other "additional" details within the dataset? How does this compare across real and fake listings?

#### Building a Predictive Model
* Which input columns fit our data the best in predicting the legitimacy of job listings?

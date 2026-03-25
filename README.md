# Random-Stratified-Sampling-of-Farmers-Across-Counties
This project implements a random stratified sampling procedure to select 120 farmers from three counties. Each county contributes 40 farmers, ensuring balanced representation across key demographic and contextual variables.

Sampling Criteria
The sampling framework is designed to capture diversity across multiple dimensions:
Sex of farmer: Male and Female
Age groups:
17–29 years (both male and female)
30–65 years (both male and female)
Village clustering: Villages categorized by low, medium, and high farmer concentration
Cohorts ("instances"): Sampling across recruitment cohorts as defined in the dataset

Methodology
Data Preparation: Farmer records are cleaned and categorized by sex, age, village cluster, and cohort.
Stratification: Farmers are grouped into strata based on the above criteria.
Random Sampling: Within each stratum, farmers are randomly selected to meet thequota of 40 per county.
Output: A CSV file (random_sample.csv) containing the final sample of 120 farmers.

Files in Repository
random_sampling_farmers.ipynb → Jupyter Notebook with code for sampling
random_sample.csv → Output file containing sampled farmers
README.md → Documentation of project scope and methodology

Usage
Open the notebook random_sampling_farmers.ipynb.
Run the cells to reproduce the sampling process.
The final sample will be saved as random_sample.csv.

Notes
Ensure reproducibility by setting a random seed in the notebook.
The sampling logic can be adapted if new strata or counties are introduced.

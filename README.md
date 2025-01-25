# Data-analysis-with-ML


This project was conceived in an academic context, in the curricular unit "Intelligent Systems for Bioinformatics" of the master's degree in Bioinformatics and was developed by:

- [Carlos Gomes](https://github.com/CarlosGomes00)
- [Diogo Esteves](https://github.com/dasesteves)
- [Joana Lopes](https://github.com/joanalopes7)
- [Tiago Miranda](https://github.com/tiagomiranda24)


**Project Overview**

This project involves the analysis of a dataset using machine learning algorithms with Python as the programming language. The work will be documented in a Jupyter Notebook, organized into sections, which will include the steps of the analysis performed. Each section will succinctly explain the procedures undertaken and the decisions made throughout the analysis.

The dataset chosen for this project is derived from the [DisGeNET](https://tdcommons.ai/multi_pred_tasks/gdi#disgenet) platform, specifically focusing on gene-disease associations. DisGeNET is a comprehensive knowledge platform that integrates data from various sources to provide extensive information on the relationships between genes and diseases.




**Project Structure**

To enhance readability and ensure a smoother flow, the content to evalutation has been divided into three separate Jupyter Notebooks. The repository includes the following files:

**"Section 1_Exploratory Analysis and Preprocessing Tasks":** This section includes a description of the data according to the available literature, as well as an exploratory analysis using graphs to illustrate the main characteristics of the data. Additionally, it contains the methodology adopted for preprocessing and the respective justifications.

**"Section 2 and 3_Unsupervised Learning and Machine Learning Task":** In this section, unsupervised analysis techniques, dimensionality reduction, and data visualization methods are applied. Moreover, this file includes Section 3 of this work, which corresponds to the Machine Learning task, where the performance of various ML models/algorithms is compared using error metrics appropriate to our problem. The best model we achieved is also identified and explored.

**"Section 4_Deep Learning Task":** Similarly to the objectives of Section 3, methods of Deep Learning are applied in Section 4.

**"Primary exploration of DL models":** This unstructured file corresponds to the initial exploration of DL models, containing the Deep Learning information presented during the intermediate classroom evaluation. It served as the foundation for improving our approach to the Deep Learning models proposed as "future work," which are presented in the "Section 4_Deep Learning Task" notebook. This file can be found in the "recycling" folder.

**"Gene-Disease Association Prediction presentation":** This PDF file corresponds to our presentation for the intermediate evaluation that took place on January 13, 2025.<br>




Additionally, the repository references several **CSV files** that are not included due to their large size and that can be requested from the project collaborators:

**"dataset_with_new_embeddings"** - Contains the embeddings generated with BioBERT for the textual descriptions of diseases.

**"full_data_sequence_embeddings"** - Contains the embeddings generated using k-mers + Word2Vec for amino acid sequences.

**"final_df"** - The dataset with all preprocessing applied to the original data.

**"final_df_ML"** - A subset of "final_df" containing only the columns necessary for machine learning and deep learning tasks.<br>




To ensure that all the project's dependencies are installed correctly, we recommend using a Conda environment. You can easily create the environment with the project's dependencies from the env.yml file included in this repository.<br>

**Steps to set up the environment:**

**1. Make sure you have Conda installed.**
If you don't have Conda installed, download and install Miniconda or Anaconda.

**2. Clone the repository to your local machine:**
If you haven't cloned the repository yet, use the following command to clone it:

```
git clone https://github.com/joanalopes7/Data-analysis-with-ML
```

**3. Create the Conda environment from the env.yml file:**
Navigate to the cloned project directory and run the following command to create the Conda environment with the required dependencies:

```
conda env create -f env.yml
```

**4. Activate the Conda environment:**
Once the environment is created, activate it with the following command:

```
conda activate noteSI
```
Note: The environment name is specified in the env.yml file. If you haven’t changed the file, the default name will be the one listed there.

**5. Verify that the dependencies & environment were installed correctly:**  
You can check if the environment was created successfully and if all dependencies were installed by running:

```
conda list
conda env list
```

**6. You're all set!**

# Predictive-Modelling-of-Breast-Cancer-Relapse-Using-Machine-Learning-and-Deep-Learning-Techniques
The primary objective of this study was to forecast the relapse of breast cancer by employing a fusion of machine learning (ML) and deep learning (DL) methodologies. 

# ABSTRACT
The study employs a dataset that comprises clinical and molecular information from individuals diagnosed with breast cancer. This includes data on demographics, histopathological characteristics, treatment specifics, and gene expression profiles. Conventional machine learning (ML) algorithms such as Logistic Regression, Random Forests, Gradient Boosting, Light Gradient Boosting, Extreme Gradient Boosting, Linear Discriminant Analysis, and a deep learning (DL) architecture called Artificial Neural Networks are used to create models and capture intricate genomic patterns. 

# I.	INTRODUCTION
----

A.	The Problem
-----
Cancer is a group of diseases characterised by the growth of abnormal cells that can invade and metastasise to other parts of the body. Breast cancer is the predominant form of cancer in women and is the leading cause of cancer-related deaths among women, highlighting its significance in public health [1].

B.	Identified Dataset
-----
The dataset explored for this study Targeted sequencing of 2509 primary breast tumours with 548 matched normals. The dataset has 2,509 rows and 39 columns. The columns contain various clinical, pathological, and molecular characteristics of breast cancer patients, which can be used for predictive modelling and analysis. The target variable is 'relapse-free status', which indicates whether the patient experienced relapse during the study period. The dataset was spooled from an online repository provided by cBioPortal for cancer genomics [11]. 

C.	Existing Work
-----
Breast cancer relapse is influenced by various factors, one of which is the existence of cancer stem cells (CSCs) that display resistance to conventional treatments [5].  Although endocrine therapy is the standard treatment for estrogen receptor (ER)-positive breast cancer, it can result in acquired resistance, which in turn leads to the relapse of the disease and its spread to other parts of the body [6]. 

# II.	METHODOLOGY
----
The methods used to construct the study's predictive model for relapse prediction in breast cancer using machine learning and deep learning are detailed in this section. An outline of the study's data, its preparation steps, and the machine learning and deep learning techniques used to construct the predictive model are presented in this part.

A.	Preliminary Data Analysis
----
The dataset was read with "df = pd.read_csv" and "df.head()" displayed the initial five patient records in the dataset. This provides a concise summary of the data's appearance and the types of fields that are recorded.

B. Data Cleaning & Treating Missing Values
----
The optimal approach for replacing missing values in a column containing floating-point values is contingent upon the data's distribution and the existence of outliers. The missing values in the 'age at diagnosis' and 'nottingham prognostic index' columns will be addressed using the mean imputation technique [18]


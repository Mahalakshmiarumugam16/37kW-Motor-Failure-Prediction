#  Predictive Maintenance of 37 kW Motor using Machine Learning

>  Real-world industrial project developed during internship at ELGi Equipment Limited

---

##  Overview

This project focuses on analyzing operational data from **37 kW air compressor motors** to predict potential failures and improve maintenance strategies.
By leveraging machine learning and clustering techniques, the project aims to identify early warning signals and reduce unexpected breakdowns.

---

##  Problem Statement

Traditional maintenance methods are reactive, which often leads to:

* Unexpected equipment failures
* Reduced machine lifespan
* Increased operational and repair costs

This creates a need for a **predictive maintenance approach** that can detect issues before failure occurs.

---

##  Objective

The objective of this project is to develop a system that:

* Detects failure patterns in motor data
* Identifies high-risk operating conditions
* Improves equipment reliability and workflow efficiency

---

##  Dataset Description

The dataset contains field data collected from **1,484 air compressor motors (37 kW)** with **47 features**.

###  Features include:

* Electrical parameters (voltage, current, resistance)
* Mechanical performance indicators
* Operational and startup characteristics

###  Target Variable:

* `1 → Motor Running`
* `0 → Motor Failed`

---

##  Data Preprocessing

To prepare the data for analysis:

* Removed irrelevant and redundant features
* Cleaned missing values
* Standardized column names for consistency
* Selected key parameters related to motor performance

This resulted in a structured dataset suitable for analysis and modeling.

---

##  Workflow

```
1. Motor Dataset (37 kW)
2. Data Cleaning & Segregation
3. Univariate Feature Analysis
4. DBSCAN Clustering
5. Cluster Visualization
6. At-Risk Motor Identification

```

---

##  Methodology

### 1️. Data Preparation

* Cleaned dataset and handled missing values
* Divided data into **running and failed motors**

---

### 2️. Feature Analysis

* Performed univariate analysis on each parameter
* Identified abnormal ranges and potential failure indicators

---

### 3️. DBSCAN Clustering

* Applied DBSCAN on failed motor data
* Used adaptive epsilon (based on distance distribution)
* Detected clusters representing failure patterns

---

### 4️. Visualization

* Created clear cluster plots for each feature
* Highlighted:

  * Failure ranges
  * Cluster density
  * Outliers

---

### 5️. Risk Detection

* Compared failed motor clusters with running motors
* Identified motors operating in high-risk zones

---

##  Results

* Identified **failure-prone regions in 37 key parameters**
* Found **20 parameters with strong failure indicators**

###  Example Insight:

* A specific resistance parameter showed:

  * Distinct high-risk ranges
  * Clearly separated stable operating zone

This confirms the effectiveness of clustering in detecting failure conditions.

---

##  Interpretation

* Certain operating ranges are strongly associated with motor failure
* Some failures occur even under low usage conditions
* Motors operating within failure zones are at higher risk

 These insights support early detection and preventive maintenance.

---

##  Conclusion

* Successfully identified critical failure patterns in motor data
* Developed a predictive approach to monitor motor health
* Reduced the risk of unexpected breakdowns

---

##  Business Impact

* Enhances equipment reliability
* Reduces downtime and maintenance cost
* Supports efficient and lean manufacturing processes
* Improves overall product quality

---

##  Internship Experience

This project was completed during my internship at **ELGi Equipment Limited**, working with real industrial datasets.

---

##  Key Highlight

> This project demonstrates the practical application of machine learning and clustering techniques on real-world industrial data for predictive maintenance.

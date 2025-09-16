# 🤖 Oracle Cloud Infrastructure Data Science Professional  

## Study Notes & Summaries  

_A comprehensive guide based on the official Oracle Data Science Professional Course._  

> 📌 _This is a summary of Oracle University lessons. No personal analysis or opinion is included._  

> ⚙️ **Note:**  
> As part of this course, I will implement the Data Science applications separately using **Databricks Community Edition**, rather than using **Jupyter Notebooks** as shown in the course. All my practical implementations will be stored under the `/DataScience_Projects` folder.  

---  

## 🏅 Certification  

![OCI Data Science Certificate](oracle-cloud-infrastructure-generative-ai-professional/img/1.jpg)  

**Oracle Cloud Infrastructure 2025 Data Science Certified Professional**  
Certified on **[Insert Date After Passing]**  
*Issued by Oracle University*  

---  

## 📘 Course Overview  

- **Platform:** Oracle Learning  
- **Goal:** Learn how to design, implement, and manage the complete Machine Learning lifecycle on OCI, including workspace setup, data preparation, training, deployment, and MLOps practices.  

---  

## 🧭 Course Structure  

### 1. Welcome to Data Science  

- [x] Course Overview *(7 min)* – ✅ _No notes_  
- [x] Expert Tips: Intro *(1 min)* – ✅ _No notes_  

### 2. Introduction and Configuration  

- [ ] Data Science: Introduction *(16 min)* – ✅ [See Summary](#data-science-introduction)  
- [ ] ADS SDK Overview *(14 min)* – ✅ [See Summary](#ads-sdk-overview)  
- [ ] Tenancy Configuration Basics *(13 min)* – ✅ [See Summary](#tenancy-configuration-basics)  
- [ ] Configure a Tenancy with OCI Resource Manager *(4 min)* – ✅ [See Summary](#configure-a-tenancy-with-oci-resource-manager)  
- [ ] Networking for Data Science *(8 min)* – ✅ [See Summary](#networking-for-data-science)  
- [ ] Authenticate to OCI APIs *(5 min)* – ✅ [See Summary](#authenticate-to-oci-apis)  
- [ ] Skill Check: Introduction and Configuration – ✅ [See Summary](#skill-check-introduction-and-configuration)  

### 3. Workspace Design and Setup  

- [ ] Projects *(6 min)* – ✅ [See Summary](#projects)  
- [ ] Notebook Sessions *(10 min)* – ✅ [See Summary](#notebook-sessions)  
- [ ] How to Work with JupyterLab *(14 min)* – ✅ [See Summary](#how-to-work-with-jupyterlab)  
- [ ] Conda Environments: Overview *(8 min)* – ✅ [See Summary](#conda-environments-overview)  
- [ ] Data Science Conda Environments *(15 min)* – ✅ [See Summary](#data-science-conda-environments)  
- [ ] Manage Conda Environments *(11 min)* – ✅ [See Summary](#manage-conda-environments)  
- [ ] Demo: Manage Conda Environments *(16 min)* – ✅ [See Summary](#demo-manage-conda-environments)  
- [ ] OCI Vault: Introduction *(12 min)* – ✅ [See Summary](#oci-vault-introduction)  
- [ ] Using OCI Vault in OCI Data Science *(15 min)* – ✅ [See Summary](#using-oci-vault-in-oci-data-science)  
- [ ] Code Repositories (Git) *(21 min)* – ✅ [See Summary](#code-repositories-git)  
- [ ] Demo: Code Repositories (Git) *(10 min)* – ✅ [See Summary](#demo-code-repositories-git)  
- [ ] Skill Check: Workspace Design and Setup – ✅ [See Summary](#skill-check-workspace-design-and-setup)  

### 4. Machine Learning Lifecycle  

- [ ] ML Lifecycle: Overview *(15 min)* – ✅ [See Summary](#ml-lifecycle-overview)  
- [ ] Access Data *(10 min)* – ✅ [See Summary](#access-data)  
- [ ] Data Preprocessing *(13 min)* – ✅ [See Summary](#data-preprocessing)  
- [ ] Demo: Data Preprocessing *(4 min)* – ✅ [See Summary](#demo-data-preprocessing)  
- [ ] Data Visualization *(10 min)* – ✅ [See Summary](#data-visualization)  
- [ ] Model Training *(4 min)* – ✅ [See Summary](#model-training)  
- [ ] Expert Tips: Training a ML Model on OCI *(3 min)* – ✅ [See Summary](#expert-tips-training-a-ml-model-on-oci)  
- [ ] Oracle AutoML: Introduction *(11 min)* – ✅ [See Summary](#oracle-automl-introduction)  
- [ ] Demo: Oracle AutoML *(29 min)* – ✅ [See Summary](#demo-oracle-automl)  
- [ ] Hyperparameter Tuning: ADSTuner *(4 min)* – ✅ [See Summary](#hyperparameter-tuning-adstuner)  
- [ ] Model Evaluation *(9 min)* – ✅ [See Summary](#model-evaluation)  
- [ ] Expert Tips: ADS Evaluators *(3 min)* – ✅ [See Summary](#expert-tips-ads-evaluators)  
- [ ] Model Explanations: Global Explainer *(14 min)* – ✅ [See Summary](#model-explanations-global-explainer)  
- [ ] Model Explanations: Local Explainer *(8 min)* – ✅ [See Summary](#model-explanations-local-explainer)  
- [ ] Expert Tips: Explainers *(2 min)* – ✅ [See Summary](#expert-tips-explainers)  
- [ ] Model Catalog: Overview *(9 min)* – ✅ [See Summary](#model-catalog-overview)  
- [ ] Model Serialization *(7 min)* – ✅ [See Summary](#model-serialization)  
- [ ] Model Deployment *(11 min)* – ✅ [See Summary](#model-deployment)  
- [ ] Demo: Model Deployment *(6 min)* – ✅ [See Summary](#demo-model-deployment)  
- [ ] Expert Tips: Hugging Face *(2 min)* – ✅ [See Summary](#expert-tips-hugging-face)  
- [ ] Demo: Model Deployment using TensorFlow *(21 min)* – ✅ [See Summary](#demo-model-deployment-using-tensorflow)  
- [ ] LLM Training & LangChain Integration *(3 min)* – ✅ [See Summary](#llm-training--langchain-integration)  
- [ ] Demo: Deploy LangChain based RAG to OCI Data Science *(4 min)* – ✅ [See Summary](#demo-deploy-langchain-based-rag-to-oci-data-science)  
- [ ] Demo: OCI Data Science Operators *(10 min)* – ✅ [See Summary](#demo-oci-data-science-operators)  
- [ ] Demo: OCI AI Quick Actions *(4 min)* – ✅ [See Summary](#demo-oci-ai-quick-actions)  
- [ ] Skill Check: Machine Learning Lifecycle – ✅ [See Summary](#skill-check-machine-learning-lifecycle)  

### 5. MLOps Practices  

- [ ] MLOps Architecture *(6 min)* – ✅ [See Summary](#mlops-architecture)  
- [ ] Data Science Jobs *(11 min)* – ✅ [See Summary](#data-science-jobs)  
- [ ] Demo: Create Artifacts *(4 min)* – ✅ [See Summary](#demo-create-artifacts)  
- [ ] Demo: Create and Manage Jobs *(5 min)* – ✅ [See Summary](#demo-create-and-manage-jobs)  
- [ ] Demo: Start and Manage a Job Run *(7 min)* – ✅ [See Summary](#demo-start-and-manage-a-job-run)  
- [ ] Demo: Scaling *(4 min)* – ✅ [See Summary](#demo-scaling)  
- [ ] Jobs Monitoring and Logging *(6 min)* – ✅ [See Summary](#jobs-monitoring-and-logging)  
- [ ] Data Science Pipeline *(7 min)* – ✅ [See Summary](#data-science-pipeline)  
- [ ] Demo: Data Science Pipeline *(16 min)* – ✅ [See Summary](#demo-data-science-pipeline)  
- [ ] Model Deployment: Autoscaling *(8 min)* – ✅ [See Summary](#model-deployment-autoscaling)  
- [ ] Expert Tips: Pipelines *(2 min)* – ✅ [See Summary](#expert-tips-pipelines)  
- [ ] Skill Check: MLOps Practices – ✅ [See Summary](#skill-check-mlops-practices)  

### 6. Related OCI Services  

- [ ] Spark Applications, Data Flow, and Data Science *(11 min)* – ✅ [See Summary](#spark-applications-data-flow-and-data-science)  
- [ ] Oracle Open Data *(3 min)* – ✅ [See Summary](#oracle-open-data)  
- [ ] OCI Data Labeling *(6 min)* – ✅ [See Summary](#oci-data-labeling)  
- [ ] Skill Check: Related OCI Services – ✅ [See Summary](#skill-check-related-oci-services)  

---  

## 📂 Lesson Notes  

---  

### 2. Introduction and Configuration  

#### Data Science: Introduction  

---  

#### ADS SDK Overview  

---  

#### Tenancy Configuration Basics  

---  

#### Configure a Tenancy with OCI Resource Manager  

---  

#### Networking for Data Science  

---  

#### Authenticate to OCI APIs  

---  

#### Skill Check: Introduction and Configuration  

---  

### 3. Workspace Design and Setup  

#### Projects  

---  

#### Notebook Sessions  

---  

#### How to Work with JupyterLab  

---  

#### Conda Environments: Overview  

---  

#### Data Science Conda Environments  

---  

#### Manage Conda Environments  

---  

#### Demo: Manage Conda Environments  

---  

#### OCI Vault: Introduction  

---  

#### Using OCI Vault in OCI Data Science  

---  

#### Code Repositories (Git)  

---  

#### Demo: Code Repositories (Git)  

---  

#### Skill Check: Workspace Design and Setup  

---  

### 4. Machine Learning Lifecycle  

#### ML Lifecycle: Overview  

---  

#### Access Data  

---  

#### Data Preprocessing  

---  

#### Demo: Data Preprocessing  

---  

#### Data Visualization  

---  

#### Model Training  

---  

#### Expert Tips: Training a ML model on OCI  

---  

#### Oracle AutoML: Introduction  

---  

#### Demo: Oracle AutoML  

---  

#### Hyperparameter Tuning: ADSTuner  

---  

#### Model Evaluation  

---  

#### Expert Tips: ADS Evaluators  

---  

#### Model Explanations: Global Explainer  

---  

#### Model Explanations: Local Explainer  

---  

#### Expert Tips: Explainers  

---  

#### Model Catalog: Overview  

---  

#### Model Serialization  

---  

#### Model Deployment  

---  

#### Demo: Model Deployment  

---  

#### Expert Tips: Hugging Face  

---  

#### Demo: Model Deployment using TensorFlow  

---  

#### LLM Training & LangChain Integration  

---  

#### Demo: Deploy LangChain based RAG to OCI Data Science  

---  

#### Demo: OCI Data Science Operators  

---  

#### Demo: OCI AI Quick Actions  

---  

#### Skill Check: Machine Learning Lifecycle  

---  

### 5. MLOps Practices  

#### MLOps Architecture  

---  

#### Data Science Jobs  

---  

#### Demo: Create Artifacts  

---  

#### Demo: Create and Manage Jobs  

---  

#### Demo: Start and Manage a Job Run  

---  

#### Demo: Scaling  

---  

#### Jobs Monitoring and Logging  

---  

#### Data Science Pipeline  

---  

#### Demo: Data Science Pipeline  

---  

#### Model Deployment: Autoscaling  

---  

#### Expert Tips: Pipelines  

---  

#### Skill Check: MLOps Practices  

---  

### 6. Related OCI Services  

#### Spark Applications, Data Flow, and Data Science  

---  

#### Oracle Open Data  

---  

#### OCI Data Labeling  

---  

#### Skill Check: Related OCI Services  

---

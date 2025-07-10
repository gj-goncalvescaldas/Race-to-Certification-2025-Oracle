# 🤖 Oracle Cloud Infrastructure AI Foundations  
### Study Notes & Summaries  
_A comprehensive guide based on the official Oracle AI Foundations Course._  
> 📌 _This is a summary of Oracle University lessons. No personal analysis or opinion is included._
> ⚙️ **Note:**  
> As part of this course, I will implement the machine learning models separately using **Databricks Community Edition**, rather than using **Jupyter Notebooks** as shown in the course. All my practical model implementations will be stored under the `/ML_Models` folder.

---

## 🏅 Certification

**Oracle Cloud Infrastructure AI Foundations Associate**  
_(To be completed after passing the exam)_  
*Issued by Oracle University*

This certification validates foundational understanding of AI concepts, Machine Learning (ML), Deep Learning (DL), Generative AI, and Oracle’s AI services in OCI.

---

## 📘 Course Overview

- **Platform:** Oracle Learning
- **Goal:** Gain foundational knowledge in AI/ML/DL, understand Generative AI concepts, and explore Oracle’s AI capabilities and services in OCI.

---

## 🧭 Course Structure

### 1. Welcome to AI Foundations
- [x] Welcome to AI Foundations *(9 min)* – ✅ _No notes_

### 2. AI Foundations
- [x] Module Intro *(1 min)* – ✅ _No notes_
- [x] Introduction to AI *(5 min)* – ✅ [See Summary](#introduction-to-ai)
- [x] AI – Tasks and Data *(8 min)* – ✅ [See Summary](#ai--tasks-and-data)
- [x] Demo: AI *(11 min)* – ✅ [See Summary](#demo-ai)
- [x] AI vs ML vs DL *(8 min)* – ✅ [See Summary](#ai-vs-ml-vs-dl)
- [x] Skill Check: AI Basics – ✅ [See Summary](#skill-check-ai-basics)

### 3. Machine Learning Foundations
- [x] Module Intro *(1 min)* – ✅ _No notes_
- [x] Introduction to Machine Learning *(6 min)* – ✅ [See Summary](#introduction-to-machine-learning)
- [x] Supervised Learning – Classification *(5 min)* – ✅ [See Summary](#supervised-learning--classification)
- [x] Supervised Learning – Regression *(7 min)* – ✅ [See Summary](#supervised-learning--regression)
- [x] Demo: Introduction to Jupyter Notebooks *(6 min)* – ✅ _No notes_
- [x] Demo: Basic Machine Learning Part – 1 *(7 min)* – ✅ [See Summary](#demo-basic-machine-learning-part--1)
- [x] Demo: Basic Machine Learning Part – 2 *(10 min)* – ✅ [See Summary](#demo-basic-machine-learning-part--2)
- [x] Unsupervised Learning *(7 min)* – ✅ [See Summary](#unsupervised-learning)
- [x] Reinforcement Learning *(8 min)* – ✅ [See Summary](#reinforcement-learning)
- [x] Skill Check: ML Basics – ✅ [See Summary](#skill-check-ml-basics)

### 4. Deep Learning Foundations
- [x] Module Intro *(1 min)* – ✅ _No notes_
- [x] Introduction to Deep Learning *(10 min)* – ✅ [See Summary](#introduction-to-deep-learning)
- [x] Deep Learning Models – Sequence Models *(6 min)* – ✅ [See Summary](#deep-learning-models--sequence-models)
- [x] Deep Learning Models – CNN *(10 min)* – ✅ [See Summary](#deep-learning-models--cnn)
- [x] Demo: Classification with Multilayer Perceptron *(8 min)* – ✅ [See Summary](#demo-classification-with-multilayer-perceptron)
- [x] Skill Check: DL Basics – ✅ [See Summary](#skill-check-dl-basics)

### 5. Generative AI and LLM Foundations
- [ ] Module Intro *(1 min)* – ✅ _No notes_
- [ ] Introduction to Generative AI *(9 min)* – ✅ [See Summary](#introduction-to-generative-ai)
- [ ] Introduction to Large Language Models *(8 min)* – ✅ [See Summary](#introduction-to-large-language-models)
- [ ] Transformers Part-1 *(8 min)* – ✅ [See Summary](#transformers-part-1)
- [ ] Transformers Part-2 *(9 min)* – ✅ [See Summary](#transformers-part-2)
- [ ] Prompt Engineering *(11 min)* – ✅ [See Summary](#prompt-engineering)
- [ ] Customize LLMs with your data *(10 min)* – ✅ [See Summary](#customize-llms-with-your-data)
- [ ] Skill Check: Gen AI Basics – ❌ Not Attempted

### 6. OCI AI Portfolio
- [ ] Module Intro *(1 min)* – ✅ _No notes_
- [ ] AI Services Overview *(8 min)* – ✅ [See Summary](#ai-services-overview)
- [ ] ML Services Overview *(7 min)* – ✅ [See Summary](#ml-services-overview)
- [ ] AI Infrastructure *(6 min)* – ✅ [See Summary](#ai-infrastructure)
- [ ] GPUs and Superclusters in OCI *(13 min)* – ✅ [See Summary](#gpus-and-superclusters-in-oci)
- [ ] Responsible AI *(7 min)* – ✅ [See Summary](#responsible-ai)
- [ ] Demo: Data Science *(10 min)* – ✅ [See Summary](#demo-data-science)
- [ ] Skill Check: OCI AI Portfolio – ❌ Not Attempted

### 7. OCI Generative AI Service
- [ ] Module Intro *(1 min)* – ✅ _No notes_
- [ ] OCI Generative AI *(8 min)* – ✅ [See Summary](#oci-generative-ai)
- [ ] Demo: OCI Generative AI *(13 min)* – ✅ [See Summary](#demo-oci-generative-ai)
- [ ] Vector Search *(9 min)* – ✅ [See Summary](#vector-search)
- [ ] Select AI *(8 min)* – ✅ [See Summary](#select-ai)
- [ ] Skill Check: OCI Gen AI Service – ❌ Not Attempted

### 8. OCI AI Services
- [ ] Language Intro *(2 min)* – ✅ _No notes_
- [ ] Demo: Language *(4 min)* – ✅ [See Summary](#demo-language)
- [ ] Speech Intro *(3 min)* – ✅ [See Summary](#speech-intro)
- [ ] Demo: Speech *(3 min)* – ✅ [See Summary](#demo-speech)
- [ ] Vision Intro *(2 min)* – ✅ [See Summary](#vision-intro)
- [ ] Demo: Vision *(5 min)* – ✅ [See Summary](#demo-vision)
- [ ] Document Understanding *(2 min)* – ✅ [See Summary](#document-understanding)
- [ ] Demo: Document Understanding *(3 min)* – ✅ [See Summary](#demo-document-understanding)
- [ ] Skill Check: OCI AI Services – ❌ Not Attempted

---

## 📂 Lesson Notes

---

### 🧩 AI Foundations

#### Introduction to AI  
---

> 📝 **Summary:**  
> This lesson introduces the concept of Artificial Intelligence (AI) as the ability of machines to mimic human cognitive and problem-solving abilities. It explains the distinction between **Artificial General Intelligence (AGI)** and task-specific AI, and discusses the increasing importance of AI in today’s data-driven world.

#### 🧠 What Is AI?

- **Artificial Intelligence (AI)**  
  → Machines that imitate aspects of human intelligence to solve specific tasks.

- **Artificial General Intelligence (AGI)**  
  → Machines that replicate the full range of human cognitive abilities, including reasoning, sensory processing, planning, creativity, and emotional intelligence.

- **AI in Practice**  
  - Classifying objects (e.g., Apple vs Orange)  
  - Filtering spam emails  
  - Writing code  
  - Predicting prices  
  - Generating text, music, or art

#### 📈 Why Do We Need AI?

1. **Volume of Data**  
   → Humans can't process the massive data generated daily. AI helps **interpret**, **analyze**, and **act** faster and more accurately.

2. **Routine Task Automation**  
   → AI reduces human burden by handling repetitive tasks like:
   - Credit approvals  
   - Claims processing  
   - Product recommendations

3. **Human-AI Collaboration**  
   → AI can augment creativity and productivity by helping with:
   - Writing stories or poems  
   - Designing graphics  
   - Generating music or software

#### 🧩 AI Domains & Use Cases

- **Language** → Translation, summarization  
- **Vision** → Image classification, object detection  
- **Speech** → Text-to-speech, speech recognition  
- **Recommendation Systems** → Product suggestions, personalization  
- **Anomaly Detection** → Fraud detection, alerting  
- **Reinforcement Learning** → Self-driving cars, robotics  
- **Forecasting** → Weather prediction, sales trends  
- **Generative AI** → Creating images or text from prompts

#### 🔑 Final Takeaway

AI is not just a futuristic concept—it’s **already embedded** in many applications and industries. It helps eliminate repetitive work, enhances human creativity, and provides powerful ways to interact with the world using data and intelligent systems.

#### AI – Tasks and Data  
---

> 📝 **Summary:**  
> This lesson explores the key domains of AI—**Language**, **Speech/Audio**, and **Vision**—and the kinds of tasks and data associated with each. It also touches on common architectures used to build models, the structure of input data, and examples of AI applications such as anomaly detection, recommendation systems, and forecasting.

#### 🧠 Language AI Tasks

- **Text-related Tasks** (Input = Text)  
  → Examples:  
  - Language detection  
  - Entity/key phrase extraction  
  - Translation (e.g., multilingual input/output using source-target language pairs)

- **Generative Language Tasks**  
  → Examples:  
  - Text generation (stories, summaries, Q&A)  
  - Chatbots like **ChatGPT** trained on **Large Language Models (LLMs)**

- **Text as Data**  
  - Sequential structure (sentences → words → tokens)  
  - **Tokenization**: converting words to numbers  
  - **Padding**: equalizing sentence length for processing  
  - **Embeddings**: vector representations capturing similarity  
  - **Similarity Measures**: cosine similarity, dot product

- **Model Architectures**  
  - **RNN (Recurrent Neural Networks)**  
  - **LSTM (Long Short-Term Memory)**  
  - **Transformers**: parallelized, self-attention for context awareness

#### 🎙️ Speech/Audio AI Tasks

- **Audio-related Tasks**  
  → Examples:  
  - Speech-to-text  
  - Speaker recognition  
  - Voice conversion

- **Generative Audio Tasks**  
  → Examples:  
  - Music composition  
  - Speech synthesis

- **Audio as Data**  
  - Digitized as time-based snapshots (sampling rate)  
  - Typical rate: **44.1 kHz** (CD quality)  
  - **Bit depth** defines richness of each sample  
  - Requires **correlation of multiple samples** for meaningful interpretation

- **Model Architectures**  
  - RNN, LSTM, **Transformers**  
  - **Variational Autoencoders**, **Waveform Models**, **Siamese Networks**  
  - Designed to process **sequential, time-series audio input**

#### 👁️ Vision AI Tasks

- **Image-related Tasks**  
  → Examples:  
  - Image classification  
  - Object detection  
  - Facial recognition (used in surveillance, biometrics, social media)

- **Generative Vision Tasks**  
  → Examples:  
  - Text-to-image generation  
  - High-resolution or stylistic image synthesis  
  - 3D object/model generation

- **Images as Data**  
  - Comprised of pixels (grayscale or color)  
  - One pixel ≠ meaning; pattern detection requires multiple  
  - Task type determines input/output structure

- **Model Architectures**  
  - **Convolutional Neural Networks (CNNs)**: detect hierarchical patterns  
  - **YOLO (You Only Look Once)**: real-time object detection  
  - **GANs (Generative Adversarial Networks)**: generate realistic images/videos

#### 🔍 Other Key AI Tasks

- **Anomaly Detection**  
  - Uses **time-series data** (single/multivariate)  
  - Applications: fraud detection, machine failure

- **Recommendation Systems**  
  - Input: data on similar users/products  
  - Output: personalized suggestions

- **Forecasting**  
  - Based on time-series input  
  - Use cases: weather prediction, stock market trends

#### 🔑 Final Takeaway

AI spans a **diverse set of tasks and data types** across multiple domains.  
From text and speech to images and forecasts, each domain requires **specific data structures** and **dedicated model architectures**.  
Understanding the nature of each task helps in choosing the right tools, data processing techniques, and models to generate accurate, context-aware results.

#### Demo: AI  
---

> 📝 **Summary:**  
> This demo introduces several pre-built services in **OCI Vision** and **OCI Language**. The instructor walks through live examples of image classification, object detection, text detection, and document understanding using Vision AI. They also showcase sentiment analysis, entity extraction, and machine translation using the Language AI service.

**🔍 Vision AI Capabilities:**
- **Image Classification**  
  Uploading images (e.g., nature, zebras) returns multiple labeled elements (e.g., “vegetation”, “animal”) with confidence scores.
  
- **Object Detection**  
  Images with traffic scenes or fruit baskets are analyzed using bounding boxes, detecting objects like taxis, people, oranges, bananas, etc.
  
- **Text Detection**  
  Bus images and fonts are used to extract visible text, license plates, and styled fonts line by line.
  
- **Document AI (Document Understanding)**  
  A receipt is uploaded and analyzed:
  - Extracted **raw text**, **key-value pairs** (e.g., transaction date, subtotal, total), and **tables** (e.g., itemized list, totals, payment details).
  - Three tables were successfully identified within the document.

**🔤 Language AI Capabilities:**
- **Text Analysis**  
  A text block is analyzed for:
  - **Language detection**  
  - **Text classification**  
  - **Entity extraction** (tagged by type)  
  - **Key phrase extraction**  
  - **Aspect-based & sentence-level sentiment detection**  
  - **PII detection** (e.g., historical dates)

- **Text Translation**  
  The same text is translated into French and Japanese using built-in translation capabilities.

**📦 Additional Note:**
- Users can also **train custom models** with their own data directly in the platform.
  
![Image 1](img/1.png)  
![Image 2](img/2.png)  
![Image 3](img/3.png)  
![Image 4](img/4.png)


#### AI vs ML vs DL  
---

> 📝 **Summary:**  
> This lesson clarifies the relationship and distinctions between **Artificial Intelligence (AI)**, **Machine Learning (ML)**, and **Deep Learning (DL)**. It introduces the different learning types (supervised, unsupervised, reinforcement), discusses real-world use cases, and explains how models learn from data to make decisions and generate insights.

#### 🧠 Definitions and Examples

- **Artificial Intelligence (AI)**  
  → Broad concept of machines performing tasks that typically require human intelligence.  
  **Example:** Self-driving car making real-time traffic decisions.

- **Machine Learning (ML)**  
  → A subset of AI that uses data and algorithms to learn and make decisions.  
  **Example:** Spam filter learning from email content and user behavior.  
  - Involves rules, equations, and procedures = **algorithms**

- **Deep Learning (DL)**  
  → A subfield of ML using **deep neural networks** to detect complex patterns.  
  **Example:** Recognizing cats in photos online.

#### 🔍 Types of Machine Learning

1. **Supervised Learning**  
   - Learns from **labeled data** (input + correct output).  
   - **Example:** Credit card approval using historical decision data.  
   - Uses algorithms to incrementally improve predictions.  
   - Outputs can be used to **classify or predict** outcomes.

2. **Unsupervised Learning**  
   - Works with **unlabeled data** to discover patterns.  
   - **Example:**  
     - **Retail**: Cluster customers by income, location, etc.  
     - **Streaming Services**: Group behavior by viewing habits.  
     - **Nutrition**: Cluster fruits/veggies by their nutritional profiles.  
   - Aims to **group similar items** without explicit instructions.

3. **Reinforcement Learning**  
   - Learns through **trial and error**, receiving **rewards/punishments**.  
   - **Example:** Learning to play chess, drive a car, or train a robot.  
   - Useful when **interaction with an environment** is essential.

#### 🧠 Deep Learning & Neural Networks

- DL involves **feature extraction** and **rule learning** directly from data.
- Ideal for tasks like **image recognition** where rules aren’t easily defined.
- Uses **multiple layers of artificial neurons** to learn hierarchical features.
- Neural networks act like **stacked brain cells**—good for function approximation.
- DL is often implemented via **supervised learning**.

#### 🎨 Generative AI (A Subset of ML)

- Focuses on creating new content: **text, images, audio, and more**.
- Trained on existing datasets to **generate original output**.
- **Example:** ChatGPT generates human-like responses by learning from text.
- Plays a key role in **content generation and creative AI tasks**.

![Image 5](img/5.png)  

#### 🔑 Final Takeaway

AI is the umbrella term, ML is a method within AI, and DL is a specialized technique within ML.  
Each builds on the other to handle increasingly complex problems—ranging from **automation** to **creativity**.  
Understanding the differences is key to choosing the right tools, architectures, and approaches for specific AI tasks.


#### Skill Check: AI Basics  
---

#### **1. Which is NOT an example of vision or image-related AI task?**  
- ✅ **Correct Answer:** Repair damaged images  
- 🧠 **Explanation:**  
  While image repair does involve images, it's not a typical vision AI task like classification or object detection. Vision AI is primarily focused on identifying, classifying, or understanding visual content, not restoration.

#### **2. Which type of Machine Learning is used in autonomous car driving?**  
- ✅ **Correct Answer:** Reinforcement Learning  
- 🧠 **Explanation:**  
  Reinforcement Learning enables an agent (e.g., the self-driving car) to learn from interacting with an environment by receiving rewards or penalties for its actions. This allows it to make decisions like safe navigation and route planning.

#### **3. Which type of Machine Learning algorithms extracts trends from data?**  
- ✅ **Correct Answer:** Unsupervised Machine Learning  
- 🧠 **Explanation:**  
  Unsupervised learning finds hidden patterns in unlabeled data. It’s ideal for clustering, association, and dimensionality reduction, helping discover trends without predefined outcomes.

#### **4. Which task is a Generative AI task?**  
- ✅ **Correct Answer:** Writing a poem based on a given theme  
- 🧠 **Explanation:**  
  Generative AI is used to produce new content (text, image, audio, etc.). Writing a poem from a prompt fits this category as it involves creative generation of new material, not analysis or classification.

#### **5. Which task is an example of a speech-related AI task?**  
- ✅ **Correct Answer:** Speech-to-text Conversion  
- 🧠 **Explanation:**  
  This involves converting spoken audio into written text using models like Automatic Speech Recognition (ASR). It's a core task in the speech/audio domain of AI.

### 🧩 Machine Learning Foundations

#### Introduction to Machine Learning  
---

> 📝 **Summary:**  
> This lesson introduces **Machine Learning (ML)** as a core subset of Artificial Intelligence that allows machines to learn from data without being explicitly programmed. It explains how ML models are trained using input features and labels, then used to make predictions. The class covers types of ML (supervised, unsupervised, reinforcement) and gives real-world examples across industries like healthcare, e-commerce, finance, and autonomous systems.

#### 🤖 What is Machine Learning?

- **Subset of AI**  
  → Focuses on creating systems that learn from examples (data) to make predictions or decisions without explicit programming.

- **Driven by Algorithms**  
  → ML uses algorithms to detect patterns and learn relationships from historical data, forming the basis for prediction and automation.

#### 🔍 How Does It Work?

1. **Training Phase**
   - Input data: features (e.g., color, texture, eye shape of animals)
   - Label: expected output (e.g., "cat" or "dog")
   - Model learns the **relationship** between features and labels during training.

2. **Inference Phase**
   - New input data is fed into the trained model.
   - The model predicts the label/output (e.g., identifies a cat or dog).

#### 🧪 Types of Machine Learning

1. **Supervised Learning**
   - Uses **labeled data**.
   - Learns mappings between input features and correct outputs.
   - 📌 **Examples**:  
     - Disease detection  
     - Spam classification  
     - Credit scoring  
     - Weather & stock prediction

2. **Unsupervised Learning**
   - Uses **unlabeled data**.
   - Detects patterns or clusters in data without known outcomes.
   - 📌 **Examples**:  
     - Customer segmentation  
     - Fraud detection  
     - Outlier detection  
     - Targeted marketing

3. **Reinforcement Learning**
   - **Learns through feedback** (rewards/punishments).
   - Ideal for tasks where actions affect outcomes over time.
   - 📌 **Examples**:  
     - Autonomous cars  
     - Robotics  
     - Game-playing agents

#### 🌍 Everyday Applications of ML

- **E-commerce**: Product recommendations based on user behavior  
- **Entertainment**: Movie suggestions on Netflix  
- **Email**: Spam detection  
- **Self-driving cars**: Navigate using trained ML algorithms  

#### 🔑 Final Takeaway

Machine Learning makes it possible for systems to **learn from data**, **improve over time**, and make intelligent predictions or decisions. Whether it’s filtering spam, recommending a product, or driving a car, ML powers many of the intelligent systems we rely on every day.

#### Supervised Learning – Classification  
---

> 📝 **Summary:**  
> This lesson explores **classification**, a supervised learning technique used to predict **categorical outcomes**. Unlike regression (which predicts continuous values), classification assigns input data into discrete **classes or labels**, such as "spam" vs "not spam" or sentiment categories. The lesson also introduces **logistic regression**, a widely used algorithm that utilizes a **sigmoid function** to output probabilities for binary or multi-class classification problems.

#### 🎯 What is Classification?

- **Definition:**  
  Classification is a supervised machine learning method that maps **input features** to **discrete class labels** using a trained model.

- **Output Type:**  
  - **Categorical**, not continuous  
  - Examples:
    - **Binary Classification:** Spam vs Not Spam  
    - **Multi-Class Classification:** Sentiment analysis (positive, negative, neutral)

#### 🛠️ How It Works

- **Training with Labeled Data:**  
  - The model is trained using a dataset that includes both features (e.g., hours studied) and known outcomes (e.g., pass/fail).
  - After training, the model can classify new, unseen data based on learned patterns.

#### 📊 Logistic Regression for Classification

- **Key Concept:**  
  Logistic regression is used to predict **binary outcomes** (e.g., pass/fail) and can be extended to **multi-class problems**.

- **Model Mechanics:**
  - Input: One or more numeric features (e.g., hours of study).
  - Output: Probability between **0 and 1** using the **sigmoid function**.
  - Prediction rule:
    - If probability > 0.5 → **Class A** (e.g., "pass")
    - If probability < 0.5 → **Class B** (e.g., "fail")

- **Sigmoid Function:**  
  \[
  \sigma(x) = \frac{1}{1 + e^{-x}}
  \]  
  Maps any real value to [0, 1] for interpreting outputs as probabilities.

#### 🌼 Iris Dataset Example (Preview to Demo)

- **Dataset:**  
  Iris flowers with 150 labeled examples across 3 species:  
  - Iris Setosa  
  - Iris Versicolor  
  - Iris Virginica  

- **Features:**  
  - Sepal Length  
  - Sepal Width  
  - Petal Length  
  - Petal Width  

- **Problem Type:**  
  → **Multi-class classification** using logistic regression.

#### 🔑 Final Takeaway

Classification is an essential part of supervised machine learning, helping models **categorize data into classes** based on learned relationships. It powers many common applications from email filtering to flower recognition, using models like **logistic regression** that turn raw data into actionable decisions.

#### Supervised Learning – Regression  
---

> 📝 **Summary:**  
> This lesson introduces **regression**, a supervised learning technique used to predict **continuous outcomes**. It emphasizes the importance of learning the **mapping between inputs and outputs** using labeled data. Linear regression is explored as a method for fitting a best line to model relationships (e.g., house price vs. size), enabling predictions through a mathematical function.

#### 📐 What is Regression?

- **Definition:**  
  Regression is a supervised machine learning method used to predict **continuous numeric values** based on input features.

- **Example Applications:**
  - **House Price Prediction:** Inputs → square footage → Output → price
  - **Cancer Detection:** Inputs → medical data → Output → tumor type
  - **Sentiment Analysis:** Inputs → review text → Output → sentiment label
  - **Stock Prediction:** Inputs → financial indicators → Output → price

#### 🔄 Supervised Learning Process

- **Training:**  
  The model is trained on a dataset of **input-output pairs** (e.g., house size → price).
  
- **Goal:**  
  Learn a **mapping function** that minimizes prediction error on new data.

#### 📉 Linear Regression Explained

- **Use Case:**  
  Predicting house prices using house size (in sq. ft.).

- **Model Equation:**  
  \[
  f(x) = w \cdot x + b
  \]  
  - **x** = input (e.g., size)  
  - **w** = slope (rate of price increase)  
  - **b** = bias/intercept (price offset)

- **Model Training:**
  - Input and output data are visualized as a **scatter plot**.
  - A **line of best fit** is found using **slope and bias** adjustments.
  - The model aims to **minimize loss**, defined as the difference between predicted and actual prices.

#### ❗ Key Concepts

- **Error:** Difference between predicted and true values.
- **Loss Function:** Often the **squared error**:
  \[
  \text{Loss} = (y_{\text{pred}} - y_{\text{actual}})^2
  \]
- **Optimization:** Algorithm iteratively adjusts **w** and **b** to minimize loss.

#### 🔁 Inference & Prediction

- Once trained, the model can:
  - Accept **new input** (e.g., 1,100 sq. ft.)
  - Use the learned function to **predict** a price.

#### 🔑 Final Takeaway

Regression is used when the prediction target is **numeric**. Linear regression builds a straight-line model that maps inputs to outputs using learned weights and biases. It's a foundational technique in supervised learning, crucial for tasks like **forecasting, pricing, and risk modeling**.

#### Demo: Basic Machine Learning Part – 1  
---  

> 📝 **Summary:**  
> This demo introduces a basic machine learning workflow using **Logistic Regression** with the **Iris dataset**. The example demonstrates how to load data, preprocess it, train a model, and make predictions — forming the foundation of any classification-based ML workflow.

#### ⚙️ Steps in the Demo

1. **Import Libraries**  
   - `pandas` for data handling  
   - `LogisticRegression` from `sklearn.linear_model` for building the classifier

2. **Load Dataset**  
   - Read `iris.csv` using `pd.read_csv()`  
   - Inspect structure using `.head()`

3. **Prepare Data**  
   - Split dataset into:  
     - **X** → Features (excluding `ID` and `Species`)  
     - **Y** → Labels (`Species` column)  
   - Drop irrelevant columns like `ID`

4. **Initialize the Model**  
   - Create model with `LogisticRegression()`  
   - Default hyperparameters used

5. **Train the Model**  
   - Call `.fit(X, Y)` to train using features and corresponding labels

6. **Make Predictions**  
   - Provide new unseen input data  
   - Predict the species of Iris using `.predict()`  
   - Output shown was: `Iris-setosa`

#### 💡 Final Output
- The model successfully predicts the species of a flower based on unseen input features.
- A solid example of applying logistic regression to a multi-class classification problem.


#### Demo: Basic Machine Learning Part – 2  
---

> 📝 **Summary:**  
> This extended demo builds upon the previous session by introducing a more complete machine learning workflow. It covers **data standardization**, **train/test splitting**, **model evaluation**, and **making predictions on new data** using **Logistic Regression** with the Iris dataset.

#### ⚙️ Steps in the Demo

1. **Setup and Cleanup**
   - Duplicate previous notebook and start fresh
   - Restart kernel and clear outputs

2. **Import Libraries**
   - `numpy` for numerical operations
   - `train_test_split` to split data into training/testing sets
   - `StandardScaler` to normalize feature data
   - `accuracy_score` to evaluate model performance

3. **Why Standardization?**
   - Ensures all features are on the same scale
   - Prevents bias from features with large numeric ranges (e.g., square footage vs number of rooms)

4. **Train/Test Split**
   - Splits dataset into:
     - `X_train`, `X_test`: features
     - `y_train`, `y_test`: labels
   - Uses `random_state=42` for reproducibility

5. **Standardize Features**
   - Scales training and testing features using `StandardScaler`

6. **Train the Model**
   - Initialize `LogisticRegression`
   - Fit model using scaled training data

7. **Evaluate the Model**
   - Make predictions using scaled test data
   - Calculate accuracy using `accuracy_score`
   - Achieved **100% accuracy** on test data

8. **Predict on New Data**
   - Create sample data points with new flower attributes
   - Standardize new input data
   - Use trained model to predict species
   - Output included `Iris-setosa` and `Iris-virginica` predictions

#### ✅ Outcome
- Successfully trained and validated a logistic regression model with high accuracy
- Demonstrated a complete end-to-end ML pipeline: from preprocessing to prediction



#### Unsupervised Learning  
---

> 📝 **Summary:**  
> This lesson introduces **Unsupervised Learning**, a machine learning approach where models discover patterns in **unlabeled data**. It focuses on identifying natural structures like **clusters** and **outliers**, often using **similarity measures**. Applications include **market segmentation**, **fraud detection**, and **recommendation systems**. Unlike supervised learning, there is no target output — the algorithm explores the data to group similar instances.

#### 🔍 What is Unsupervised Learning?

- **Definition:**  
  A learning method where the algorithm detects **patterns, structures, and similarities** in data **without labeled outputs**.

- **Analogy Examples:**
  - Sorting LEGO pieces by color or shape without instructions.
  - Grouping fruits by similarities in color or size (e.g., apples and cherries together).

#### 🧩 Clustering: Core Technique

- **Clustering** groups similar items based on shared features.
- **Outliers** are data points that don’t fit well into any cluster.
  - Example: Grapes are shaped and sized differently from apples or strawberries.

#### 📦 Common Applications

1. **Market Segmentation**
   - Cluster customers based on **purchase behavior** or **demographics**.
   - Example: Target ads for protein supplements to health-focused customers.

2. **Outlier Analysis**
   - Identify **anomalous transactions** in financial data (e.g., fraud detection).
   - Large or recurring payments could signal suspicious activity.

3. **Recommendation Systems**
   - Group users by **viewing or listening history**.
   - Example: Netflix or Spotify recommends content based on cluster profiles.

#### 📏 Understanding Similarity

- **Similarity Score:**  
  Ranges from 0 to 1, indicating how alike two data points are.
  - Closer to **1** → more similar.
  - Example: Apple and cherry (both red) may have similarity ≈ 1.

- **Common Similarity Metrics:**
  - **Euclidean Distance**
  - **Manhattan Distance**
  - **Cosine Similarity**
  - **Jaccard Similarity**

#### 🔁 Unsupervised Learning Workflow

1. **Prepare the Data**  
   - Handle missing values  
   - Normalize & scale features  

2. **Create Similarity Matrix**  
   - Choose based on data type and algorithm used  

3. **Run Clustering Algorithm**  
   - Techniques:  
     - Partition-based  
     - Hierarchical  
     - Density-based  
     - Distribution-based  

4. **Interpret Results**  
   - Since there's **no ground truth**, interpret cluster quality by:
     - Comparing to business expectations
     - Reviewing cluster characteristics
     - Iteratively refining steps

#### 🔑 Final Takeaway

Unsupervised learning helps **reveal hidden patterns** in data without needing labels. It’s essential for tasks where we lack predefined outcomes, such as segmentation, anomaly detection, and personalization. The process is highly exploratory and iterative.

#### Reinforcement Learning  
---

> 📝 **Summary:**  
> This lesson introduces **Reinforcement Learning (RL)** — a machine learning approach where an agent learns by interacting with an **environment** and receiving **rewards or penalties**. The agent's goal is to discover an **optimal policy** that maximizes rewards over time. RL is widely used in areas like robotics, gaming, self-driving cars, and personal assistants.

#### 🐶 Real-World Analogy

- **Like teaching a dog tricks:**  
  → Reward good behavior, punish wrong actions.  
  → Over time, the dog learns the best behaviors — this is similar to how machines learn in RL.

#### 🧠 Key Concepts

| Term          | Definition |
|---------------|------------|
| **Agent**     | The learner or decision-maker (e.g., a robot, car, or software). |
| **Environment** | The external system the agent interacts with (e.g., road, warehouse). |
| **State**     | A snapshot of the environment at a given time. |
| **Action**    | A decision or move made by the agent in a state (e.g., turn left/right). |
| **Policy**    | The strategy that maps states to actions. |
| **Reward**    | Feedback given for actions taken (positive = good, negative = bad). |
| **Optimal Policy** | A strategy that maximizes long-term rewards. |

#### 🚗 Common Use Cases

- **Autonomous Vehicles:**  
  Real-time decisions based on sensor data and road conditions.
  
- **Smart Assistants (Alexa, Siri):**  
  Personalization and adaptation to speech and user behavior.

- **Industrial Automation:**  
  Optimize robotic arms and manufacturing lines for performance.

- **Gaming & VR:**  
  AI characters that adapt and evolve with player behavior.

#### 🏗️ RL in Action – Self-Driving Car Example

1. **Agent:** Self-driving car system  
2. **Environment:** Roads, traffic, and surroundings  
3. **State:** Camera input (road view)  
4. **Actions:** Steer left, right, or go straight  
5. **Policy:** Learns best actions over time  
6. **Reward:** Safety, correct navigation = reward; crashing = penalty

#### 🤖 RL in Action – Robotic Arm Example

- **Objective:** Pick and place goods in a warehouse efficiently

1. **Environment Setup:** Robotic arm, warehouse layout, goods  
2. **States:** Positions of arm, items, and targets  
3. **Actions:** Move arm, pick up, place items  
4. **Rewards:**  
   - ✅ Correct placement = positive reward  
   - ❌ Dropping items = penalty

5. **Training Process:**
   - Starts with random actions
   - Learns from rewards/penalties
   - Improves strategy through **exploration + experience**

#### 🔄 Learning Algorithms

- **Q-Learning**
- **Deep Q-Networks (DQN)**

These algorithms guide the learning of the **optimal policy** through repeated interaction and reward-based feedback.

#### 🔑 Final Takeaway

Reinforcement Learning is ideal for scenarios where agents must **learn by doing**, making it a powerful tool for **real-time decision-making**, **control systems**, and **adaptive AI**. It mimics trial-and-error learning and leads to intelligent behavior without needing labeled data.


#### Skill Check: ML Basics  
---

### 1. Which algorithm is used for predicting continuous numerical values?

- ✅ **Correct Answer:** Linear Regression  
- 🧠 **Explanation:** Linear Regression is a regression algorithm used for predicting continuous numerical values by modeling the relationship between dependent and independent variables using a straight line.

### 2. Which application does NOT require a Machine Learning solution?

- ✅ **Correct Answer:** Password Validation  
- 🧠 **Explanation:** Password validation is a straightforward process that involves checking whether a user-entered password matches the stored password. This can be achieved through standard cryptographic techniques and rules without the need for machine learning.

### 3. What type of Machine Learning algorithm is used when we want to predict the resale price on a residential property?

- ✅ **Correct Answer:** Regression  
- 🧠 **Explanation:** Regression is the type of Machine Learning algorithm used when we want to predict continuous numerical values, such as the resale price of a residential property.

### 4. Which type of function is used in Logistic Regression to predict a loan defaulter?

- ✅ **Correct Answer:** Sigmoidal function  
- 🧠 **Explanation:** Logistic Regression uses the sigmoidal (logistic) function, which is an S-shaped curve that maps any input value to an output value between 0 and 1, ideal for binary classification.

### 5. Which type of Machine Learning algorithm learns from outcomes to make decisions?

- ✅ **Correct Answer:** Reinforcement Learning  
- 🧠 **Explanation:** Reinforcement Learning enables an agent to learn optimal actions based on feedback (rewards or penalties) received from interacting with an environment.
  
---

### 🧩 Deep Learning Foundations

#### Introduction to Deep Learning  
---

> 📝 **Summary:**  
> This lesson introduces **Deep Learning (DL)** as a specialized area within Machine Learning (ML) that uses **Artificial Neural Networks (ANNs)** to process raw data (e.g., pixels) and extract internal feature representations automatically. DL enables scalability and performance for complex tasks, including image classification, text translation, and generative applications.

#### 🧠 What Is Deep Learning?

- **Deep Learning (DL)** is a subset of ML that focuses on training **Artificial Neural Networks (ANNs)** to solve tasks such as image classification.
- ANNs can **process raw data** like image pixels and **extract patterns** (features) automatically to predict outcomes.
- In contrast to ML, DL does **not require manual feature engineering**—it builds internal representations of the data through training.

#### ⚡ Scalability & Performance

- DL can utilize **parallel computations**, splitting data into batches for faster learning.
- This enables processing of **large datasets efficiently**, making DL ideal for tasks where manual feature extraction is infeasible.

#### 📜 History of Deep Learning

- **1950s** – Artificial neurons, perceptron, and MLP introduced  
- **1980s** – Backpropagation algorithm for training ANNs  
- **1990s** – Convolutional Neural Networks (CNNs) developed  
- **2000s** – Rise of GPU use  
- **2010s** – Mainstream adoption (e.g., AlexNet, Deep Q-Network)  
- **2016+** – Generative use cases, large language models (LLMs)

#### 🧩 DL Applications by Data Type

- **Images**: Image classification, object detection, segmentation  
- **Text**: Translation, sentiment detection, summarization  
- **Audio**: Music generation, speech-to-text  
- **Video**: Object tracking, event detection  
- **Generative AI**: Text-to-image, LLMs, GANs

#### 🧱 Choosing the Right Architecture

| Data Type | Task                        | DL Architecture              |
|-----------|-----------------------------|------------------------------|
| Image     | Classification, Detection   | CNN                          |
| Text      | Translation, QA, Summarization | Transformers, LSTM, RNN  |
| Audio     | Speech-to-Text, Music       | RNN, LSTM, Transformers      |
| Generative| Text-to-Image, Content Gen  | GANs, Diffusion, Transformers|

![Image 6](img/6.png)  

#### 🧬 Anatomy of an ANN (Artificial Neural Network)

- **Neurons**: Computational units that process inputs and produce outputs
- **Weights**: Define connection strength between neurons
- **Activation Functions**: Convert weighted inputs into outputs (e.g., ReLU)
- **Bias**: Adds flexibility to neuron activation
- **Layers**:
  - **Input Layer**: Receives raw data (e.g., pixels)
  - **Hidden Layers**: Extract features and learn internal representations
  - **Output Layer**: Produces the final prediction

#### 🧪 Example: Digit Recognition

- **Input**: 28x28 pixel images of digits (0–9)
- **Architecture**:
  - Input Layer: 784 neurons (28×28 pixels)
  - Hidden Layers: 2 layers with 16 neurons each
  - Output Layer: 10 neurons (digits 0–9)
- **Training**:
  1. Input image shown to ANN (e.g., digit "2")
  2. Incorrect prediction triggers **backpropagation**
  3. ANN adjusts weights to reduce prediction error
  4. Repeats across thousands of images for accuracy

#### 🔁 Backpropagation

- Key algorithm for **training ANNs**
- Adjusts weights based on error between predicted and expected outputs
- Enables **learning from labeled data** to improve performance over time

#### 🔑 Final Takeaway

Deep Learning empowers machines to **automatically learn complex features** from raw data, scale across massive datasets, and solve advanced AI tasks. Its architecture and training mechanisms are modeled on the brain and optimized for performance through methods like backpropagation and parallel computing.

#### Deep Learning Models – Sequence Models  
---

> 📝 **Summary:**  
> This lesson covers deep learning architectures designed for **sequential data** such as text, audio, or time series. It explains the workings of **Recurrent Neural Networks (RNNs)** and **Long Short-Term Memory (LSTM)** networks, focusing on how they handle sequence patterns, dependencies, and long-term memory.

#### 🧠 What Are Sequence Models?

- Designed to process **ordered sequences** of data points or events.
- Used for **pattern recognition**, **classification**, **prediction**, and **sequence generation**.
- Applications include:
  - Natural Language Processing (NLP): machine translation, sentiment analysis, text generation
  - Speech recognition: audio to text
  - Music generation: creating original compositions
  - Sign language recognition: interpreting gesture sequences
  - Time series forecasting: finance, weather prediction

#### 🔄 Recurrent Neural Networks (RNNs)

- Neural networks with **feedback loops** allowing information to persist across time steps.
- Maintain an internal **hidden state (memory)** updated as each sequence element is processed.
- Enables capturing dependencies **spread across time** in sequential data.

##### RNN Architecture Types

| Type       | Description                          | Example Use Case                   |
|------------|------------------------------------|----------------------------------|
| One-to-One | Traditional feedforward network    | Not suited for sequences         |
| One-to-Many| Single input, multiple outputs     | Music or sequence generation     |
| Many-to-One| Multiple inputs, single output     | Sentiment analysis from reviews  |
| Many-to-Many| Multiple inputs, multiple outputs | Machine translation, entity recognition |

- **Limitation:** Difficulty capturing **long-term dependencies** due to the **vanishing gradients problem**.

#### 🔑 Long Short-Term Memory (LSTM)

- Designed to overcome RNN limitations for **long-term dependencies**.
- Uses **memory cells** and **gating mechanisms** to selectively remember or forget information over time.
- Maintains relevant information across long sequences, improving performance on sequential tasks.

##### LSTM Components and Operation

- **Inputs per time step**:  
  - Current input vector  
  - Previous hidden state  
  - Previous cell state

- **Gates controlling information flow**:  
  - **Input Gate:** Decides which new information to add to memory  
  - **Forget Gate:** Determines which memory information to discard  
  - **Output Gate:** Regulates output from the memory cell for current time step

- **Process**:  
  1. Gates filter and update the cell state.  
  2. The updated cell state produces the current hidden state (output).  
  3. Hidden state passed to the next time step.

#### 🔑 Final Takeaway

Sequence models like RNNs and LSTMs enable deep learning to handle **ordered, time-dependent data** by maintaining context across inputs. LSTMs, with their gating mechanisms, address long-term dependencies and are widely used in NLP, speech, music, and time series applications.

#### Deep Learning Models – CNN  
---

> 📝 **Summary:**  
> This lesson explores **Convolutional Neural Networks (CNNs)**, a class of deep learning models specialized in processing **grid-like data** such as images and videos. The structure, working, and applications of CNNs are explained through an intuitive analogy with a house inspection robot.

#### 🧠 Overview of Deep Learning Model Architectures

- **Feedforward Neural Networks (FNN / MLP):** Simplest neural networks; not ideal for image or sequence data.
- **Convolutional Neural Networks (CNN):** Designed to extract spatial patterns from image and video data.
- **Recurrent Neural Networks (RNN):** Handle sequential data with feedback loops for temporal context.
- **Autoencoders:** Unsupervised models for **dimensionality reduction** and **feature extraction**.
- **Long Short-Term Memory (LSTM):** Specialized RNNs for **long-term dependency** handling.
- **Generative Adversarial Networks (GANs):** Generate **synthetic data** like images, text, and audio.
- **Transformers:** State-of-the-art in **natural language processing** and **language understanding**.

#### 🧩 What Is a Convolutional Neural Network?

- CNNs process **two-dimensional data** (e.g., images) more effectively than traditional ANN.
- Unlike ANNs that flatten images into 1D arrays, CNNs preserve **spatial structure**.
- CNNs extract hierarchical features such as **edges, textures, shapes**, etc.

#### 🏗 CNN Architecture

1. **Input Layer** – Accepts image data.
2. **Feature Extraction Layers:**
   - **Convolutional Layer (with ReLU)**
   - **Pooling Layer**
3. **Classification Layers:**
   - Fully Connected Layer  
   - Softmax Output Layer  
   - Optional Dropout Layer (for regularization)

#### 🛠 Robot Analogy for CNN Layers

| Robot Tool            | CNN Component           | Functionality Description                                 |
|------------------------|-------------------------|------------------------------------------------------------|
| Blueprint Detector     | Convolutional Layer      | Detects local patterns (edges, textures)                   |
| Pattern Highlighter    | Activation Function (ReLU)| Introduces non-linearity for learning complex features     |
| Summarizer             | Pooling Layer            | Reduces spatial size while preserving important info       |
| House Expert           | Fully Connected Layer    | Classifies based on learned features                       |
| Guess Maker            | Softmax Layer            | Outputs probabilities for each class                       |
| Quality Checker        | Dropout Layer            | Prevents overfitting by ignoring random neurons during training |


#### 🧪 How Feature Extraction Works

- **Convolutional Layer:** Applies filters (kernels) across image pixels to detect local patterns.
- **Activation Function (ReLU):** Adds non-linearity to the model.
- **Pooling:** Downsamples feature maps to reduce computation and overfitting.

#### ⚠️ Limitations of CNNs

- **High computation cost** on large datasets.
- Prone to **overfitting** with small/imbalanced datasets.
- Considered **black-box models**—hard to interpret.
- Sensitive to small input perturbations.

#### 🧾 Applications of CNNs

- **Image Classification** – E.g., distinguishing cats vs. dogs
- **Object Detection** – Identifying and localizing objects
- **Image Segmentation** – Pixel-level classification of regions
- **Face Recognition** – Identifying individuals from facial features
- **Medical Imaging** – Tumor detection, diagnosis
- **Self-Driving Cars** – Understanding traffic scenes and signs
- **Satellite Image Analysis** – Land cover classification, environmental monitoring

#### 🔑 Final Takeaway

Convolutional Neural Networks are the backbone of modern **computer vision** tasks. Their ability to automatically extract **hierarchical spatial features** from images makes them effective for complex tasks like classification, detection, and segmentation across various industries.

#### Demo: Classification with Multilayer Perceptron  
---

> 📝 **Summary:**  
> This lesson demonstrates how to use a Multilayer Perceptron (MLP) to classify a dataset with concentric circles. We explore how changing the number of neurons in the hidden layer affects classification accuracy and decision boundary complexity.

#### 1. Dataset Creation
- Use `make_circles` from the Sklearn library.
- Generate 300 samples: 150 points per class (outer circle = 0, inner circle = 1).
- Add noise and adjust factor to modify point distribution.
- Parameters:
  - `n_samples` (e.g., 300)
  - `noise` (e.g., 0.1)
  - `factor` (distance between circles, e.g., 0.5)
  - `random_state` for reproducibility

#### 2. Initial Data Visualization
- Plot data points colored by label.
- Observe concentric circle pattern.
- Explore impact of changing `noise` and `factor`.

#### 3. MLP Classifier Setup
- Use an MLP classifier with one hidden layer.
- Number of neurons in the hidden layer is adjustable (1 to 6 neurons).
- Use ReLU activation function for non-linear decision boundaries.
- Use a fixed random seed for initialization.
- Train the classifier on the dataset.

#### 4. Interactive Model Training and Visualization
- Slider widget to select number of neurons.
- On slider update:
  - Train MLP with chosen hidden layer size.
  - Generate a grid covering the data range.
  - Predict labels for grid points.
  - Plot decision boundaries using contour plots.
  - Overlay training data points.
  - Update plot title and axis labels.

#### 5. Observations
- With 1 neuron: poor classification, decision boundary too simple.
- Increasing neurons: decision boundary becomes more complex.
- More points are classified correctly with more neurons.
- Visual intuition about model complexity and performance.

#### 6. Conclusion
- MLP can separate non-linearly separable data with enough neurons.
- Interactive demo helps understand the role of hidden neurons.
- Thanks for watching!

#### 🔑 Final Takeaway
The number of neurons in the hidden layer directly impacts the complexity of the decision boundary and classification accuracy. Increasing neurons allows the MLP to learn more complex patterns, improving its ability to separate non-linear data.


#### Skill Check: DL Basics  
---

### 1. How do hidden layers in neural networks help with character recognition?

- ✅ **Correct Answer:** Enabling the network to learn complex features like edges and shapes  
- 🧠 **Explanation:** Hidden layers in neural networks are crucial for character recognition because they enable the network to learn and extract complex features and patterns, such as edges, shapes, and curves, which are essential for recognizing characters.

### 2. Which Neural Network has a feedback loop and is designed to handle sequential data?

- ✅ **Correct Answer:** Recurrent Neural Networks  
- 🧠 **Explanation:** Recurrent Neural Networks (RNNs) are a type of neural network architecture that includes feedback connections. These feedback connections allow RNNs to process sequential data, such as time series, natural language, speech, and more.

### 3. Which essential component of Artificial Neural Network performs weighted summation and applies activation function on input data to produce an output?

- ✅ **Correct Answer:** Neuron  
- 🧠 **Explanation:** A neuron in an Artificial Neural Network is the fundamental building block responsible for performing weighted summation and applying an activation function to input data to produce an output.

### 4. Which type of Recurrent Neural Network (RNN) architecture is used for Machine Translation?

- ✅ **Correct Answer:** Many-to-Many  
- 🧠 **Explanation:** Machine Translation involves translating a sentence or sequence of text from one language to another, which is essentially a sequence-to-sequence problem. Many-to-Many RNN architecture takes a sequence of inputs and produces a sequence of outputs, suitable for this task.

### 5. Which sequence model can maintain relevant information over long sequences?

- ✅ **Correct Answer:** Long Short-Term Memory Neural Networks  
- 🧠 **Explanation:** Long Short-Term Memory (LSTM) networks are a specialized type of recurrent neural network designed to address the vanishing gradient problem and maintain relevant information over long sequences via gating mechanisms controlling the flow of information.

---

### 🧩 Generative AI and LLM Foundations

#### Introduction to Generative AI  
---  
#### Introduction to Large Language Models  
---  
#### Transformers Part-1  
---  
#### Transformers Part-2  
---  
#### Prompt Engineering  
---  
#### Customize LLMs with your data  
---  
#### Skill Check: Gen AI Basics  
---  

---

### 🧩 OCI AI Portfolio

#### OCI AI Portfolio Module Intro  
---  
#### AI Services Overview  
---  
#### ML Services Overview  
---  
#### AI Infrastructure  
---  
#### GPUs and Superclusters in OCI  
---  
#### Responsible AI  
---  
#### Demo: Data Science  
---  
#### Skill Check: OCI AI Portfolio  
---  

---

### 🧩 OCI Generative AI Service

#### OCI Generative AI Service Module Intro  
---  
#### OCI Generative AI  
---  
#### Demo: OCI Generative AI  
---  
#### Vector Search  
---  
#### Select AI  
---  
#### Skill Check: OCI Gen AI Service  
---  

---

### 🧩 OCI AI Services

#### Language Intro  
---  
#### Demo: Language  
---  
#### Speech Intro  
---  
#### Demo: Speech  
---  
#### Vision Intro  
---  
#### Demo: Vision  
---  
#### Document Understanding  
---  
#### Demo: Document Understanding  
---  
#### Skill Check: OCI AI Services  
---  

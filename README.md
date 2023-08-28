# DDoS Detection using Machine Learning

Denial of Service (DDoS) attacks poses a significant threat to network security. These attacks often originate from virtual machines in the cloud, rather than the attacker's own machine, to maintain anonymity and utilize higher network bandwidth.

Past research has primarily focused on analyzing traffic at the destination (victim's) side with predefined thresholds. However, these approaches come with notable disadvantages:
- They are solely passive defenses post-attack and cannot utilize outbound statistical attack features.
- Tracing back to the attacker is challenging using these methods.

Numerous DDoS detection techniques exist, but they often fall short in effectively mitigating these attacks. Thus, in this project, we implemented eight distinct Machine Learning (ML) techniques to detect DDoS attacks from the source side within a cloud infrastructure.

## Project Details

- **Data Source**: We trained our models using the NSDL Dataset and implemented eight different ML models for DDoS detection.
- **Data Split**: We partitioned our gathered data into training and testing samples.
- **Tool Usage**: Jupyter Notebook was the primary tool for training and testing our machine learning models.
- **Evaluation**: We assessed both supervised and unsupervised learning algorithms, including:
  - Linear Regression (LR)
  - Support Vector Machine (SVM) with linear, RBF (Radial Basis Function), and polynomial kernels
  - Decision Tree
  - Naive Bayes
  - Random Forest
  - Unsupervised learning algorithm: k-means

## Evaluation Metrics

- **Accuracy**: This metric represents the fraction of correctly classified samples and is a common way to evaluate a model's performance.
  
  `Accuracy = (TP + TN) / (TP + TN + FP + FN)`

- **Recall**: Also known as sensitivity, recall measures the true positive rate (TPR), indicating the proportion of actual positive values correctly identified.
  
  `Recall = TP / (TP + FN)`

- **Precision**: Precision, or positive predictive value, measures the consistency of repeated measurements under unchanged conditions.
  
  `Precision = TP / (TP + FP)`

- **F1 Score**: The F1 score, a harmonic average of recall and precision, is valuable when recall and precision conflict.
  
  `F1 Score = 2 * (Recall * Precision) / (Recall + Precision)`

- **Confusion Matrix**: The confusion matrix compares predicted and actual values, providing insight into algorithm performance.

  ![Confusion Matrix](https://user-images.githubusercontent.com/69844239/127862308-636eabe8-5a0f-4509-985f-7c3216e968ab.png)

## Flow Chart
![Flow Chart](https://user-images.githubusercontent.com/69844239/127862059-404a8c1e-65fd-42f6-a1b8-a31d9fd4b665.png)

## DDoS Report by Imperva
![Imperva DDoS Report](https://user-images.githubusercontent.com/69844239/127859906-4638bbf5-dd5a-4521-a0f0-e2ab06f30478.png)

## Most Common Types of DDoS Attacks
![Common DDoS Attacks](https://user-images.githubusercontent.com/69844239/127860077-fc633342-8ddf-44ad-86d7-4bb1f7cd12db.png)

## Proposed Model
![Proposed Model](https://user-images.githubusercontent.com/69844239/127863514-797e5442-91a5-4797-bd46-287f79eb3858.jpg)

## Detection Results
![Detection Results](https://user-images.githubusercontent.com/69844239/127863218-a5eb5ea6-d60b-43b6-ad2e-03152aab411c.jpg)

Feel free to ask if you need more information or have any questions regarding this project.

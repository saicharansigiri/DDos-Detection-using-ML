# DDos-Detection-using-ML
* Denial of service (DOS) attacks are a serious threat to network security. These attacks are often sourced from virtual machines in the cloud, rather than from the attacker’s own machine, to achieve anonymity and higher network bandwidth.
* Past research focused on analyzing traffic on the destination (victim’s) side with predefined thresholds. These approaches have significant disadvantages.
* They are only passive defenses after the attack, they cannot use the outbound statistical features of attacks, and it is hard to trace back to the attacker with these approaches.
* There are many different DDos detection Techniques,But they are Not effective to mitigate these attacks.
  So, In this Project we Implemented the 8 different types of  ML(Machine Learning Techniques) to detect DDos attacks From Source Side in Cloud Infrastructure. 

* DDos detection using ML Techniques we have Trained our models using NSDL -Dataset & implemented 8 differenet ML Models To Detect DDos.
* We split our gathered data into training samples and testing samples.
* We used Jupyter Notebook for Training and Testing of our machine Learning Models.
* We evaluate both supervised learning and unsupervised learning algorithms. 
* For supervised classification,we evaluated the Following.
   - Linear Regression (LR),
   - SVM (with linear, RBF(Radial Basis Function) and polynomial kernels),Decision Tree,
   - Naive Bayes and Random Forest algorithms.
   - We also tested unsupervised learning algorithm i.e k-means.
### Flow Chart :
![image](https://user-images.githubusercontent.com/69844239/127862059-404a8c1e-65fd-42f6-a1b8-a31d9fd4b665.png)

### DDOS Report by imperva : 
![image](https://user-images.githubusercontent.com/69844239/127859906-4638bbf5-dd5a-4521-a0f0-e2ab06f30478.png)
### Most Common Types of DDosAttacks : 
![image](https://user-images.githubusercontent.com/69844239/127860077-fc633342-8ddf-44ad-86d7-4bb1f7cd12db.png)
### Proposed Model : 
![model](https://user-images.githubusercontent.com/69844239/127863514-797e5442-91a5-4797-bd46-287f79eb3858.jpg)
### **Implementation And Evaluation** :
* **Accuracy** : Accuracy is the fraction of correctly classified samples. This is the most commonly used metric to evaluate a model. The higher this value is, indicates the model is better.
                                    
                                    Accuracy = (TP+TN)/(TP+TN+FP+FN) 
* **Recall** : Recall, also known as sensitivity, it is the true positive rate (TPR). This measures the proportion of actual positive values that are correctly identified. Higher recall means fewer false negative values. 

                                    Recall = TP/ (TP+FN)



 
* **Precision** : Precision (positive predictive value) represents the degree to which repeated measurements under unchanged conditions show the same results.
                                    
                                    Precision = TP / (TP+FP)

* **F1 Score** : F1 score, also known as balanced F-score or F-measure, is the harmonic average of recall and precision, considering they have equal weight. This is a good metric when recall and precision cause conflict and hard to decide which one is better.

                F1 score = 2*recall*precision / (recall + precision)
* **Confusion Matrix** : Nearly all the classification metrics are based on the confusion matrix, also known as the error matrix. It is a table that compares the predicted values and actual values (standard values), it reflects the performance of an algorithm. Figure 2 is the format of a confusion matrix. Columns are the predicted values counts and rows are the actual values counts
                        
 ![image](https://user-images.githubusercontent.com/69844239/127862308-636eabe8-5a0f-4509-985f-7c3216e968ab.png)



 
    



### Detection Results :
![detection results](https://user-images.githubusercontent.com/69844239/127863218-a5eb5ea6-d60b-43b6-ad2e-03152aab411c.jpg)






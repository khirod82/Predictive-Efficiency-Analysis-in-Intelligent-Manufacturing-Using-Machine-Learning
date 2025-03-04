**"Predictive Efficiency Analysis in Intelligent Manufacturing Using Machine Learning"**

### **Explanation:**  
This project applies machine learning techniques to analyze and predict efficiency in an intelligent manufacturing system. Using a dataset with operational parameters like **temperature, vibration, power consumption, network latency, and packet loss**, an **SVM (Support Vector Machine) classifier** is trained to classify efficiency levels as **High, Medium, or Low**.

The dataset is preprocessed by:  
- **Encoding categorical variables** (Operation_Mode)  
- **Scaling numerical features** using **StandardScaler**  
- **Splitting data into training and testing sets**  
- **Training an SVM classifier** with a linear kernel  

The model achieves an **accuracy of 91.68%**, with high precision, recall, and F1-score for classifying efficiency levels.

### **Inference:**  
1. **Temperature, vibration, and network latency significantly impact efficiency.**  
2. **SVM performs well in classifying efficiency, suggesting a clear separation between different operational states.**  
3. **Medium-efficiency cases are harder to classify (75% recall), possibly indicating overlapping features between High and Low categories.**  
4. **With further optimization (hyperparameter tuning, feature engineering, or ensemble learning), the model's performance could improve further.**  
5. **This analysis can help manufacturers optimize machine efficiency, reduce downtime, and improve production quality in an Industry 4.0 environment.**  

# Money Laundering Detection Using Big Data and Machine Learning

## Overview
This project focuses on detecting suspicious financial transactions that may indicate money laundering activities. It uses Big Data technologies such as Apache Spark along with Machine Learning models to analyze large-scale transaction data and classify transactions as normal or suspicious.

## Objectives
- Analyze large-scale financial transaction data  
- Identify suspicious transaction patterns  
- Perform feature engineering for better prediction  
- Build Machine Learning models for classification  
- Handle imbalanced datasets  
- Develop a scalable fraud detection system  

## Technologies Used
- Python  
- Apache Spark (PySpark)  
- Scikit-learn  
- Pandas  
- NumPy  
- Matplotlib  

## Project Structure
├── data/  
├── notebooks/  
├── src/  
├── models/  
├── results/  
├── README.md  

## Methodology
1. Data Collection  
Public or synthetic financial transaction datasets are used.

2. Data Preprocessing  
Handling missing values, removing duplicates, and transforming data.

3. Feature Engineering  
Extracting features such as transaction frequency, average amount, and time intervals.

4. Big Data Processing  
Apache Spark is used for distributed data processing.

5. Model Training  
Logistic Regression, Decision Tree, and Random Forest models are trained.

6. Evaluation  
Performance is evaluated using Accuracy, Precision, Recall, and F1-score.

## Results
- Transactions are classified as normal or suspicious  
- Improved fraud detection accuracy  
- Efficient handling of large datasets using Spark  

## Challenges
- Imbalanced dataset with very few fraud cases  
- Feature selection complexity  
- Processing large-scale data efficiently  

## Future Enhancements
- Real-time fraud detection using streaming data  
- Integration with banking systems  
- Use of deep learning models  
- Graph-based fraud detection techniques  

## References
- Research papers on Anti-Money Laundering (AML)  
- Apache Spark Documentation  
- Scikit-learn Documentation  

## How to Run
1. Install dependencies:  
pip install pyspark pandas numpy scikit-learn matplotlib  

2. Start Spark session:  
from pyspark.sql import SparkSession  
spark = SparkSession.builder.appName("AML Project").getOrCreate()  

3. Run the project:  
python main.py  

## Contributors
- Your Name  
- Team Member 2  
- Team Member 3  

## Conclusion
This project demonstrates how combining Big Data and Machine Learning can effectively detect money laundering activities. It provides a scalable and efficient approach for financial fraud detection.

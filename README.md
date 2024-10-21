# BankApps-Sentiment-Analysis
The banking industry is experiencing a dramatic shift towards digital services, with mobile banking apps becoming the primary touchpoint between financial institutions and their customers.
# Result 
## Distribusi Sentiment 
![image](https://github.com/user-attachments/assets/6eec93d2-f64a-4876-b521-b20631076ae5)
![image](https://github.com/user-attachments/assets/dc41c183-b74d-4876-8c08-79a3e9a220e7)
![image](https://github.com/user-attachments/assets/027363c8-c841-4bc9-bc86-11545fd6868b)

## Metrics Results
# Classification Results Analysis

| Application | Classifier  | Accuracy | Recall | Precision | F1 Score | Performance Overview |
|------------|-------------|----------|---------|-----------|----------|---------------------|
| BCA | Random Forest | 76.23% | 76.23% | 78.08% | 70.88% | Best performer for BCA, showing strong overall balance between accuracy and precision |
| BCA | XGBoost | 74.78% | 74.78% | 70.30% | 71.59% | Close second, with particularly strong F1 score indicating good balance |
| BCA | Naive Bayes | 74.49% | 74.49% | 66.49% | 69.82% | Decent performance with balanced metrics |
| BCA | SVM | 66.09% | 66.09% | 65.72% | 65.88% | Lowest performer but consistent across metrics |
| BNI | Random Forest | 73.96% | 73.96% | 78.77% | 66.87% | Top performer for BNI with notably high precision |
| BNI | Naive Bayes | 72.78% | 72.78% | 64.98% | 65.34% | Second best accuracy with balanced performance |
| BNI | XGBoost | 71.30% | 71.30% | 62.82% | 65.47% | Solid middle-ground performer |
| BNI | SVM | 61.83% | 61.83% | 58.52% | 60.09% | Struggles across all metrics for BNI |
| BRI | Random Forest | 82.17% | 82.17% | 84.96% | 79.96% | **Star performer** across all applications with highest scores |
| BRI | Naive Bayes | 81.53% | 81.53% | 84.30% | 79.32% | Impressively close to RF performance |
| BRI | XGBoost | 80.57% | 80.57% | 80.49% | 79.06% | Very strong consistent performance |
| BRI | SVM | 76.75% | 76.75% | 77.72% | 77.15% | Solid performance with well-balanced metrics |

## Key Observations:
1. BRI models consistently outperform other applications across all classifiers
2. Random Forest emerges as the most reliable classifier across all applications
3. SVM generally shows the lowest performance but with more consistent metrics
4. BNI shows the most room for improvement among the three applications

## Accurcay by Classifier
![image](https://github.com/user-attachments/assets/a704c986-c864-4f6f-a473-d64c1d67c0c6)
## Best Performing Classifiers

| Application | Classifier | Accuracy |
|------------|------------|----------|
| BCA | Random Forest | 76.23% |
| BNI | Random Forest | 73.96% |
| BRI | Random Forest | 82.17% |

**Note:** Random Forest (RF) consistently emerges as the top-performing classifier across all banking applications, with BRI showing the highest accuracy at 82.17%.

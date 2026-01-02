# AI-Art-DSA210-Project
AI Art Trends: Analysis of Popularity and Style Evolution Data Science Project Report

# **Introduction (Motivation)**
The rise of AI-generated art has reshaped creative production, democratizing access while raising debates about originality and artistic value. Despite the artistic discussions, there is limited quantitative analysis of how the public engages with different AI-generated styles or tools.
By investigating measurable data such as likes and views, this project aims to bridge artistic intuition with data-driven insight, helping understand the cultural reception of AI creativity.

# **Data Sources and Collection Methods**
- Public datasets from Kaggle
( https://www.kaggle.com/datasets/waqi786/ai-generated-art-trends
https://www.kaggle.com/datasets/atharvasoundankar/ai-generated-art-popularity-and-market-trends )

# **Exploratory Data Analysis (EDA)**
- **Data Cleaning:** Handled missing values and ensured data quality.
- **Descriptive Statistics:** Calculated summary statistics for popularity metrics such as Popularity_Score, Likes, and Engagement_Score.
- **Correlation Analysis:** Numerical correlations were explored through a heatmap after applying one-hot encoding to categorical variables.
- **Category Comparison:** Boxplots and bar charts were used to compare popularity across categorical variables such as art style, creator type, tool, and region.

### **Hypotheses**
- **H1:** Popularity has significantly increased after 2022.
- **H2:** Certain tools correlate with higher average engagement.
- **H3:** Human-edited (Hybrid) artworks perform better than fully AI-generated ones.
- **H4:** Art style significantly affects popularity.

# **Machine Learning Applications**
### **1. Regression Models**
**Models used:**
- Ridge Regression (linear baseline)
- Random Forest Regressor (non-linear ensemble)
**Evaluation metrics:**
- Root Mean Squared Error (RMSE), R² score

### **2. Classification Models**
**Models used:**
- Logistic Regression
- Random Forest Classifier
**Evaluation metrics:**
- Accuracy, ROC-AUC, Confusion Matrix, Precision, Recall, F1-score

# **Findings and Insights**
Across all stages—EDA, hypothesis testing, regression, and classification—the results consistently point to the same conclusion:
AI-generated artwork popularity cannot be reliably explained or predicted using metadata alone.
Key insights:
- Neither linear nor non-linear models capture meaningful predictive signals.
- Popularity appears to be driven by latent factors not present in the dataset, such as:
  visual and aesthetic qualities of the artwork, platform recommendation algorithms, viral diffusion and social exposure, external reputation effects etc.

Machine learning played a crucial role in validating the limits of predictability, rather than merely optimizing performance.

# **Limitations and Future Work**
### **Limitations**
- The analysis relies exclusively on metadata and excludes image content, leaving aesthetic factors unexplored.
- Engagement metrics like likes, views can be affected by external factors such as platform-specific dynamics, algorithmic exposure and social factors like artists reputation.

### **Future Work**
Future extensions of this project could:
- incorporate image-based features using convolutional neural networks (CNNs),
- apply multimodal models combining visual and metadata inputs,
- include platform-level exposure data (e.g., impressions, follower counts),
- explore causal inference methods to disentangle popularity drivers.

# **Conclusion**
This project demonstrates that null or negative predictive results can be meaningful and informative in data science. By systematically applying statistical analysis and machine learning techniques, we show that metadata alone is insufficient to explain engagement patterns in AI-generated art.
Rather than indicating failure, these findings highlight the complexity of cultural and creative domains and emphasize the importance of feature selection and data scope when applying machine learning to real-world problems.

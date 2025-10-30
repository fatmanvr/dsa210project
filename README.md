# AI-Art-DSA210-Project
AI Art Trends: Analysis of Popularity and Style Evolution Data Science Project Report

# **Introduction (Motivation)**
The rise of AI-generated art has reshaped creative production, democratizing access while raising debates about originality and artistic value. Despite the artistic discussions, there is limited quantitative analysis of how the public engages with different AI-generated styles or tools.
By investigating measurable data such as likes and views, this project aims to bridge artistic intuition with data-driven insight, helping understand the cultural reception of AI creativity.

# **Data Sources and Collection Methods**
- Public datasets from Kaggle
- Scraped metadata from art-sharing platforms (DeviantArt, ArtStation, or HuggingFace Spaces).

# **Exploratory Data Analysis (EDA)**
- **Data Cleaning:** handle missing values, encode categorical variables (One-Hot Encoding).
- **Descriptive Statistics:** summarize distributions of likes, views, and comments.
- **Correlation Analysis:** check relationships between numerical features.
- **Trend Analysis:** time series or grouped bar plots for year vs. tool/style popularity.
- **Category Comparison:** violin plots or boxplots of likes/views by tool or style.

### **Hypotheses**
- **H1:** The popularity of AI-generated artworks has increased significantly since 2022.
- **H2:** Certain tools (e.g., Midjourney) and specific styles (e.g., realism, fantasy) correlate with higher average engagement.
- **H3:** Human-edited AI artworks tend to perform better than fully automated outputs.
- **H4:** Classification models can predict “popular” artworks with >80% accuracy using categorical + numerical features.

# **Machine Learning Applications**
- **Classification:** Predict whether an artwork is “popular” (binary target).
  - Models: Logistic Regression, Decision Tree, Random Forest
- **Regression:** Predict numerical engagement level (likes or views).
  - Models: Linear Regression, Random Forest Regressor
- **Feature Importance:** Identify which factors most strongly influence popularity.
- **Visualization:** Trend lines, correlation heatmaps, feature importance charts.

# **Findings and Insights**
After conducting the analysis, key insights will be summarized.

# **Limitations and Future Work**
## **Limitations**
- **External Factors:** Engagement metrics like likes or views can be affected by external factors such as platform visibility or artist reputation.
- **Aesthetic Factors:** The analysis focuses on metadata rather than visual content, leaving aesthetic factors unexplored.

## **Future Work**
- Future work could include larger, multi-platform datasets and integrate image-based features such as color or composition.
- More advanced models, including ensemble or deep learning approaches, could further enhance predictive accuracy and uncover deeper cultural patterns in AI-driven art trends.

# **Conclusion**
This project will provide a data-driven understanding of how AI-generated art trends evolve and what factors contribute to public engagement. By combining aesthetic intuition with quantitative analysis, the study aims to illustrate the cultural shift in creativity brought by artificial intelligence. Beyond artistic curiosity, this research highlights how machine learning can interpret human taste and digital creativity patterns in an era where algorithms shape both creation and reception.

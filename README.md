# Credit-Card-User-Clustering-with-R
This repository contains a study on clustering credit card users to understand spending and behavior patterns for targeted marketing strategies. Various clustering models, especially Model-Based Clustering, were analyzed to identify distinct consumer segments based on credit card usage.

## Abstract
This study focuses on clustering credit card users to understand spending and behavior patterns for targeted marketing strategies. Various clustering models were analyzed to identify distinct consumer segments based on credit card usage. Key findings include different preferences like cash-in-advance, installment purchases, and full repayment behaviors, effectively segmented using advanced clustering algorithms (Mainly using Model-Based Clustering). The practical application of this research allows credit card companies to tailor offers to meet specific consumer needs, potentially increasing profitability. Future work might include integrating real-time data to refine these clustering techniques and exploring the impact of economic changes on consumer behavior. This research enhances understanding of consumer financial behavior in a detailed and actionable manner, providing significant value to marketers in the highly competitive credit card industry.

## Introduction
This project aims to analyze credit card user data to uncover distinct spending and behavior patterns. By using various clustering algorithms, we aim to segment users into meaningful groups that can be targeted more effectively by marketing strategies.

### Background of Study with Research Objective
Consumer spending patterns are critical in business decision-making. With the increasing use of credit cards over cash, it's vital for companies to understand these patterns to tailor their services. The primary objective is to identify key consumer segments based on their credit card usage.

## Literature Review
Our review covers various consumer preferences and behaviors in credit card usage.

### Cash-in-Advance Preference
Consumers who prioritize cash transactions to control financial exposure.

### Installment Purchases Preference
Consumers who prefer installment payments to manage cash flow and finance larger purchases.

### Revolvers with Expensive Purchases
Consumers who use credit cards for high-value purchases, viewing them as financial leverage tools.

### Full Repayment Preference
Consumers who consistently pay their credit card balances in full to avoid debt.

### Active Users with High Spending and Repayment
Financially active consumers who manage high spending and repayments, often seeking credit card benefits.

## Research Gap
Previous studies have not fully explored how specific spending behaviors influence long-term consumer actions. There is a need for comprehensive analysis using advanced clustering algorithms to predict these behaviors dynamically.

## Methodology
Our methodology involves several steps to prepare and analyze the data.

### Data Cleaning and Manipulation
Transforming variable names for readability and handling missing values to ensure a clean dataset.

### Feature Understanding with EDA, and Selection and Dimensionality Reduction using PCA
Conducting exploratory data analysis (EDA) and using Principal Component Analysis (PCA) to reduce data dimensions while retaining essential information.

### Cluster Tendency Assessment
Assessing the dataset's clustering tendency using the Hopkins statistic to ensure significant grouping characteristics.

### Clustering Models
We employed various clustering models to analyze the data.

#### CLARA Clustering Algorithm Model
Effective in managing large datasets using a sampling method to reduce computational demands.

#### Hierarchical K-Means Clustering Algorithm Model
Combines hierarchical clustering and K-means to improve clustering accuracy and stability.

#### Fuzzy Clustering Algorithm Model
Assigns membership probabilities to each point for all clusters, useful in complex market analysis scenarios.

#### Model-Based Clustering with EM Algorithm Model
Uses statistical models and the Expectation-Maximization (EM) algorithm to identify clusters with different densities and shapes.

#### Density-Based Spatial Clustering of Applications with Noise (DBSCAN) Algorithm Model
Identifies clusters based on the density of data points and is robust to noise.

## Data
The study used a Kaggle dataset of 9000 active credit card holders, reduced to 8636 entries after data cleaning, with 18 behavioral variables.

## Results
The analysis revealed distinct patterns in the dataset, with significant clustering tendencies.

### Hypothesis Testing Results
The clustering analysis supported various hypotheses about consumer behavior segments, such as cash-in-advance users, installment purchasers, and full repayment users.

## Discussion
### Analysis
The analysis confirmed that clustering techniques are effective in identifying diverse consumer behaviors.

### Model Effectiveness
Among the models used, Model-Based Clustering (VEV Model) provided the most detailed insights, identifying five distinct clusters.

### Challenges and Limitations
Handling missing data and capturing dynamic consumer behavior patterns were key challenges.

### Theoretical Implications
This study highlights the importance of advanced clustering algorithms in understanding consumer credit behaviors.

### Practical Applications
Credit card companies can use these insights to develop targeted marketing strategies, improving customer engagement and profitability.

## Future Work and Improvements
Future research could integrate real-time data analysis and explore the impact of economic shifts on consumer behavior to enhance the models' predictive accuracy.

## Reference
- Allegue, S., et al. (2020). "RFMC: A spending-category segmentation."
- Artzi, I. (2022). "Predictive Analytics Techniques: Theory and Applications in Finance."
- Bagnoli, C., et al. (2022). "Industry 4.0 and the Emergent Business Models."
- Balayn, A., et al. (2021). "Managing bias and unfairness in data for decision support."
- Bhasin, A. (2023). "Credit Card Dataset for Clustering."
- Bolaños-Martínez, D., et al. (2024). "Clustering pipeline for vehicle behavior in smart villages."
- Boshoff, E., et al. (2022). "Buy Now Pay Later: Multiple Accounts and the Credit System in Australia."
- Cachero-Martínez, S., et al. (2024). "Because I’m happy: exploring the happiness of shopping in social enterprises."
- Carrasco, R.A., et al. (2019). "A Fuzzy Linguistic RFM Model Applied to Campaign Management."
- Çetinkaya-Rundel, M., et al. (2021). "An educator’s perspective of the tidyverse."
- Chakraborty, S., et al. (2022). "Data Classification and Incremental Clustering Using Unsupervised Learning."
- Chen, F., et al. (2024). "Financial knowledge and responsible credit card behavior."
- Chen, J.M., et al. (2021). "Clustering commodity markets in space and time."
- Cherif, A., et al. (2023). "Credit card fraud detection in the era of disruptive technologies."
- Chodorow-Reich, G., et al. (2020). "Cash and the Economy: Evidence from India’s Demonetization."
- Ghosh, A. (2016). "Banking sector globalization and bank performance."
- Hanji, S., & Hanji, S. (2023). "Towards Performance Overview of Mini Batch K-Means and K-Means."
- Helmus, J.R., et al. (2020). "A data driven typology of electric vehicle user types and charging sessions."
- Hicham, N., & Karim, S. (2022). "Analysis of Unsupervised Machine Learning Techniques."
- Jackson, I. (2022). "AutoML Approach to Stock Keeping Units Segmentation."
- Jadwal, P.K., et al. (2022). "Analysis of clustering algorithms for credit risk evaluation."
- Kasem, M.S.E., et al. (2024). "Customer profiling, segmentation, and sales prediction."
- Kumar, S., & Nayak, J.K. (2024). "Understanding the intricacies of risky indebtedness."
- Lam, T. (2022). "The People’s Algorithms: Social Credits and the Rise of China’s Big (Br)other."
- Nanda, A.P., & Banerjee, R. (2021). "Consumer’s subjective financial well-being."
- Oziegbe Omoifo, D. (2020). "Improving Customer Value Co-creation."
- Pellandini-Simányi, L. (2023). "Algorithmic classifications in credit marketing."
- Pietrewicz, L. (2019). "Technology, Business Models and Competitive Advantage in the Age of Industry 4.0."
- Popoyan, L., et al. (2020). "Winter is possibly not coming: Mitigating financial instability."
- Qiu, Y., & Wang, J. (2024). "A Machine Learning Approach to Credit Card Customer Segmentation."
- Regmi, S.R., et al. (2022). "Customer Market Segmentation using Machine Learning Algorithm."
- Relja, R., et al. (2024). "Understanding the psychological determinants of buy-now-pay-later."
- Rishi, B., et al. (2024). "Examining the dynamics leading towards credit card usage attitude."
- Schomburgk, L., & Hoffmann, A. (2023). "How mindfulness reduces BNPL usage."
- Seldal, M.M.N., & Nyhus, E.K. (2022). "Financial Vulnerability, Financial Literacy, and the Use of Digital Payment Technologies."
- Shankar, S., et al. (2017). "No Classification without Representation."
- Shy, O. (2023). "Cash Is Alive: How Economists Explain Holding and Use of Cash."
- Tóth, J.F., et al. (2021). "Ethical sensitivity in consumers’ decision-making."
- Vamsee, C.S., et al. (2023). "Demographic and Psychographic Customer Segmentation for Ecommerce Applications."
- Yuping, Z., et al. (2020). "New Methods of Customer Segmentation and Individual Credit Evaluation."

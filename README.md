# Unsupervised Learning Project

## Project/Goals

The core objective of this project is to apply unsupervised learning techniques to a wholesale data dataset. The project consists of four main components, including exploratory data analysis and pre-processing, KMeans clustering, hierarchical clustering, and principal component analysis (PCA). Through these steps, we aim to gain insights and discover patterns within the dataset, ultimately providing valuable information for decision-making and business optimization.

## Process

#### Step 1: EDA - Exploratory Data Analysis & Pre-processing

Conduct an exploratory data analysis on the diabetes dataset. Choose the visualizations I want to use, and my analysis cover the following tasks mostly:

- Data Import
- Data Cleaning: Check the dataset for any missing or incorrect data and clean the dataset accordingly. Data Description: Generate summary statistics such as mean, median, and standard deviation for each column of the dataset. 
- Data Visualization: Create various visualizations such as histograms, box plots, scatter plots, and heatmaps to understand the relationships and trends between the different variables in the dataset.
- Outlier Detection
- Correlation Analysis: Calculate the correlation between different variables in the dataset to determine which variables are highly correlated.
- Data Transformation
- Feature Selection

#### Step 2: KMeans Clustering
The objective of my analysis was to group similar products together into clusters based on their attributes such as fresh, milk, grocery, frozen, detergents_paper, and delicatessen. To perform the k-means clustering analysis, I pre-processed the dataset, determined the optimal number of clusters, initialized the centroids, assigned data points to clusters, updated the centroids, and repeated the process until convergence. This allowed me to effectively identify distinct groups within the dataset and gain insights into product segmentation.

#### Step 3: Hierarchical Clustering 
The analysis involved iteratively merging or splitting clusters based on a similarity measure until a dendrogram was formed.
To perform the hierarchical clustering analysis, I pre-processed the dataset and determined the optimal number of clusters using techniques such as the dendrogram. This allowed me to effectively identify distinct clusters and understand the hierarchical relationships among the data points. By utilizing this approach, I gained valuable insights into the underlying structure of the wholesale dataset and the grouping of similar products based on their attributes.

#### Step 4: PCA
In this section, I performed principal component analysis (PCA) to draw conclusions about the underlying structure of the wholesale customer data. By applying PCA to the dataset, I aimed to identify the compound combinations of features that best describe customers, as PCA calculates the dimensions that maximize variance. Through this analysis, I gained insights into the most influential features and their contributions to customer segmentation, enabling a deeper understanding of the underlying patterns and characteristics within the wholesale data.

## Conclusion
Based on the exploratory data analysis (EDA) conducted on the wholesale customer dataset, the following findings can be summarized:

- The distribution of the variables in the dataset is highly skewed, with a majority of the variables having a long tail on the right side. This indicates that there are a few customers who spend significantly more than the majority of customers in each product category.

- There are strong positive correlations observed between the "Grocery" and "Detergents_Paper" variables, as well as between the "Milk" and "Grocery" variables. This suggests that customers who spend more on groceries also tend to spend more on detergents and customers who spend more on milk also tend to spend more on groceries.

- The "Fresh" variable shows a relatively low correlation with the other variables, indicating that the spending on fresh products is not strongly associated with the spending on other product categories. This suggests that customers may have different preferences or needs when it comes to fresh products compared to other categories.

- The majority of the customers in the dataset fall into the lower spending range, with a few customers spending significantly higher amounts in each product category. This indicates that there may be different segments of customers with varying purchasing behaviors, such as regular consumers with moderate spending and occasional high-spending customers.
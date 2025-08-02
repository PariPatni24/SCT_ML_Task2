Customer Segmentation using K-Means Clustering

Task
**SkillCraft Technology Internship – Machine Learning Task 2**  
Cluster mall customers into different groups based on their spending behavior using K-Means Clustering.

Dataset
- Source: [Kaggle – Mall Customer Segmentation Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- Features used:
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1–100)`

 Objective
Apply unsupervised learning (K-Means Clustering) to segment customers into distinct clusters for targeted business insights and marketing strategies.

Workflow
1. Data Preprocessing
   - Load and explore the dataset
   - Handle missing values (if any)
   - Select relevant features for clustering
2. Feature Scaling
   - Standardize features to improve clustering performance
3. Elbow Method
   - Determine optimal number of clusters (k)
4. K-Means Clustering
   - Fit the model and assign clusters
5. Cluster Visualization
   - Use scatter plots to visualize clusters in 2D and optionally in 3D
6. Interpretation
   - Analyze cluster profiles and spending behavior

 Visualizations
- Elbow Method Plot
-  Cluster Plot: Annual Income vs Spending Score
-  Optional 3D Cluster Plot (with Age)

 Evaluation
As this is an **unsupervised** learning problem, we evaluate results based on:
- Visual clarity of cluster separation
- Business interpretability of the clusters

Tools & Libraries
- Python 
- Pandas
- Matplotlib / Seaborn
- scikit-learn

 Files Included
- `SCT_ML_Task2.ipynb` – Colab Notebook with complete implementation

 Author
**Pari Patni**  
Machine Learning Intern – SkillCraft Technology  
August 2025

 Submission Format
Repository Name: `SCT_ML_Task2`  
Notebook: Uploaded & committed  
README: You’re reading it ✅


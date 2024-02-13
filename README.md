# Project-1-Iris-Dataset-Basic-Analysis

# Exploratory Data Analysis (EDA) on the Iris Dataset

# 1.	Data Loading and Overview:
•	The dataset (Iris.csv) is loaded into a Pandas DataFrame (iris_df) with the 'Id' column set as the index.
•	The first few rows of the dataset are displayed using print(iris_df.head()) to get a sense of the data structure.

# 2.	Summary Statistics:
•	Summary statistics of the dataset are computed using iris_df.describe() and printed to understand the central tendency and spread of numerical features.

# 3.	Visualizing Distributions:
•	Visualizations of Sepal and Petal distributions by Species are created using histograms with Kernel Density Estimates (KDE).
•	Subplots are used for Sepal Length, Sepal Width, Petal Length, and Petal Width to compare the distributions across different species.
![image](https://github.com/Vinod-Ghanchi/Project-1-Iris-Dataset-Basic-Analysis/assets/80514865/205a2c7a-499a-4e3c-90cf-5abf1a431995)

# 4.	Pairwise Scatter Plot:
•	A pairwise scatter plot with color-coded species is created using Seaborn's pairplot to explore relationships between different features.
![image](https://github.com/Vinod-Ghanchi/Project-1-Iris-Dataset-Basic-Analysis/assets/80514865/1ac0a488-c540-4a82-9345-1f383516224d)
![image](https://github.com/Vinod-Ghanchi/Project-1-Iris-Dataset-Basic-Analysis/assets/80514865/dd782aef-e2c6-4a5c-855b-def328b5a1f1)

# 5.	Box Plots:
•	Box plots for each feature by species are created to visualize the central tendency, spread, and identify potential outliers.
![image](https://github.com/Vinod-Ghanchi/Project-1-Iris-Dataset-Basic-Analysis/assets/80514865/3a0608f0-1951-4bb3-a6af-18bc87ddf278)
![image](https://github.com/Vinod-Ghanchi/Project-1-Iris-Dataset-Basic-Analysis/assets/80514865/98936c11-8ec7-42db-8aec-bad480b6f3b3)


# 6.	Correlation Matrix:
•	A heatmap of the correlation matrix is generated to identify the linear relationships between numerical features.
![image](https://github.com/Vinod-Ghanchi/Project-1-Iris-Dataset-Basic-Analysis/assets/80514865/2f5bf264-112e-4dcc-9999-75ff5fb744b2)


# 7.	Violin Plots:
•	Violin plots for each feature by species are created to visualize the distribution and density of the data, providing insights into the variability within each species.
![image](https://github.com/Vinod-Ghanchi/Project-1-Iris-Dataset-Basic-Analysis/assets/80514865/f6716848-9a46-4813-8604-e2b32a0c3eed)

# 8.	Swarm Plots:
•	Swarm plots for each feature by species are generated, showing individual data points and their distribution along the categorical axis.
![image](https://github.com/Vinod-Ghanchi/Project-1-Iris-Dataset-Basic-Analysis/assets/80514865/dcb1bff1-a55f-441e-92d7-aa170498e7bb)
![image](https://github.com/Vinod-Ghanchi/Project-1-Iris-Dataset-Basic-Analysis/assets/80514865/d585b38f-e5e1-48d4-9740-39de2da8c27a)


# 9.	3D Scatter Plot:
•	A 3D scatter plot is created to visualize the Sepal dimensions in a three-dimensional space with color-coded species.
![image](https://github.com/Vinod-Ghanchi/Project-1-Iris-Dataset-Basic-Analysis/assets/80514865/eaa73f4b-accc-4b4b-88cf-c60f30c5538f)


# 10.	Parallel Coordinate Plot:
•	A parallel coordinate plot is generated to visualize trends and relationships between features across different species.
![image](https://github.com/Vinod-Ghanchi/Project-1-Iris-Dataset-Basic-Analysis/assets/80514865/5832ed94-4645-4891-af2e-e10f0ed388d2)
![image](https://github.com/Vinod-Ghanchi/Project-1-Iris-Dataset-Basic-Analysis/assets/80514865/b14b3bd9-1273-4f00-9b7e-d07db8067e58)

# 11.	Radar Chart:
•	A radar chart is created to display the normalized average values of features by species, providing a holistic view of the differences in feature values.
![image](https://github.com/Vinod-Ghanchi/Project-1-Iris-Dataset-Basic-Analysis/assets/80514865/61bfec70-802d-42f3-9ab2-fd3dcc5b6ab7)


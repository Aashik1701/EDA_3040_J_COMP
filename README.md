# EDA_3040_J_COMP
J component project for EDA (CSE3040) Tourist Behaviour analysis


CSE3040 Exploratory Data Analysis

J Component - Project Report 



Tourist Behaviour Analysis

By
22MIA1022			   Smitha Gladius T S
22MIA1130        Srilekha R
22MIA1155        Mohammed Aashik F

			
M.Tech CSE with Specialization in Business Analytics


Submitted to

Dr.A.Bhuvaneswari, 
Assistant Professor Senior,
SCOPE, VIT, Chennai

     School of Computer Science and Engineering






ABSTRACT 

This “tourism” abstract uses datasets to investigate the behaviour of tourists, with an emphasis on examining patterns, preferences, and decision-making processes. It investigates variables including destination preference, mode of transportation, spending trends, and satisfaction levels using quantitative approaches. To help stakeholders in the tourism industry improve marketing strategies, destination management, and overall visitor experiences, the study attempts to unearth insights into the dynamics of tourist behaviour. Through the integration of varied datasets, this study advances our comprehension of how travellers engage with locations and amenities, enabling well-informed choices and promoting the growth of sustainable tourism.
Introduction
The behaviour of tourists is a complicated and diverse phenomenon that is influenced by a wide range of internal and external variables. It is imperative that destination management organizations, legislators, marketers, and other tourism sector players comprehend the nuances of visitor behaviour. Conventional approaches to researching visitor behaviour have focused on surveys, interviews, and observations. Although these methods are helpful, their subjective nature and small sample numbers sometimes result in restricted insights. However, the advent of big data and the development of data analytics have created new opportunities for studying the behaviour of tourists by analyzing massive databases. The importance of using datasets to study tourism behaviour is explored in this introduction, along with how they can help find important insights, guide decision-making, and improve the general efficacy and efficiency of tourism management techniques. When compared to conventional research methodologies, the incorporation of datasets into the study of tourism behaviour offers various advantages. First of all, datasets give researchers access to a plethora of historical and real-time data, enabling them to get a complete picture of visitor behaviours, preferences, and trends. Researchers can learn about a variety of aspects of tourist behaviour, such as destination choice, travel patterns, spending habits, preferred accommodations, and satisfaction levels, by examining data from sources like booking platforms, social media, mobile apps, and transportation systems. Additionally, by using quantitative methods to examine visitor behaviour, databases help researchers find statistically significant trends, correlations, and patterns in the data. In contrast to subjective research, this quantitative analysis improves the rigour and reproducibility of findings, offering a more objective knowledge of visitor behaviour. Furthermore, the knowledge gained from dataset analysis can help formulate policies and make evidence-based decisions related to tourism management. Data-driven insights can be used by destination management companies to create focused marketing campaigns, allocate resources optimally, build infrastructure better, and improve guest experiences. In a similar vein, data can be used by legislators to solve sustainability issues, lessen congestion, and encourage ethical tourism. In conclusion, the use of datasets in the research of visitor behaviour has enormous potential to transform our knowledge of visitor dynamics and help guide industry strategic decision-making. Through the utilization of big data analytics, scholars can gain important insights that support the sustainable growth and administration of tourism destinations across the globe.
Dataset:
Description: The dataset contains information related to travel and user interactions with travel-related content or services. It includes various features such as average views on travel pages, likes on check-ins, family membership status, comments on travel pages, network ratings, etc.
Features: Features represent different aspects or attributes of the data that can be used for analysis or prediction. These include both numerical features (e.g., average views, likes) and categorical features (e.g., preferred device, preferred location type).
Target Variable: The target variable represents the outcome or prediction target of interest in a machine learning task. In this case, it seems like the target variable is related to purchasing behavior ('Buy_ticket'), indicating whether a user purchased a ticket or not.
Tools Used:
Pandas: For data analysis and manipulation, Pandas is a potent Python package. To work with structured data effectively, it offers data structures such as DataFrames. Pandas is used in this project to load the dataset, choose pertinent columns, and handle preliminary data.

Scikit-learn, sometimes known as sklearn, is a well-known Python machine learning framework that offers a variety of tools for creating machine learning models. Sklearn is used in this research to extract features, normalize data, and possibly even create prediction models.

Seaborn and Matplotlib: These two Python packages are used to visualize data. While Seaborn offers more sophisticated statistical visualization features, Matplotlib gives more basic plotting functionalities. Visualizing patterns, distributions, and relationships within the data can be accomplished with the use of these tools.

NumPy: NumPy is a core Python scientific computing package. It supports operations in linear algebra, mathematical functions, and multidimensional arrays. While not stated directly in the code samples, other libraries such as scikit-learn and Pandas frequently use NumPy internally.

Jupyter Notebook and Google Colab: These two interactive computing environments let you make and distribute documents with real-time code, formulas, graphics, and narrative prose. Because they allow for an experimental and iterative approach to data science projects, they are frequently used for data analysis, exploration, and machine learning model prototyping.

Algorithm and Techniques used

Data Cleaning:
Description: Data cleaning involves identifying and correcting errors or inconsistencies in the dataset to ensure its quality and reliability for analysis.
Implementation:
Missing Values: Identify missing values in the dataset and decide how to handle them (e.g., imputation, removal).
Duplicate Records: Identify and remove duplicate records from the dataset.
Data Validation: Validate the integrity and consistency of the data (e.g., checking for incorrect data types, out-of-range values).
Handling Outliers: Identify and handle outliers, which are data points that deviate significantly from the rest of the data and may distort analysis results.
Data Processing:
Description: Data processing involves transforming the raw data into a format suitable for analysis and modeling.
Implementation:
Normalization/Standardization: Scale numerical features to a standard range to ensure that they have similar magnitudes.
Encoding Categorical Variables: Convert categorical variables into numerical representations using techniques such as one-hot encoding.
Feature Engineering: Create new features or transform existing ones to extract more meaningful information from the data.
Feature Extraction:
Description: Feature extraction involves deriving new features from the existing ones to capture relevant information for analysis and modeling.
Implementation:
Principal Component Analysis (PCA): Extract principal components that capture the maximum variance in the data while reducing dimensionality.
Text Processing: Extract features from text data using techniques or word embeddings.
Image Processing: Extract features from images using techniques such as edge detection, texture analysis, or deep learning-based feature extraction.
Feature Subset Selection:
Description: Feature subset selection involves identifying the most relevant subset of features from the original set to improve model performance and interpretability.
Implementation:
Univariate Feature Selection: Select features based on their individual relationship with the target variable using statistical tests such as ANOVA or chi-square.
Recursive Feature Elimination (RFE): Select features by recursively training a model and eliminating the least important features based on their coefficients or feature importance scores.
Model-Based Feature Selection: Select features based on their importance scores obtained from a machine learning model (e.g., decision trees, random forests).
Outlier Detection:
Description: Outlier detection involves identifying data points that deviate significantly from the rest of the data distribution, potentially indicating errors or anomalies.
Implementation:
Statistical Methods: Detect outliers using statistical measures such as z-scores, quartiles, or standard deviations.
Distance-Based Methods: Detect outliers based on their distance from the centroid or nearest neighbors in the feature space.
  6.       Descriptive Statistics:
Algorithm/Technique: Summary Statistics
Description: Summary statistics such as mean, median, mode, standard deviation, minimum, maximum, and percentiles provide an overview of the central tendency, dispersion, and distribution of numerical data.
    7.Plots:
Histograms: Visualize the distribution of numerical data.
Box plots: Show the distribution of numerical data and identify outliers.
Violin plots: Combine the features of box plots and kernel density plots to visualize the distribution of data.
8.Correlation Analysis:
Algorithm/Technique: Pearson Correlation Coefficient
Description: Measures the linear correlation between pairs of numerical variables. It ranges from -1 to 1, where 1 indicates a perfect positive correlation, -1 indicates a perfect negative correlation, and 0 indicates no correlation.
Plots:
Scatter plots: Visualize the relationship between pairs of numerical variables.
Heatmaps: Display the correlation matrix between all pairs of numerical variables.
9.Cluster Analysis:
Algorithm/Technique: K-means Clustering
Description: Partition numerical data into k clusters based on their similarities, aiming to minimize the intra-cluster distance and maximize the inter-cluster distance.
Plots:
Scatter plots with clustered data points: Visualize the clustering results by plotting data points colored by their cluster assignments.

Conclusion and future enhancements
Contribution by teammates
Github Link:
References:
[1]. Daniel MagoVistro, Faizan Rasheed, Leo Gertrude David, “The Cricket Winner Prediction With Application of Machine Learning And Data Analytics” International Journal of Scientific & Technology Research (2019) 
[2]. Madan Gopal Jhanwar and VikramPudi, “Predicting the Outcome of ODI Cricket Matches: A Team Composition Based Approach” International Institution of Information Technology (2017) [3]. I. P. Wickramasingheet. al, "Predicting the performance of batsmen in test cricket," Journal of Human Sport & Exercise”, vol. 9, no. 4, pp. (2017) 
[4]. R. P. Schumaker, O. K. Solieman and H. Chen, "Predictive Modeling for Sports and Gaming” in Sports Data Mining, vol. 26, Boston, Massachusetts: Springer, (2016) 
[5]. J. McCullagh, "Data Mining in Sport: A Neural Network Approach," International Journal of Sports Science and Engineering, vol. 4, no. 3 (2016) 
[6]. Bunker, Rory &Thabtah, Fadi. “A Machine Learning Framework for Sport Result Prediction. Applied Computing and Informatics”. (2017) 
[7] Kulkarni, V. & Sinha, P., n.d. Effective Learning and Classification using Random Forest Algorithm. International Journal of Engineering and Innovative Technology (IJEIT). 
[8] Lokhande, A., Chawan, R. &. &Pramila&, S., 2018. Prediction of Live Cricket Score and Winning. Computer and IT Dept, VeermataJeejabai Technological Institute, Mumbai, India, 5(4)(2394-9333). 
[9] Mitchel, M. T., 1997. Machine learning. Burr Ridge, IL: McGraw Hill, 45, 1997. 
[10] Murphy, K. P., 2006. Naive bayes classifiers. University of British Columbia.
[11] Nasteski &Vladmir, 2007. An Overview of the Supervised Machine Learning Methods. Faculty of Information and Technology. Faculty of Information and communication Technologies. 
[12] Shah, P. & Shah, M., 2015. Predicting ODI Cricket Result. ISSN (Paper) 2312-5187 ISSN (Online) 2312-5179 An International Peer-reviewed Journal, Volume 5



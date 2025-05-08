# Business Formation Analysis with U.S. Census BFS Data

This project analyzes U.S. business formation trends using data from the U.S. Census Bureau’s Business Formation Statistics (BFS). The analysis is based on the seasonally unadjusted, 2025 Q1, US business applications.

---

### 1. Business Understanding

As someone currently working as an Operations Manager and owner of a startup, I’ve been deeply involved in helping individuals launch and grow their businesses. I’ve worked hands-on with clients to guide them through the early stages of formation, from idea to execution. This dataset instantly stood out to me as an opportunity to compare national business formation trends with what I’ve been seeing on the ground.

What I wanted to find out?

- What sector is gaining the most traction? NAICSRET - Retail Trade - The business applications are for the retail trade sector with 249,898 applications.

- Are the businesses my clients are starting aligned with broader national trends? The business's that are being started by clients are in the same sector.

- How might these trends evolve in the near future? The model was used to predict April's Business applications, Retail Trade still has the highest number of applications around 86 to 87,000.

This project is both professionally relevant and personally rewarding, as it allows me to bring data-driven insight into a space I’m actively working to improve.

### 2. Data Understanding
- **Dataset Source:** U.S. Census Bureau – https://www.census.gov/econ/bfs/current/index.html
- **Dataset Dictionary:** U.S. Census Bureau – https://www.census.gov/econ/bfs/pdf/bfs_monthly_data_dictionary.pdf
- Files: bfs_mothly.csv, bfs_monthly_data_dictionary.pdf

### 3. Data Preparation
- Filtered for relevant columns
- Cleaned missing or null values
- Aggregated data by NAICS sector and number of business applications.

### 4. Modeling
A **linear regression model** was built to predict monthly business applications using Janaury & February as the features and March as the target.

### 5. Evaluation
- **Metrics used:** Mean Squared Error (MSE) 6402148.316243282, Root Mean Squared Error (RMSE) 2530.246690787932
- **Findings:** The Model performs decent and has a 10% error. It's predictions are off about 2,530 applications. This suggests that the model is able to capture more of a general prediction, but it is not very precise. Using the model to predict applications for April, the NAICS sector 'Retail Trade' still has the highest number, around 86 to 87,000. 

### 6. Deployment
This analysis is presented in a Jupyter Notebook and summarized in a blog post on my webiste.

### File Description

Graphs and plots of the data in this repository:

- Total Q1 Applications by NAICS Sector.png - Bar graph PNG of Total Q1 Applications by NAICS Sector
- Hypothetical April 2025 Business Applications by Sector.png - Bar graph PNG of Predicted April Applications by NAICS Sector
- Actual vs Predicted March Applications.png - Scatter Plot PNG of Actual vs. Predicted Values for March
  
Data Sources:

- bfs_montly.csv - Notebook containing the data analysis
- bfs_monthly_data_dictionary.pdf - PDF of dataset terms/definitions
- Vizal Business List.pdf - PDF of Vizal Business List 
- Vizal Business List.img - Image of Vizal Business List



---

## Repositary link  

[https://github.com/Nataskie/Data-Science-Blog-Post.gitcd Data-Science-Blog-Post](https://github.com/Nataskie/Data-Sceince-Blog-Post.git)

## Blog Link
https://www.belladessinsstudio.com/post/which-businesses-are-blooming-in-america 

## References
 I acknowledge Eddy May for insightful guidance, structuring and for helping me to adhere to the project guidelines.
 I aslo acknowledge The Purposed Eagle Network & Vizal for providing the comparison information for this project.

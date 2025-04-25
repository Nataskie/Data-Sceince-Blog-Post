# Business Formation Analysis with U.S. Census BFS Data

This project analyzes U.S. business formation trends using data from the U.S. Census Bureau’s Business Formation Statistics (BFS). The analysis is based on the seasonally unadjusted, 2025 Q1, US business applications.

---

### 1. Business Understanding

As someone currently working as an Operations Manager and owner of a startup, I’ve been deeply involved in helping individuals launch and grow their businesses. I’ve worked hands-on with clients to guide them through the early stages of formation, from idea to execution. This dataset instantly stood out to me as an opportunity to compare national business formation trends with what I’ve been seeing on the ground.

What I wanted to find out?

- What sector is gaining the most traction? NAICSRET - Retail Trade

- Are the businesses my clients are starting aligned with broader national trends? Yes, I have 

- How might these trends evolve in the near future? The model was used to predict April's Business applications.

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
- **Metrics used:** Mean Squared Error (MSE), Root Mean Squared Error (RMSE)
- **Findings:** Model performs decent, has a 10% error.

### 6. Deployment
This analysis is presented in a Jupyter Notebook and summarized in a blog post on my webiste.
Graphs and plots of the data in this repository:
- Total Q1 Applications by NAICS Sector.png
- Hypothetical April 2025 Business Applications by Sector.png
- Actual vs Predicted March Applications.png

---

## Repositary link  

[https://github.com/Nataskie/Data-Science-Blog-Post.gitcd Data-Science-Blog-Post](https://github.com/Nataskie/Data-Sceince-Blog-Post.git)

## References
 I acknowledge Eddy May for insightful guidance, structuring and adhering to the project guidelines.

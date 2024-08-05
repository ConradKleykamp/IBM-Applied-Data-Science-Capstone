# IBM-Applied-Data-Science-Capstone
![image](https://github.com/user-attachments/assets/00a1035d-514d-48fb-982e-fdfcfb9df90b)

This repository includes all the work that was completed as part of IBM's Applied Data Science Capstone course. The files included here are:
- 1 Data Collection API
- 2 Data Collection with Web Scraping
- 3 Data Wrangling
- 4 EDA with SQL
- 5 EDA with Visualization
- 6 Launch Sites Locations Analysis with Folium
- 7 Interactive Dashboard with Plotly Dash
- 8 Machine Learning Prediction
- IBM Capstone Final Presentation/Report

---

### Objective
SpaceY is a fictional commercial rocket launch provider that wishes to compete against SpaceX. SpaceX's Falcon 9 rocket launches are advertised to cost $62 million, while other rocket launch providers cost ~$165 million. SpaceX's savings are due to the ability to land and reuse the first stage. How can a company like SpaceY bid against SpaceX for a rocket launch? By using public SpaceX data, if we can determine whether the first stage will land, we can determine the cost of a launch. Overall, this project leverages multiple machine learning models to accurately predict the likelihood of a successful landing of the first stage rocket. 

---

### Methods
Data Collection
- API, Web Scraping (BeautifulSoup)

Data Wrangling
- Replacing missing values
- Training label --> 'Outcome' column
- One Hot Encoding --> 1 (Successful Landing), 0 (Unsuccessful landing)

Exploratory Data Analysis (EDA)
- SQL Queries
- Visualizations w/ Matplotlib, Seaborn

Launch Sites Location Analysis
- Folium

Launch Records Dashboard
- Plotly Dash

Predictive Analysis
- Logistic Regression
- Support Vector Machine
- Decision Tree Classifier
- K Nearest Neighbor Classifier

---

### General Results
The overall task was a binary classification problem, where an 'Outcome' of 1 represented a successful landing and an 'Outcome' of 0 represented an unsuccessful landing. It was found that all predictive methods/models yielded a ~83.33% test set accuracy in predicting whether or not a rocket landing would be successful. The Decision Tree Classifier yielded the highest training set accuracy (~88.88%) when compared to the other models. 

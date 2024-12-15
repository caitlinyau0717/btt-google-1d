# BTT-Google-1D

#### A machine learning project designed to analyze Google search trends related to alcohol and marijuana, and understand how interest in these topics varies across time and location in response to specific events.

## Contributors
- Caitlin Yau
- Sruti Karthikeyan
- Shreya Narayanan
- Avritt Rohwer (Challenge Advisor)
- Michelle Hui (Teaching Assistant)

## Individual Contributions
- Data Collection: Avritt, Sruti, Caitlin, Shreya
- Data Analysis: Caitlin
- Random Forest Model Development: Caitlin
- SARIMA Model Development: Sruti
- Prophet Model Development: Sruti
- Result Analysis: Caitlin
- Weekly/Monthly Aggregation: Sruti
- State-level Analysis: Caitlin

## Running the Project
Download the .ipynb files and the .csv files and run them in Google Colab or Jupyter Notebooks. Change the .csv file input in the python notebook as needed.

## Goals
- Predict future high-interest periods for alcohol and marijuana
- Identify patterns in search interest over time, location (state), and forecast potential spikes to perform targeted interventions, such as promoting healthier alternatives during high-interest periods. 
- Combine data analysis, feature engineering, machine learning models, and a rolling forecast framework to provide a dynamic, real-time prediction model.

## Business Impact
- Google created a challenge for a hypothetical public health organization.
    - The goal is to promote healthier alternatives to popularly misused drugs.
- The organization aims to maximize advertising impact.
    - The organization has limited funds.
    - Advertising efforts will target areas with the highest search interest in misused drugs.

## Resources Leveraged
- Google Trends
- Google Colab
- Pandas
- Scikit Learn
- Matplotlib
- Numpy

## Results and Key Findings
- States had varying search interest results where many were above, approximately, and below the national average where the highest is California and the lowest is Wyoming.
    - Could be due to numerous reasons including population differences and substance laws.
        - As of 2023, California has a population 38.9M while Wyoming has a population of 584,057
        - Weed is legal in California but not in Wyoming
- Loss function results by states varied as loss in states such as California and New York were much lower than loss in states such as Montana and Vermont
- The states with the highest search interest are as follows: Michigan, Pennsylvania, Oklahoma, Minnesota, Maine, Colorado, Arkansas

## Potential Next Steps
Testing out new models
- Times Series Clustering (K-Means Clustering, DBSCAN)
- Further Exploring Our Models (Random Forest, SARIMA, Prophet)
Further exploratory analysis
- More demographics (gender, race, age)
Adding on a sentiment analysis component 
- Explore headline events to track trends based on sentiments
Advertise substance awareness
- Utilize generative AI to analyze news headlines and support advertising efforts

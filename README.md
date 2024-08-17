# Association-rules_ML

Project Overview

This project generates synthetic transaction data and performs the following analyses:
1. Apriori Algorithm : Generates association rules from the transaction data.
2. K-Means Clustering : Segments customers based on their transaction history.

The results are visualized using Plotly, and the generated HTML files can be hosted locally for review.

Features

- Synthetic Data Generation : Creates random customer and product transaction data.
- Apriori Algorithm : Extracts association rules with adjustable support and confidence thresholds.
- K-Means Clustering : Groups customers into clusters for segmentation analysis.
- Interactive Visualizations : Generates interactive 3D visualizations of the analysis.

Setup
Installation

1. Clone the repository:
 
    

2. Install the required Python packages:

    bash ~

    pip install -r requirements.txt
    

Usage

1. Run the script:

    To generate the synthetic data, run the Apriori algorithm, and perform K-Means clustering, execute the following command:

    bash ~
    python analyzer.py
    

2. View the Results:

Requirements !
numpy==1.24.4
pandas==2.0.3
faker==20.0.0
plotly==5.15.0
scikit-learn==1.2.2
tqdm==4.66.1
 
 
 OR

run this command in your terminal ---> pip install -r requirements.txt


Home page ~ 


![image](https://github.com/user-attachments/assets/3a303337-8d9e-46cd-984a-2b6311c56570)


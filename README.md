# Thesis Repository: Operational Efficiency Analysis at Nishat Mills Limited

This repository contains primary data and analysis code used in my thesis report on operational efficiency practices at Nishat Mills Limited (NML). The data was collected through qualitative interviews and quantitative surveys from NML employees. The focus is on identifying efficiency practices, challenges, and recommendations for cost reduction in textile manufacturing operations.

The repository includes raw survey data in Excel format and a Jupyter Notebook with Python code for data analysis, visualization, and modeling (e.g., using libraries like Pandas, Matplotlib, Seaborn, Scikit-learn, and Statsmodels).

## Repository Contents

- *Nishat survey dataset.xlsx*: Raw survey responses from NML employees. This file includes timestamped entries with questions on demographics, awareness of efficiency practices, challenges, and suggestions for improvement. Data is anonymized and covers departments like Spinning, Weaving, Dyeing/Processing, and Finishing.
  
- *Nishat Operational efficiencies Analysis.ipynb*: Jupyter Notebook containing Python code for:
  - Data loading and preprocessing.
  - Exploratory data analysis (EDA) with visualizations (e.g., histograms, heatmaps).
  - Statistical modeling (e.g., regression analysis using Statsmodels).
  - Machine learning models (e.g., Random Forest Regressor for predicting efficiency factors).
  - Evaluation metrics (e.g., MAE, R² score) and learning curves.

## Data Collection Overview

The primary data consists of:
- *Qualitative Data*: Gathered through semi-structured interviews with NML employees to explore in-depth insights on operational challenges and efficiency practices.
- *Quantitative Data*: Collected via surveys (as in the Excel file) from front-line workers, focusing on metrics like waste reduction, machine maintenance, and cost-saving contributions.

All data was collected ethically, with participant consent, and is used solely for academic purposes in this thesis.

## Requirements

To run the Jupyter Notebook:
- Python 3.x
- Install dependencies via pip:
  
  pip install pandas numpy matplotlib seaborn statsmodels scikit-learn
  
- Jupyter Notebook or Google Colab for execution.

## Usage

1. Clone the repository:
   
   git clone https://github.com/Hamza-dev60/MSc-dissertation-2026.git
   
2. Open the Jupyter Notebook (Nishat Operational efficiencies Analysis.ipynb) in Jupyter or upload to Google Colab.
3. Ensure the Excel file is in the same directory or update the file path in the code.
4. Run the cells sequentially for data loading, analysis, and visualizations.

Note: The notebook includes code to upload files in Google Colab; adjust as needed for local environments.

## Methodology Flowchart

Below is a Mermaid diagram illustrating the high-level workflow of data collection and analysis used in the thesis.

mermaid
flowchart TD
    A[Start: Thesis Research Objective] --> B[Data Collection Phase]
    B --> C1[Qualitative Interviews]
    B --> C2[Quantitative Surveys]
    C1 --> D[Transcribe & Analyze Themes<br>(e.g., Challenges in Efficiency)]
    C2 --> E[Compile Survey Data<br>(Nishat survey dataset.xlsx)]
    D --> F[Integrate Insights]
    E --> F
    F --> G[Data Analysis in Jupyter Notebook<br>(EDA, Visualization, Modeling)]
    G --> H[Derive Findings & Recommendations<br>(e.g., Cost Reduction Strategies)]
    H --> I[End: Thesis Report]


This diagram can be rendered directly in GitHub's Markdown preview.

## License

This repository is for academic purposes only. Data and code are shared under [MIT License](LICENSE). Please cite this repository if used in further research.

## Contact

For questions related to the thesis or repository, contact [ht0565m@gre.ac.uk].

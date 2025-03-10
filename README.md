# Marriage Trends in India: Love vs. Arranged - Data Analysis

## Overview
This repository contains a Jupyter Notebook that conducts an in-depth analysis of marriage trends in India, comparing "Love" and "Arranged" marriages. The analysis leverages the dataset sourced from Kaggle: [Marriage Trends in India - Love vs. Arranged](https://www.kaggle.com/datasets/ak0212/marriage-trends-in-india-love-vs-arranged). The notebook explores various dimensions of marital dynamics, including temporal trends, demographic factors, parental approval, urban-rural differences, marital satisfaction, divorce rates, and socio-economic influences, providing a comprehensive view of evolving societal patterns in India.

## Objectives
- Investigate the prevalence and trends of Love versus Arranged marriages over time.
- Analyze the influence of factors such as age, education, religion, income, and location on marriage type.
- Assess outcomes like marital satisfaction, divorce rates, and inter-caste/inter-religion marriages.
- Highlight cultural and socio-economic factors shaping marital preferences in India.

## Repository Contents
- **`Marriage_Trends_India_Analysis.ipynb`**: The main Jupyter Notebook containing the data analysis, visualizations, and findings.
- **`marriage_data_india.csv`** (optional): The dataset file (not included in the repository; download from Kaggle).
- **`README.md`**: This file, providing an overview and instructions for the project.

## Dataset
The analysis is based on the "Marriage Trends in India: Love vs. Arranged" dataset from Kaggle. Key features include:
- `Marriage_Type`: Love or Arranged
- `Year_of_Marriage`: Derived from `Years_Since_Marriage`
- `Age_at_Marriage`: Age at the time of marriage
- `Education_Level`: Educational attainment
- `Parental_Approval`: Level of parental consent
- `Urban_Rural`: Urban or rural residence
- `Religion`: Religious affiliation
- `Marital_Satisfaction`: Satisfaction rating
- `Divorce_Status`: Divorce outcome
- `Inter-Caste` & `Inter-Religion`: Indicators of mixed marriages
- `Spouse_Working`: Employment status of spouse
- `Children_Count`: Number of children
- `Dowry_Exchanged`: Presence of dowry
- `Income_Level`: Income category

**Note**: The dataset must be downloaded from the Kaggle link and placed in the appropriate directory (e.g., `/kaggle/input/`) for the notebook to run locally or in a Kaggle environment.

## Requirements
To run the notebook, ensure the following Python libraries are installed:
- `numpy`
- `pandas`
- `seaborn`
- `matplotlib`
- `datetime`

Install dependencies using pip:
```bash
pip install numpy pandas seaborn matplotlib
```

## Usage
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/[your-username]/marriage-trends-india-analysis.git
   cd marriage-trends-india-analysis
   ```

2. **Download the Dataset**:
   - Obtain `marriage_data_india.csv` from the [Kaggle dataset page](https://www.kaggle.com/datasets/ak0212/marriage-trends-in-india-love-vs-arranged).
   - Place it in a directory matching the notebook's input path (e.g., `/kaggle/input/marriage-trends-in-india-love-vs-arranged/`).

3. **Run the Notebook**:
   - Open the notebook in Jupyter:
     ```bash
     jupyter notebook Marriage_Trends_India_Analysis.ipynb
     ```
   - Alternatively, use Google Colab or Kaggle Notebooks by uploading the file and dataset.

4. **Explore the Analysis**:
   - Execute cells sequentially to load data, preprocess, and generate visualizations.
   - Review the "Summary of Findings" section for key insights.

## Key Findings
- **Trends**: Love marriages are increasing, while Arranged marriages are declining.
- **Demographics**: Minimal variation in marriage type by education; Love marriages slightly more common among Graduates.
- **Cultural Factors**: High parental approval for Arranged marriages (90.25%) vs. Love marriages (88.79%).
- **Urban-Rural Shift**: Post-2005, Love marriages gained popularity in rural areas.
- **Outcomes**: Higher divorce rates in Love marriages (10.1%); Arranged marriages report stable satisfaction (80.1%).
- **Socio-Economic Insights**: Middle-income families favor Love marriages; dowry is rising in urban areas (31%).

For detailed results, refer to the notebook's "Summary of Findings" section.

## Structure of the Notebook
1. **Introduction**: Project overview and objectives.
2. **Data Loading and Exploration**: Initial data inspection.
3. **Data Preprocessing**: Feature engineering (e.g., `Year_of_Marriage`).
4. **Exploratory Data Analysis (EDA)**: Visualizations and statistical insights across multiple dimensions.
5. **Summary of Findings**: Consolidated insights.
6. **Additional Analysis Suggestions**: Ideas for further exploration.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/new-analysis`).
3. Commit changes (`git commit -m "Add new analysis"`).
4. Push to the branch (`git push origin feature/new-analysis`).
5. Open a Pull Request.

Please ensure code follows PEP 8 guidelines and includes comments for clarity.


## Acknowledgments
- Dataset provided by [ak0212](https://www.kaggle.com/ak0212) via Kaggle.
- Built with support from open-source libraries: NumPy, Pandas, Seaborn, and Matplotlib.

## Contact
For questions or suggestions, please open an issue on GitHub or contact [msourav38@gmail.com].

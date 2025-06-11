# Hospital Patient Records Analysis

A comprehensive data analysis project focused on analyzing hospital patient records to extract meaningful insights about patient demographics, medical procedures, costs, and outcomes. This project is part of the CISAM competition initiative.

## 📋 Project Overview

This project analyzes a dataset of hospital patient records containing information about patient demographics, medical conditions, procedures, costs, length of stay, readmission rates, and patient satisfaction. The analysis aims to identify patterns and trends that can help improve healthcare delivery and patient outcomes.

## 🎯 Features

- **Patient Demographics Analysis**: Age and gender distribution analysis
- **Medical Condition Insights**: Analysis of common conditions and their treatment patterns
- **Cost Analysis**: Healthcare cost patterns and factors affecting treatment expenses
- **Length of Stay Analysis**: Factors influencing hospital stay duration
- **Readmission Rate Study**: Identification of patterns in patient readmissions
- **Patient Satisfaction Metrics**: Analysis of satisfaction scores and their correlations
- **Outcome Tracking**: Recovery and stability outcome analysis

## 📊 Dataset Information

The dataset contains **984 patient records** with the following attributes:

| Column | Description |
|--------|-------------|
| Patient_ID | Unique identifier for each patient |
| Age | Patient age |
| Gender | Patient gender (Male/Female) |
| Condition | Medical condition/diagnosis |
| Procedure | Medical procedure performed |
| Cost | Treatment cost |
| Length_of_Stay | Number of days in hospital |
| Readmission | Whether patient was readmitted (Yes/No) |
| Outcome | Treatment outcome (Recovered/Stable) |
| Satisfaction | Patient satisfaction score (1-5) |

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- Jupyter Notebook or JupyterLab
- Required Python packages (install using pip):

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/hospital-patient-records.git
cd hospital-patient-records
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```
*Note: If requirements.txt doesn't exist, install the packages mentioned in Prerequisites*

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

4. Open the analysis notebook:
```
src/hospital-patient-records.ipynb
```

## 📁 Project Structure

```
hospital-patient-records/
├── README.md                          # Project documentation
├── src/                              # Source code and analysis
│   ├── hospital-patient-records.ipynb # Main analysis notebook
│   └── data/                         # Dataset directory
│       └── hospital data analysis.csv # Hospital patient records dataset
└── .github/                          # GitHub workflow and instructions
    ├── instructions/                 # Project instruction files
    │   ├── readme.instructions.md    # README generation guidelines
    │   └── release-notes.instructions.md
    └── prompts/                      # Automation prompts
        ├── generate-readme.prompt.md
        └── generate-release-notes.prompt.md
```

## 💻 Usage

1. **Open the Jupyter Notebook**: Navigate to `src/hospital-patient-records.ipynb`

2. **Load the Dataset**: The notebook will load data from `src/data/hospital data analysis.csv`

3. **Run Analysis Cells**: Execute cells sequentially to perform various analyses:
   - Data exploration and cleaning
   - Descriptive statistics
   - Visualization of key metrics
   - Pattern identification
   - Insights generation

4. **Interpret Results**: Review the generated charts, statistics, and insights to understand hospital patient patterns

### Example Analysis Areas

- **Cost vs. Length of Stay**: Analyze the relationship between treatment costs and hospital stay duration
- **Readmission Patterns**: Identify factors that contribute to patient readmissions
- **Satisfaction Analysis**: Examine what drives patient satisfaction scores
- **Demographic Insights**: Understand how age and gender affect treatment outcomes

## 🔍 Key Insights

*This section will be populated as the analysis progresses with findings such as:*

- Average length of stay by medical condition
- Cost patterns across different procedures
- Readmission rates by demographic groups
- Satisfaction score correlations with outcomes

## 🤝 Contributing

This project is part of the CISAM COMPET. Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/analysis-improvement`)
3. Commit your changes (`git commit -am 'Add new analysis feature'`)
4. Push to the branch (`git push origin feature/analysis-improvement`)
5. Create a Pull Request

## 📄 License

This project is created for educational and competition purposes. Please refer to your institution's guidelines for data usage and sharing policies.

## 👨‍💻 Credits & Acknowledgments

- **Author**: Gabriel Borges
- **Organization**: COMPET CISAM
- **Tools Used**: 
  - Python for data analysis
  - Pandas for data manipulation
  - Matplotlib/Seaborn for visualization
  - Jupyter Notebook for interactive analysis

## 📞 Contact

For questions about this analysis or collaboration opportunities, please reach out through the CISAM competition channels.

---

*This README was generated to provide comprehensive documentation for the Hospital Patient Records Analysis project. Update this file as the analysis evolves and new insights are discovered.*

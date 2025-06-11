# Hospital Patient Records Analysis - Maternity Focus

A comprehensive data analysis project focused on analyzing hospital patient records with a specific emphasis on **maternity care and female patient outcomes**. This project analyzes female patient demographics, medical conditions, treatment outcomes, and satisfaction patterns while excluding financial data to focus purely on clinical and care quality metrics. This project is part of the CISAM competition initiative.

## 📋 Project Overview

This project analyzes a filtered dataset of hospital patient records focusing exclusively on **female patients** to better understand maternity care patterns and women's healthcare outcomes. The analysis examines patient demographics, medical conditions, procedures, length of stay, readmission rates, and patient satisfaction scores. By focusing on female patients and excluding cost analysis, this study aims to identify patterns and trends that can help improve maternal healthcare delivery and patient outcomes.

## 🎯 Features

- **Female Patient Demographics Analysis**: Age and gender distribution analysis focused on maternity care
- **Medical Condition Insights**: Analysis of conditions affecting female patients and maternity-related care
- **Maternity Care Focus**: Specialized analysis of childbirth and pregnancy-related cases
- **Length of Stay Analysis**: Factors influencing hospital stay duration for female patients
- **Readmission Rate Study**: Identification of readmission patterns in female patients
- **Patient Satisfaction Metrics**: Analysis of satisfaction scores and their correlations with outcomes
- **Outcome Tracking**: Recovery and stability outcome analysis for female patients
- **Non-Financial Analysis**: Focus on clinical and care quality metrics without cost considerations

## 📊 Dataset Information

The dataset contains **filtered female patient records** from the original hospital dataset with the following characteristics:

**Analysis Focus:**
- **Female patients only** - Filtered to focus on maternity and women's healthcare
- **Non-financial analysis** - Cost data excluded to focus on clinical outcomes
- **Maternity care emphasis** - Special attention to childbirth and pregnancy-related cases

| Column | Description |
|--------|-------------|
| Patient_ID | Unique identifier for each patient |
| Age | Patient age |
| Gender | Patient gender (Female only in filtered dataset) |
| Condition | Medical condition/diagnosis |
| Procedure | Medical procedure performed |
| Length_of_Stay | Number of days in hospital |
| Readmission | Whether patient was readmitted (Yes/No) |
| Outcome | Treatment outcome (Recovered/Stable) |
| Satisfaction | Patient satisfaction score (1-5) |

**Note:** The original dataset contained both male and female patients with cost information, but this analysis focuses specifically on female patients with cost data removed to emphasize clinical care quality metrics.

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- Jupyter Notebook or JupyterLab
- Required Python packages:

```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
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

Or install packages individually:

```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
```

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

2. **Load the Dataset**: The notebook automatically loads data from `src/data/hospital data analysis.csv`, filters for female patients only, and removes financial data

3. **Run Analysis Cells**: Execute cells sequentially to perform maternity-focused analyses:
   - Data exploration and cleaning (female patients only)
   - Demographic analysis for women's healthcare
   - Medical conditions analysis with maternity focus
   - Length of stay patterns for female patients
   - Readmission and outcomes analysis
   - Patient satisfaction metrics
   - Correlation analysis (non-financial variables)

4. **Interpret Results**: Review the generated charts, statistics, and insights to understand female patient and maternity care patterns

### Example Analysis Areas

- **Maternity Demographics**: Analyze age distribution and patterns in female patients
- **Childbirth vs. Other Conditions**: Compare treatment patterns between maternity and other medical conditions
- **Female Patient Satisfaction**: Examine satisfaction drivers specific to women's healthcare
- **Non-Financial Outcomes**: Focus on clinical quality metrics without cost considerations
- **Readmission Patterns**: Identify factors affecting female patient readmissions

## 🔍 Key Insights

Based on the maternity-focused analysis of female patients:

### Demographics & Patient Profile
- **Focused Dataset**: Analysis of female patients only, excluding financial data
- **Age Distribution**: Comprehensive age analysis for women's healthcare patterns
- **Maternity Cases**: Specific tracking of childbirth and pregnancy-related conditions

### Clinical Outcomes
- **Treatment Outcomes**: Recovery and stability rates for female patients
- **Length of Stay**: Hospital duration patterns specific to women's healthcare needs
- **Readmission Rates**: Patterns in female patient readmissions, including maternity cases
- **Patient Satisfaction**: Satisfaction scores analyzed specifically for women's healthcare experience

### Analytical Focus
- **Non-Financial Metrics**: Emphasis on clinical quality rather than cost factors
- **Maternity Care**: Specialized insights into childbirth and pregnancy-related healthcare
- **Correlation Analysis**: Relationships between age, length of stay, and satisfaction for female patients
- **Condition-Specific Patterns**: Treatment variations across different medical conditions affecting women

*Note: Specific numerical insights are generated dynamically in the Jupyter notebook based on the current dataset analysis.*

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
- **Project Focus**: Maternity and Women's Healthcare Analysis
- **Tools Used**:
  - Python for data analysis and statistical computing
  - Pandas for data manipulation and filtering
  - NumPy for numerical computations
  - Matplotlib/Seaborn for data visualization
  - SciPy for statistical analysis
  - Jupyter Notebook for interactive analysis and documentation

## 📞 Contact

For questions about this analysis or collaboration opportunities, please reach out through the CISAM competition channels.

---

*This README documents the Hospital Patient Records Analysis project with a specialized focus on maternity care and women's healthcare outcomes. The analysis excludes financial data to emphasize clinical quality metrics and patient care patterns. Update this file as the analysis evolves and new insights are discovered.*

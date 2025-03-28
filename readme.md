# Rolling Matching Analysis in Healthcare Outreach

## 📊 Project Overview

This project demonstrates a sophisticated data science approach to analyzing healthcare outreach effectiveness using a rolling matching methodology. The code simulates and analyzes the impact of different intervention programs on physical checkup completion rates.

## 🎯 Key Features

- **Data Simulation**: Generates realistic synthetic healthcare data
- **Rolling Matching Technique**: Advanced matching methodology to compare intervention and control groups
- **Multi-Program Analysis**: Evaluates three different outreach programs
- **Comprehensive Visualization**: Generates bar charts and trend line plots
- **Detailed Statistical Analysis**: Calculates completion rates and intervention lift

## 🧰 Technologies Used

- Python
- NumPy
- Pandas
- Scikit-Learn
- Matplotlib
- Seaborn

## 🔍 Methodology: Rolling Matching

The rolling matching approach allows for:
- Time-varying treatment assignment
- Dynamic matching of intervention and control groups
- Accounting for non-random outreach patterns

### Key Analysis Steps
1. Simulate patient data with varying characteristics
2. Generate outreach and completion histories
3. Perform nearest-neighbor matching
4. Calculate completion rates and intervention effects

## 📈 Output Files

The script generates:
- `physical_checkup_completion_rates.csv`: Summary statistics
- `Physical_Checkup_Completion_Rates_By_Program.png`: Comparative bar chart
- `Monthly_Physical_Checkup_Completion_Rates.png`: Monthly trend visualization

## 🚀 How to Use

### Prerequisites
- Python 3.8+
- Required libraries: numpy, pandas, scikit-learn, matplotlib, seaborn

### Installation
```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

### Running the Analysis
```bash
python rolling_matching_analysis.py
```

## 📊 Example Results

The analysis compares three healthcare outreach programs (A, B, C) across multiple months, demonstrating:
- Intervention group completion rates
- Control group completion rates
- Performance lift for each program

## 🔬 Customization

Easily modify:
- Simulation parameters
- Number of matches
- Matching variables
- Outreach probability function

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## 📄 License

MIT License - See LICENSE.md for details

## 🎓 Citation

If you use this code in academic research, please cite:
- Your Name
- "Rolling Matching Analysis in Healthcare Outreach" (Year)

## 💡 Disclaimer

This is a simulation-based research tool. Always validate healthcare interventions with real-world data and professional medical guidance.

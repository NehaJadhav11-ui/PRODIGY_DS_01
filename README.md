# Task_1
Histogram to visualize the distribution of variable
Age and Gender Distribution Analysis - Data Visualization

This mini-project visualizes the age distribution across gender categories using a histogram. It provides insights into demographic structure based on age and gender from a given dataset.

Dataset

Dataset used: age_gender.csv  
Location used: `archive (2)/age_gender.csv`  
Contains:
- `age`: Age of individuals
- `gender`: Encoded as 0 (Male) and 1 (Female)

Task Overview

- Loaded and cleaned the dataset
- Removed records with age > 100
- Mapped gender values from 0/1 to 'Male'/'Female'
- Plotted histogram showing age distribution by gender using seaborn

Visualization Details

- Histogram using `seaborn.histplot`
- Age grouped into 30 bins
- Gender visualized using color separation (`hue='gender'`)
- Palette: Set2 (for aesthetic separation)

Technologies Used

- Python
- pandas
- seaborn
- matplotlib

How to Run

1. Clone the repository or copy the notebook/code
2. Ensure `age_gender.csv` is placed in the correct path
3. Run the script or notebook

License

This project is licensed under the MIT License.

Contact

For feedback or questions, feel free to reach out via email or LinkedIn.

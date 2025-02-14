# Hurricane Data Analysis - Categorizing Hurricanes by Damage

## Overview
This project analyzes historical hurricane data and categorizes hurricanes based on their financial damage. The analysis helps in understanding the economic impact of hurricanes and provides insights for disaster preparedness, insurance modeling, and climate studies.

## Analysis Breakdown
### 1. Converting Damage Values
- Raw damage values (e.g., `"100M"`, `"1.42B"`, `"Damages not recorded"`) are converted into numerical format for consistency and analysis.

### 2. Assigning Hurricanes to Damage Categories
- Hurricanes are classified using a predefined **damage scale**:
  - **Rating 0**: No recorded damage
  - **Rating 1**: $0 < damage ≤ $100M
  - **Rating 2**: $100M < damage ≤ $1B
  - **Rating 3**: $1B < damage ≤ $10B
  - **Rating 4**: $10B < damage ≤ $50B
  - **Rating 5**: damage > $50B

### 3. Storing and Analyzing the Data
- Hurricanes are grouped into a dictionary where the keys represent **damage ratings** and the values are lists of hurricanes falling into each category.
- The distribution of hurricanes across damage categories is printed to provide insights into the financial impact of hurricanes over time.

## Key Insights
- Many hurricanes have **no recorded damage**, highlighting gaps in historical data.
- Most hurricanes fall into the **lower damage categories** (Ratings 1 and 2).
- A few extreme hurricanes caused **over $50 billion in damages**, showcasing their devastating economic impact.

## Next Steps
- Visualizing the hurricane damage distribution using **matplotlib or seaborn**.
- Expanding the analysis to include **hurricane frequency trends over time**.
- Integrating **wind speed and mortality ratings** for a more comprehensive classification.

## How to Use
1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/hurricane-analysis.git
   cd hurricane-analysis
   ```
2. Run the analysis script:
   ```sh
   python hurricane_analysis.py
   ```
3. View categorized hurricane data and insights.

## Contributing
Contributions are welcome! If you have ideas for improvement, feel free to submit a pull request.

## License
This project is licensed under the MIT License.



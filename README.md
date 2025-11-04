# Dzaleka Refugee Camp Data Analysis Project

## Overview
This GitHub repository contains Jupyter notebooks analyzing key aspects of refugee life in the Dzaleka Refugee Camp, located in Dowa, Malawi. The project focuses on three main areas:
- **Assistance Distribution**: Preferences for humanitarian aid in the form of food, money, or a combination.
- **Durable Solutions**: Refugee preferences for long-term solutions such as resettlement, citizenship, or repatriation.
- **Water Fetching**: Patterns of water collection, including frequency and volume by area within or near the camp.

These analyses are based on sample datasets collected from camp participants, aiming to provide insights for humanitarian organizations, policymakers, and researchers to improve support and resource allocation. All data is anonymized and focuses on aggregate trends.

## Repository Structure
- **`assistance_distribution.ipynb`**: Notebook analyzing preferences for food and/or monetary assistance among refugees.
- **`duration_solution.ipynb`**: Notebook exploring preferred durable solutions (resettlement, citizenship, repatriation) by nationality.
- **`water_fetching.ipynb`**: Notebook examining water fetching habits, including containers per day, days per week, and a pie chart visualization of monthly contributions by area.
- **`README.md`**: This file providing project documentation.

## Data Sources
The datasets are derived from surveys or records of refugees in Dzaleka Refugee Camp. Key highlights:
- **Assistance Distribution**: Includes participant names (anonymized) and preferences (e.g., "Food", "Money", "Food plus money").
- **Durable Solutions**: Maps nationalities (e.g., Congo, Burundi, Rwanda) to preferred solutions (e.g., Resettlement, Rapatriation, Citizenship).
- **Water Fetching**: Covers areas (e.g., Karonga, Likuni) with metrics like containers fetched per day and days per week, culminating in monthly estimates.

Note: These are sample datasets for demonstration. Real-world data should be handled with privacy and ethical considerations in line with UNHCR guidelines.

## Installation and Usage
### Prerequisites
- Python 3.x
- Jupyter Notebook or JupyterLab
- Required libraries: `pandas`, `matplotlib` (install via `pip install pandas matplotlib`)

### Running the Notebooks
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/dzaleka-refugee-analysis.git
   cd dzaleka-refugee-analysis
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt  # If a requirements file is added, otherwise install pandas and matplotlib manually
   ```
3. Launch Jupyter:
   ```
   jupyter notebook
   ```
4. Open and run any `.ipynb` file in your browser.

Each notebook includes code for loading data, basic analysis (e.g., dataframes and visualizations), and sample outputs like tables and charts.

## Key Insights from Analyses
- **Assistance Distribution**: Most participants prefer food-based aid, with some opting for combined food and money support. This highlights the need for flexible assistance programs.
- **Durable Solutions**: Preferences vary by nationality; for example, Congolese refugees often favor resettlement, while others lean toward citizenship or repatriation. This can inform advocacy and policy efforts.
- **Water Fetching**: Areas like Zomba show higher daily container needs (e.g., 6 containers/day, 3 days/week), indicating potential water access disparities. The pie chart visualizes percentage contributions to monthly water fetching totals.

## Contributing
Contributions are welcome! If you have additional data, improved analyses, or visualizations, please:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/new-analysis`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature/new-analysis`).
5. Open a Pull Request.

Ensure all contributions respect data privacy and focus on humanitarian impact.

## License
This project is licensed under the MIT License.

## Contact
For questions or collaborations, contact [jospinamissi@gmail.com]. This project is inspired by efforts to support refugees in Malawi and beyond.

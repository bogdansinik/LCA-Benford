# LCA-Benford

This repository provides data and R scripts for analyzing Life-Cycle Assessment (LCA) databases using Benford's Law. It aims to evaluate data quality by testing the conformity of numeric data in the database against the expected distribution defined by Benford's Law. The repository also includes visualizations to aid in interpreting the results.

## Features

The repository supports the following analyses:

1. **Test Whole Database for Conformity**
   - Analyze the entire dataset to determine its overall compliance with Benford’s Law.

2. **Test Each Column for Conformity**
   - Evaluate individual columns in the database for adherence to Benford’s Law.

3. **Test Conformity by Country**
   - Assess data conformity for each country represented in the dataset.

4. **Test Conformity by Compartment**
   - Analyze specific compartments or categories within the dataset for compliance.

5. **Test Conformity by Continent**
   - Examine data conformity aggregated by continent.

## Visualizations

The script generates comprehensive visualizations for each of the analyses listed above. These visualizations help identify geographic and categorical variations in the dataset's conformity to Benford’s Law.

## Research Context

This repository was developed as part of the research study, **"Testing Life-Cycle Assessment Data Quality with Benford’s Law Reveals Geographic Variations"**, in collaboration with my mentor, Aleksandar Tošić. The study investigates geographic and categorical variations in data quality across LCA databases.

## Repository Structure

```
LCA-Benford/
├── data/                # Contains raw and processed LCA database files
├── scripts/             # R scripts for analyses and visualizations
├── results/             # Output files and generated visualizations
└── README.md            # Repository documentation
```

## Requirements

To run the analyses, the following tools and libraries are required:

- **R** (Version 4.0 or later)
- Key R libraries:
  - `stats`
  - `tidyverse`
  - `readxl`
  - `benford.analysis`
  - `ggplot2`
  - `dplyr`
  - `readr`
  - `countrycode`
  - `patchwork`

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/LCA-Benford.git
   cd LCA-Benford
   ```

2. Install the required R libraries:
   ```R
   install.packages(c("tidyverse", "benford.analysis", "ggplot2", "dplyr", "readr"))
   ```

3. Run the R scripts in the `scripts/` directory to perform the analyses and generate visualizations.

4. Results and visualizations will be saved in the `results/` directory.

## Contributing

Contributions to this repository are welcome. Please open an issue or submit a pull request for any suggestions, bug fixes, or enhancements.

## Acknowledgments

Special thanks to Aleksandar Tošić for mentorship and collaboration throughout this research.

---

For any inquiries or further information, please contact me via [email](mailto:bogdan.sinik@famnit.upr.si) or open an issue in this repository.

# Ontario Rental Market Data Analysis Using Machine Learning

## Project Overview
This project analyzes rental market data from small communities in Ontario using machine learning techniques. The analysis focuses on uncovering insights about property types, rental prices, amenities, and spatial distribution to inform decision-making in the rental market.

## Project Phase: Exploratory Data Analysis (EDA) and Visualization
- **Duration**: January 2024 - April 2024
- **Dataset Source**: Kijiji
- **Dataset Features**: 25,732 rows and 18 columns covering attributes like property type, price, size, location, and more.

## Key Accomplishments
### Data Preparation
- **Data Cleaning**:
  - Removed irrelevant columns (e.g., `CSDUID`, `Title`, `Location`, `adId`, `URL`, etc.).
  - Cleaned the `Price` column by removing currency symbols.
  - Extracted numerical values from `Bedrooms` and `Bathrooms`.
  - Handled missing and invalid values (e.g., imputation for `Size` and outlier removal).
  - Converted categorical columns to the appropriate data type.
  - Transformed binary attributes (`Hydro`, `Water`, `Heat`) into numerical equivalents.

### Exploratory Data Analysis (EDA)
1. **Bar Charts**:
   - Visualized property types distribution and popular amenities by region.
2. **Pie Charts**:
   - Analyzed the composition of rental properties by type within each region.
3. **Scatter Plots**:
   - Explored the relationship between property size and rental price.
4. **Heat Maps**:
   - Mapped the spatial density of rental properties across Ontario.

## Challenges Encountered
- **Handling Outliers**: Addressed unrealistic property sizes to maintain data integrity.
- **Managing Missing Data**: Applied various imputation techniques.
- **Standardizing Data Types**: Ensured consistency across all features.

## Tools and Technologies
- **Programming**: Python
- **Libraries**: Pandas, NumPy, Matplotlib
- **Visualization**: Looker Studio
- **References**: Notable resources include works by Lemenkova (2019), Raschka et al. (2020), and Waskom (2021).

## Future Work
- Extend analysis to predictive modeling for rental price estimation.
- Incorporate additional datasets to improve the robustness of findings.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ontario-rental-analysis.git

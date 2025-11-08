# BMW Sales Analysis Dashboard

## Project Overview

This project provides a comprehensive analysis of BMW car sales data across multiple regions and years. The analysis includes data cleaning, aggregation, visualization, and insights generation, with results exported to an interactive Excel dashboard.

## 📊 Project Description

The BMW Sales Analysis Dashboard is designed to help understand sales patterns, trends, and key performance indicators for BMW vehicles. It processes raw sales data and transforms it into meaningful insights through:

- **Data Cleaning**: Verification of data quality, handling missing values and duplicates
- **Statistical Analysis**: Calculation of key metrics and aggregations
- **Visual Analytics**: Creation of professional charts and graphs
- **Dashboard Creation**: Export to Excel with formatted sheets and embedded visualizations
- **Insights Generation**: Identification of trends, top performers, and growth patterns

## 📁 Dataset Information

### Data Source
- **File**: `BMW_sales.csv`
- **Size**: 1000 rows × 11 columns
- **Period**: 2013-2024

### Data Columns

| Column Name | Type | Description |
|-------------|------|-------------|
| Model | String | BMW model name (e.g., 5 Series, X5, i8) |
| Year | Integer | Year of sale (2013-2024) |
| Region | String | Geographic sales region |
| Color | String | Vehicle color |
| Fuel_Type | String | Type of fuel (Petrol, Diesel, Electric, Hybrid) |
| Transmission | String | Transmission type (Automatic, Manual) |
| Engine_Size_L | Float | Engine size in liters |
| Mileage_KM | Integer | Vehicle mileage in kilometers |
| Price_USD | Integer | Vehicle price in USD |
| Sales_Volume | Integer | Number of units sold |
| Sales_Classification | String | Sales category (High, Medium, Low) |

### Data Characteristics

- **No Missing Values**: The dataset is complete with no null values
- **No Duplicates**: Each record is unique
- **Clean Data**: All fields are properly formatted and validated

## 🛠️ Technology Stack

### Required Libraries
```python
- pandas (1.5+)          # Data manipulation and analysis
- numpy (1.23+)          # Numerical computations
- matplotlib (3.6+)      # Data visualization
- openpyxl (3.0+)        # Excel file handling
```

### Python Version
- Python 3.8 or higher recommended

## 📈 Analysis Features

### 1. Data Quality Checks
- Missing value detection
- Duplicate identification
- Basic statistical summaries
- Data type validation

### 2. Aggregations & Metrics
- **Regional Analysis**: Total sales and revenue by region
- **Model Performance**: Sales volume and average price by model
- **Temporal Trends**: Year-over-year growth analysis
- **Fuel Type Analysis**: Sales distribution and average mileage by fuel type
- **Transmission Preferences**: Sales patterns by transmission type

### 3. Key Insights Generated

#### Business Intelligence Insights:
1. **Top Performing Regions**: Identifies highest revenue-generating markets
2. **Best Selling Models**: Ranks models by sales volume
3. **Price Analysis**: Average pricing by model segment
4. **Color Preferences**: Most popular colors for each model
5. **Fuel Type Trends**: Adoption patterns of different fuel technologies
6. **Growth Metrics**: Year-over-year sales growth percentages
7. **Market Segmentation**: Distribution of high, medium, and low sales classifications

### 4. Visualizations

The project generates 6 professional-grade charts:

1. **Sales Distribution Pie Chart**
   - Shows percentage share by region
   - Exploded view for top region
   - BMW brand colors

2. **Top Models Bar Chart** 
   - Horizontal bar chart of top 5 models
   - Improved axis scaling for better comparison
   - Value labels on bars

3. **Fuel Type Trend Line Chart**
   - Multi-line chart showing trends over years
   - Different colors for each fuel type
   - Grid for easy reading

4. **Revenue by Region Bar Chart**
   - Vertical bars showing total revenue
   - Values displayed in millions USD
   - Clear labeling

5. **Sales Classification Donut Chart**
   - Donut-style pie chart
   - Distribution of high/medium/low sales
   - Clean, modern design

6. **Average Price Comparison**
   - Horizontal bar chart
   - Price in thousands for readability
   - Top 7 models featured

### 5. Excel Dashboard

The final deliverable is a professional Excel workbook with three sheets:

#### Sheet 1: Cleaned Data
- Complete dataset with all columns
- Auto-adjusted column widths
- Ready for further analysis

#### Sheet 2: Visual Dashboard
- Title banner
- All 6 charts embedded
- Professional layout (2×3 grid)
- High-resolution images (300 DPI)

#### Sheet 3: Summary Statistics
- Key Performance Indicators (KPIs)
- Total sales volume
- Total revenue
- Average metrics
- Top performers
- Growth rates

## 🚀 How to Use

### Installation

1. **Clone or Download the Project**
```bash
cd "path/to/project"
```

2. **Install Required Packages**
```bash
pip install pandas numpy matplotlib openpyxl
```

### Running the Analysis

1. **Ensure Data File is Present**
   - Verify `BMW_sales.csv` is in the project directory

2. **Run the Script**
```bash
python bmw_sales_analysis.py
```

3. **Check Output Files**
   - The script will create:
     - `BMW_Sales_Dashboard_Clean.xlsx` (Excel dashboard)
     - 6 PNG image files (visualizations)

### Customization

You can customize the analysis by modifying:

- **Color Scheme**: Edit `BMW_COLORS` list in the script
- **Chart Types**: Modify plotting functions
- **Metrics**: Add new aggregations in Section 3
- **Insights**: Add custom analysis in Section 3
- **Excel Layout**: Adjust chart positions in Section 5

## 📊 Key Findings (Sample)

Based on the analysis of the data:

- **Top Region by Sales**: Asia leads with the highest sales volume
- **Best Selling Model**: The 5 Series is the top performer
- **Revenue Leader**: North America generates highest revenue
- **Fuel Preference**: Petrol vehicles dominate, but electric is growing
- **Price Range**: Models range from ~$50K to ~$115K average price
- **Growth Trend**: Positive year-over-year growth observed
- **Transmission**: Automatic transmission strongly preferred

## 🎨 Design Features

- **BMW Brand Colors**: Charts use BMW's signature blue palette
- **Professional Styling**: Clean, corporate design aesthetic
- **Readability**: Large fonts, clear labels, and legends
- **High Resolution**: 300 DPI exports for print quality
- **Consistent Theming**: Unified design across all visualizations

## 📋 Project Structure

```
Project/
│
├── BMW_sales.csv                    # Input data file
├── bmw_sales_analysis.py            # Main analysis script
├── README.md                        # This file
│
├── Generated Files:
│   ├── BMW_Sales_Dashboard_Clean.xlsx
│   ├── chart1_region_sales_pie.png
│   ├── chart2_top_models_bar.png
│   ├── chart3_fuel_type_trend.png
│   ├── chart4_revenue_by_region.png
│   ├── chart5_classification_donut.png
│   └── chart6_avg_price_by_model.png
```

## 🔧 Troubleshooting

### Common Issues:

1. **Module Not Found Error**
   - Solution: Install missing packages using pip

2. **File Not Found Error**
   - Solution: Ensure BMW_sales.csv is in the same directory

3. **Excel File Won't Open**
   - Solution: Close any open instances of the Excel file

4. **Charts Not Showing in Excel**
   - Solution: Verify PNG files were created successfully

## 💡 Future Enhancements

Potential improvements for future versions:

- [ ] Interactive Plotly dashboards
- [ ] Time series forecasting
- [ ] Customer segmentation analysis
- [ ] Market basket analysis
- [ ] Web-based dashboard using Dash or Streamlit
- [ ] Automated report generation
- [ ] Email delivery of reports
- [ ] Real-time data updates

## 👨‍💻 Author

Created by: [Your Name]
Date: 2024
Contact: [Your Email]

## 📝 License

This project is for educational and analytical purposes.

## 🙏 Acknowledgments

- Data analysis performed using pandas and numpy
- Visualizations created with matplotlib
- Excel integration via openpyxl
- Inspired by BMW's commitment to excellence and innovation

---

## Quick Start Guide

### For Non-Technical Users:

1. Open the generated Excel file: `BMW_Sales_Dashboard_Clean.xlsx`
2. Navigate between sheets:
   - **Sheet 1**: View raw data
   - **Sheet 2**: See visual dashboard
   - **Sheet 3**: Review summary statistics

### For Developers:

1. Review the code sections:
   - Section 1: Data loading
   - Section 2: Aggregations
   - Section 3: Insights
   - Section 4: Visualizations
   - Section 5: Excel export

2. Modify as needed for your use case

3. Run and generate updated outputs

---

**Last Updated**: November 2024

For questions or support, please refer to the code comments or contact the author.

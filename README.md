# Blinkit Sales Analysis

![Project Pipeline](https://github.com/dhyeymodi2001/Blinkit-Sales-Analysis/blob/main/Screenshots/image.png)

## Project Overview
This project is an end-to-end data analysis of Blinkit outlet sales data. It involves data extraction, cleaning, storage, visualization, and predictive modeling to optimize outlet performance and inventory management. The analysis was conducted using Python, MySQL, Power BI, and Machine Learning techniques.

## Workflow
1. **Data Acquisition:**
   - **Source**: Blinkit outlet sales dataset
   - **Method**: Direct data extraction from Blinkit dataset
   
2. **Setting Up Environment:**
   - **Tools Used**: Python, Jupyter Notebook, MySQL, Power BI
   - **Install Dependencies**:
     ```bash
     pip install pandas numpy sqlalchemy pymysql seaborn matplotlib scikit-learn
     ```

3. **Data Cleaning & Preprocessing:**
   - Removed duplicate records to ensure data accuracy
   - Handled missing values to prevent inconsistencies
   - Converted categorical variables into numerical format
   - Formatted price and sales columns for analysis

4. **Storing Cleaned Data in MySQL:**
   - Used `pymysql` and `SQLAlchemy` to store structured data in MySQL
   - Enabled efficient querying for sales insights

5. **Exploratory Data Analysis (EDA) & Visualization:**
   - Created sales trend graphs, heatmaps, and distribution plots using:
     ```python
     import matplotlib.pyplot as plt
     import seaborn as sns
     ```
   - Identified top-selling products, peak hours, and outlet performance

6. **Predictive Modeling & Advanced Analytics:**
   - **Sales Prediction Model**: Trained a regression model to predict sales for new outlets
   - **Product Demand Clustering**: Used K-Means clustering to segment outlets based on sales patterns
   - **Market Basket Analysis**: Applied the Apriori algorithm to identify frequently bought-together products

7. **Interactive Dashboard in Power BI:**
   - Designed a dashboard to visualize key performance metrics like revenue, order volume, and product demand
   - Utilized DAX measures to enhance business intelligence

## Project Structure
```plaintext
|-- BlinkIT Grocery Data.xlsx/                # Raw and processed data
|-- Blinkit_Sales_Dashboard.pbix              # PowerBI Dashboard
|-- README.md                                 # Project documentation
|-- requirements.txt                          # Python dependencies
|-- project.ipynb                             # Main data processing script
```

## Key Insights
- Identified top-performing Blinkit outlets based on revenue and order volume
- Predicted sales for new locations to optimize store expansion strategy
- Discovered frequently purchased item combinations to improve inventory placement
- Analyzed outlet-wise peak sales hours for better operational efficiency

## Future Enhancements
- Automate data pipeline for real-time updates
- Expand analysis with external datasets for deeper insights
- Integrate customer sentiment analysis based on reviews (if available)

## Getting Started
1. Clone the repository:
   ```bash
   git clone <repo-url>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up MySQL and import data
4. Run Jupyter Notebook for analysis

## Tools & Technologies Used
- **Data Processing:** Python, Pandas, NumPy
- **Database Management:** MySQL
- **Data Visualization:** Matplotlib, Seaborn, Power BI
- **Machine Learning:** Scikit-learn (Regression, Clustering, Market Basket Analysis)
- **Development Environment:** Jupyter Notebook, VS Code

## Conclusion
The Blinkit Sales Analysis project provides actionable insights into outlet performance, customer purchasing behavior, and sales forecasting. By leveraging Power BI for visualization and machine learning for predictive analytics, the project helps optimize store expansion, inventory management, and revenue growth. Future enhancements such as automation and real-time data integration can further improve decision-making capabilities.

![Project Dashboard](https://github.com/dhyeymodi2001/Blinkit-Sales-Analysis/blob/main/Screenshots/BlinkIt%20Dashboard.png)


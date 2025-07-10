
# Sales & Customer Behaviour Insights – Green Cart Ltd.

## Project Overview

This project presents a structured data analysis of Green Cart Ltd.'s sales and customer behaviour using Python and industry-standard libraries. The goal is to derive actionable insights from historical sales, customer, and product datasets to support strategic decisions in areas like promotions, customer loyalty, and delivery performance.

The analysis covers:
- Revenue trends by product category and region  
- Customer segmentation based on loyalty tiers  
- Effects of discounts on quantity sold  
- Delivery delays by customer region  
- Signup timing and purchasing patterns  

## Tools & Libraries Used

This project was developed using the following tools and Python libraries:

- **Python** 3.10+
- **Jupyter Notebook** – for interactive analysis and visualisations
- **pandas** >= 1.5.0 – for data manipulation and analysis  
- **numpy** >= 1.21.0 – for numerical operations  
- **matplotlib** >= 3.5.0 – for static visualisations  
- **seaborn** >= 0.11.2 – for enhanced statistical plots  
- **ipython** >= 8.0.0 – for improved interactive notebook experience


## Key Features

- Data Cleaning: Standardised text fields, corrected typos, removed duplicates, handled missing values.
- Feature Engineering: Created variables for revenue, order week, price bands, delivery lateness, email domain, and time to order.
- Visual Analysis: Heatmaps, bar plots, line plots, and segmentation charts.
- Business Questions Answered: Supported by clean tables and visual outputs.
- Recommendations: Clear, data-backed suggestions based on insights.

## Key Insights

- "Cleaning" category alone drives the largest share of revenue across all regions.
- "Gold" loyalty tier customers generate the most revenue and highest order volume.
- Discounts don’t increase items per transaction but drive higher overall sales volume.

## How to Run the Project

1. Clone the repository:
   git clone https://github.com/Samuel-Cantarero/sales-customer-behaviour-insights.git
   cd sales-customer-behaviour-insights

2. Create and activate a virtual environment (optional but recommended):
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install required packages:
   pip install -r requirements.txt

4. Open the notebook:
   Launch Jupyter and open `notebook/green_cart_analysis.ipynb`, then run all cells in order.

## Author

Antonio Samuel Cantarero Malagón  
GitHub: https://github.com/Samuel-Cantarero

## License

This project is for educational and academic purposes only. All data used is anonymised and synthetic.

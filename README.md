
# SaaS Opportunity Compass 

[](https://www.python.org/) [](https://pandas.pydata.org/) [](https://plotly.com/studio/) [](https://opensource.org/licenses/MIT)

**A market intelligence dashboard that analyzes thousands of product launches to identify underserved, high-growth niches in the SaaS market.**



##  Live Demo 

**You can view and interact with the live, deployed dashboard at the following URL:**

### ➡️ **[https://e394127a-d32e-4c23-82a1-d062b190f56c.plotly.app](https://e394127a-d32e-4c23-82a1-d062b190f56c.plotly.app)**


-----

## About The Project

In the crowded Software as a Service (SaaS) market, finding a genuine opportunity is like finding a needle in a haystack. This project was built to solve that problem. The **SaaS Opportunity Compass** is a strategic tool for venture capitalists and startup founders that moves beyond gut feeling. By analyzing real-world launch data from Product Hunt, this dashboard provides a data-driven view of the competitive landscape, enabling users to spot market gaps and make smarter investment decisions.

This project was created for the **Plotly Studio Hackathon**.

### Key Features:

  * **Market Saturation Analysis:** A treemap visualizes which markets are crowded versus which are highly-rated by users.
  * **Opportunity Matrix:** A scatter plot identifies emerging niches by mapping market growth against competition.
  * **Dynamic Filtering:** The entire dashboard can be filtered to drill down into specific categories or market segments.
  * **AI-Powered Insights:** The app includes a natural language summary that provides an actionable investment thesis based on the data.

-----

## The Workflow

This project was built following a standard data analytics workflow:

1.  **Data Sourcing:** Raw data containing thousands of product launches from 2020 and 2021 was sourced from a [Product Hunt dataset on Kaggle](https://www.kaggle.com/datasets/undefinenull/product-hunt).
2.  **Data Cleaning & Feature Engineering:** The raw data was processed in a Python script using the Pandas library. This critical step involved:
      * Standardizing inconsistent category names.
      * Converting data types to ensure accurate calculations.
      * Engineering the key metric for the analysis: **Year-over-Year (YoY) Growth Rate** for each product category.
3.  **Dashboard Development:** The final `engineered_data.csv` was uploaded to **Plotly Studio**. The interactive dashboard, charts, and filters were all built using natural language prompts.
4.  **Deployment:** The finished application was deployed to **Plotly Cloud** to be shared publicly.

-----

##  Tech Stack

  * **Data Analysis:** Python, Pandas, Google Colab
  * **Dashboard & Deployment:** Plotly Studio, Plotly Cloud
  * **Data Source:** Kaggle

-----

## How To Use

The code in this repository is for the data preparation stage. To replicate this work:

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/your-username/saas-opportunity-compass.git
    ```
2.  **Upload the data** (`2020.csv` and `2021.csv`) to a notebook environment like Google Colab.
3.  **Run the notebook** (`Data_Preparation.ipynb`) to generate the final `engineered_data.csv` file.
4.  This final CSV can then be used in any BI tool, including Plotly Studio, to build the dashboard.

-----

## Acknowledgments

  * Thank you to the **Plotly** team for hosting the hackathon and providing access to Plotly Studio.
  * Data provided by the **Product Hunt** community via Kaggle.

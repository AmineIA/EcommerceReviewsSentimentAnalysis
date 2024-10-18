# Sentiment Analysis of E-commerce Reviews

This project focuses on scraping reviews from e-commerce websites, analyzing the sentiment of these reviews using BERT, and visualizing the results with a Streamlit dashboard. It provides insights into customer feedback to help administrators make data-driven decisions.

## Project Overview
### Features
- **Scraping reviews** from e-commerce websites (Amazon in this example).
- **Sentiment analysis** using a BERT-based model from Hugging Face.
- **Visualization of sentiment distribution** with an interactive Streamlit dashboard.
- **Filtering options** for detailed exploration of positive, negative, or neutral reviews.


## Usage

- **Dashboard Overview**:
  - **View Reviews**: Display the list of reviews and their sentiments.
  - **Sentiment Distribution**: Visualize the proportion of positive, negative, and neutral reviews.
  - **Filter Reviews**: Use the dropdown to filter reviews by sentiment type.

---

## Technologies Used

- **Python**: Core programming language.
- **Selenium**: Web scraping from dynamically loaded pages.
- **BeautifulSoup**: For HTML parsing.
- **Transformers (Hugging Face)**: BERT-based sentiment analysis.
- **Streamlit**: Interactive data visualization.
- **Matplotlib & Seaborn**: Data visualization tools.

---

## Potential Improvements

1. **Support for more e-commerce websites**: Expand scraping logic to handle multiple websites.
2. **Automate scraping**: Use a scheduler like `cron` or `Airflow` for periodic scraping.
3. **Add email notifications**: Send summary reports of sentiment trends automatically to admins.
4. **Enhance the dashboard**: Include additional interactive plots, word clouds, or time-series analysis.

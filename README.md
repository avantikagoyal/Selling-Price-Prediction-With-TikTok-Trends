# TikTok & Mercari Sneakers Sales Analysis

## Project Overview
Our project, "TikTok & Mercari Sneakers Sales Analysis," aimed to develop a predictive model that forecasts the optimal pricing of sneaker brands based on TikTok engagement metrics and second-hand selling prices on Mercari. This model helps companies identify trending products and make informed decisions about promotions or collaborations, maintaining a competitive edge by aligning with the peak interest in trending items.

## Team Members
- Avantika Goyal
- Hillary Hoang
- Sadhanha Anand
- Winnie Chen

## Repository Contents
- `TikTok_and_Mercari_Sneakers_Sales_Analysis.ipynb`: Jupyter notebook containing all the code and models developed.
- `Final_Project_Report.pdf`: Detailed project report outlining the business objectives, methodology, results, and actionable insights.
- `Final_Project_Presentation_Slides.pdf`: Presentation slides summarizing our project and potential next steps.
- `Data/`: Directory containing all the datasets used in this project.

## Business Objective
The main objective was to aid companies in predicting the prices of trending sneakers, leveraging social media metrics from TikTok and pricing trends from Mercari. This prediction enables companies to strategically manage promotions, collaborations, and pricing strategies based on the lifecycle of product trends.

## Methodology
We employed predictive analytics using a Random Forest Regression model, incorporating variables like selling price, discounts, and social media engagement metrics. Detailed analysis was conducted to understand the relationship between TikTok engagement and Mercari selling prices, guiding dynamic pricing strategies.

## Methodology
Our methodology included comprehensive steps: data collection, cleaning, exploratory data analysis (EDA), and predictive modeling using a Random Forest Regression model. To gather the necessary data, we employed web scraping techniques using **Selenium** and **BeautifulSoup**. Selenium was used to automate web browser interaction, allowing us to collect dynamic content from TikTok and Mercari, which rely heavily on JavaScript for content loading. BeautifulSoup was used to parse and extract structured data from the HTML content. After collecting the data, we preprocessed the data to prepare it for analysis. We then conducted EDA to understand the relationships between social media engagement metrics and Mercari selling prices. Finally, we built a predictive model using **Random Forest Regression** to forecast pricing trends effectively, focusing on key variables such as likes, shares, views, listing prices, and selling prices.


## Technologies Used
- **Python** for data manipulation and analysis, utilizing libraries such as Pandas, NumPy, Scikit-learn, Matplotlib, and Seaborn.
- **PySpark** for handling large datasets and performing distributed data processing.
- **Jupyter Notebook** for interactive documentation of our analysis process.

## Results
Our model achieved an 85% accuracy in forecasting optimal prices, demonstrating strong potential for enhancing pricing strategies and marketing efforts. The insights derived from this analysis are intended to help companies tailor their strategies to capitalize on emerging trends and maximize market performance.

## Contributions
Each team member contributed to different facets of the project, from data collection and model development to strategy formulation and report writing. Our collaborative effort ensured a comprehensive approach to solving the business problem.

## Future Work
We plan to refine our predictive model and expand our analysis to include more brands and product types. Ongoing evaluation and adaptation of the model will help maintain its relevance and effectiveness in a rapidly changing market landscape.

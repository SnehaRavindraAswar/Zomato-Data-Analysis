# Zomato-Data-Analysis
Project Overview
This project is an analysis of Zomato data to extract valuable insights using statistical and visualization techniques. The analysis aims to identify key trends in restaurant ratings, customer behavior, and the relationship between various restaurant types and customer preferences.

Objectives
Data Cleaning: Process the raw Zomato dataset by handling missing or incorrect values (e.g., converting rating formats).
Exploratory Data Analysis (EDA): Visualize and understand data relationships through charts and plots.
Statistical Insights: Derive insights about restaurant performance, customer spending behavior, and ordering preferences.
Dataset
The Zomato dataset contains the following key fields:

Restaurant name
Location
Cuisines
Average cost for two people
Rating
Votes
Listed type of restaurant (Dine-out, Café, etc.)
Online order availability
Tools and Libraries
Pandas: For data manipulation and cleaning.
NumPy: For numerical operations and calculations.
Matplotlib & Seaborn: For generating visualizations and understanding patterns.
Key Insights
1. Restaurant Type and Votes
Analysis: Counted and visualized the number of votes received for each type of restaurant.
Insight: Dine-in restaurants have received the highest number of votes, indicating a preference for dining out in person.
2. Ratings Distribution
Analysis: Visualized the distribution of restaurant ratings using a histogram.
Insight: The majority of restaurants received ratings between 3.5 and 4.0, showing that most restaurants are well-rated but not exceptional.
3. Average Spending by Couples
Analysis: Examined the approximate cost for two people across restaurants.
Insight: Most couples prefer restaurants with an approximate cost of around 300 rupees, suggesting an average budget for dining.
4. Online vs Offline Orders and Ratings
Analysis: Compared the ratings of restaurants that accept online orders versus those that do not, using boxplots.
Insight: Restaurants with online orders tend to have higher ratings compared to those accepting only offline orders.
5. Order Mode Preference by Restaurant Type
Analysis: Created a heatmap to show the relationship between restaurant types and their order modes (online or offline).
Insight: Dine-in restaurants primarily accept offline orders, whereas cafés mainly receive online orders. This suggests that customers prefer in-person dining at restaurants but online ordering at cafés.
How to Run
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/zomato-data-analysis.git
Install required libraries:
bash
Copy code
pip install -r requirements.txt
Run the analysis:
bash
Copy code
jupyter notebook zomato_analysis.ipynb
Conclusion
This analysis highlights the preferences of Zomato users, focusing on dining preferences, ratings, and spending habits. The findings can help restaurants optimize their services and understand customer behavior better.

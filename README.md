🍽️ # Zomato Restaurant Data Analysis

 This project performs an exploratory data analysis (EDA) on Zomato’s global restaurant data. The dataset provides insights into restaurants across various countries, including their cuisines, ratings, delivery 
 options, and average costs.

📊 Project Objective

* Perform comprehensive data cleaning and preprocessing.
* Explore categorical and numerical variables.
* Merge and analyze external country code data.
* Visualize restaurant trends globally (e.g., ratings, cuisines, delivery modes).
* Identify valuable business insights from customer feedback and ratings.

📁 Dataset Description

 Main Dataset: zomato.csv
* Column Name	Description
* Restaurant ID	Unique identifier for each restaurant
* Restaurant Name	Name of the restaurant
* Country Code	Numeric country code (to be mapped via external file)
* City	City where the restaurant is located
* Address	Full address of the restaurant
* Locality	Area within the city
* Longitude, Latitude	Geolocation coordinates
* Cuisines	Cuisines served by the restaurant
* Average Cost for two	Cost estimate for two people
* Currency	Currency of the cost
* Has Table booking	Whether the restaurant accepts table bookings (Yes/No)
* Has Online delivery	Availability of online delivery option
* Is delivering now	Real-time delivery status
* Price range	Price tier (1 to 4)
* Aggregate rating	Overall customer rating (0 to 5)
* Rating color, text	Visual and textual representation of rating
* Votes	Number of votes cast for the restaurant
# Country Mapping File: Country-Code.xlsx
* Maps numeric Country Code values to country names.

🛠️ Tools & Libraries Used
 
* Python
* Pandas – Data handling
* NumPy – Numerical operations
* Matplotlib & Seaborn – Data visualization
* Jupyter Notebook – Interactive development

📈 Key Analyses Performed

✅ Data Preprocessing

* Checked for missing values (Cuisines had 9 missing values)
* Merged country codes using an external Excel sheet

📌 Categorical Variable Analysis

 * Has Table booking, Has Online delivery, Rating text, Currency, Country explored using bar plots and pie charts

🔢 Numerical Variable Analysis

 * Explored Aggregate rating, Votes, Average Cost for two via descriptive statistics and distributions

🌍 Country-Based Insights

 * India, USA, and UK had the highest number of restaurants
 * Pie chart of restaurant distribution by top 3 countries

⭐ Rating Insights

 * Highest ratings concentrated around specific price tiers
 * Ratings of 0 (unrated) observed – important for cleaning or filtering
 * Color-coded rating summaries grouped and visualized

📊 Sample Visualizations

* Pie chart of restaurant distribution across countries
* Count plot of rating colors
* Bar plots of votes and average cost vs. rating
* Heatmap of missing values

🧠 Key Findings

* India accounts for 94.39% of the dataset.
* Most restaurants do not offer online delivery or table booking.
* The majority of rated restaurants fall in the "Very Good" and "Excellent" categories.
* Price range does not always correlate with higher ratings.


📌 Future Improvements

* Add NLP analysis of customer reviews (if available).
* Create a dashboard using Plotly Dash or Streamlit.
* Incorporate clustering for restaurant segmentation.

📬 Contact

* For questions or suggestions, feel free to connect:

📧 Email: 2010prabhavgupta@gmail.com

💼 LinkedIn: in/prabhav91

 © 2025 | Zomato Data Analysis by [TheMLengineer07]











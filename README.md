🎬 Movie Revenue Prediction – Simple Linear Regression

This project applies Simple Linear Regression to analyze the relationship between Marketing Spend (Cr) and Box Office Revenue (Cr).
The goal is to predict movie revenue based on marketing investment.

📂 Dataset Overview

Rows: 200+ movies (approx.)

Columns:

Marketing_Spend_Cr → Marketing budget in Crores (₹ Cr)

Box_Office_Revenue_Cr → Box office revenue in Crores (₹ Cr)

⚙️ Instructions to Run
1. Clone Repository
git clone https://github.com/srimidhuna/movie_box_office_revenue.git

cd movie_box_office_revenue

3. Create Virtual Environment
conda create -n revenue python=3.10 -y
conda activate revenue

4. Install Requirements
pip install -r requirements.txt

Open task.ipynb to explore step by step.

🧹 Data Cleaning

Loaded dataset from CSV (Movie_Revenue.csv).

Selected relevant features: Marketing_Spend_Cr (X) and Box_Office_Revenue_Cr (y).

Handled missing/null values (if any).

Converted to numerical types for regression.

📊 Regression Analysis
🔹 Model Training

Used scikit-learn LinearRegression.

Fit model:

X = Marketing Spend

y = Box Office Revenue

🔹 Prediction Example

Predicted revenue for a ₹10 Cr marketing spend:

Predicted Revenue: ₹97.65 Cr

📈 Visualization
Marketing Spend vs Box Office Revenue

Scatter plot with regression line:

Blue dots = Movies (actual data)

Red line = Best Fit Line (predicted relationship)

<img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/401f48ad-1521-4a88-b90d-cd1355a1c81a" />


💡 Insights

There is a positive correlation between marketing spend and box office revenue.

However, the relationship is not very strong → higher spend does not always guarantee success.

Outliers suggest that other factors (actors, story, franchise strength) also play a big role.

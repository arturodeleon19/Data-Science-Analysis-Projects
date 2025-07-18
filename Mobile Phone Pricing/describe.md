📱 Mobile Phone Features & Price Range Prediction
📌 Dataset Overview

This project analyzes a dataset of 2,000 mobile phones with 21 features, including technical specifications (RAM, battery, camera) and binary flags (Bluetooth, 4G, etc.).
The goal is to explore how these features influence a phone’s price range (target variable) and build predictive models.

🔗 Dataset Source: https://www.kaggle.com/datasets/khwaishsaxena/mobile-phone-pricing-dataset

📂 Dataset Description

Key Features
Column Name	   Description	  Data Type	Example   Values
battery_power	Battery capacity (mAh)	Integer	1500, 3000
blue	Bluetooth support (0=No, 1=Yes)	Binary	0, 1
clock_speed	Processor speed (GHz)	Float	1.2, 2.5
dual_sim	Dual SIM support (0=No, 1=Yes)	Binary	0, 1
fc	Front camera megapixels	Float	2.0, 8.0
four_g	4G support (0=No, 1=Yes)	Binary	0, 1
int_memory	Internal storage (GB)	Integer	16, 64
m_deep	Phone thickness (cm)	Float	0.7, 1.0
mobile_wt	Weight (grams)	Integer	150, 180
n_cores	Number of processor cores	Integer	2, 8
pc	Primary camera megapixels	Float	5.0, 12.0
px_height	Pixel resolution height	Integer	800, 1920
px_width	Pixel resolution width	Integer	600, 1080
ram	RAM (MB)	Integer	2000, 4000
sc_h	Screen height (cm)	Float	10.2, 15.5
sc_w	Screen width (cm)	Float	5.5, 7.5
talk_time	Battery life per charge (hours)	Integer	5, 20
three_g	3G support (0=No, 1=Yes)	Binary	0, 1
touch_screen	Touchscreen (0=No, 1=Yes)	Binary	0, 1
wifi	WiFi support (0=No, 1=Yes)	Binary	0, 1
price_range	Target: Price category (0-3)	Categorical	0=Low, 3=Very High

Price Range Encoding:

    0: Low Cost

    1: Medium Cost

    2: High Cost

    3: Very High Cost

🎯 Project Objectives

    Exploratory Data Analysis (EDA)

        Identify correlations between features and price range.

        Compare specs across price tiers (e.g., RAM vs. price).

    Predictive Modeling

        Classify phones into price ranges using algorithms like:

            XGBoost / LightGBM (Gradient Boosting)

        Evaluate model performance with metrics like accuracy and confusion matrices.

🛠️ Tools & Technologies

    Python Libraries:

        pandas (Data Manipulation)

        seaborn / matplotlib (Visualization)

        scikit-learn (ML)

        XGBoost / LightGBM (Gradient Boosting)

    Other Tools:

        Jupyter Notebook (Interactive Analysis)

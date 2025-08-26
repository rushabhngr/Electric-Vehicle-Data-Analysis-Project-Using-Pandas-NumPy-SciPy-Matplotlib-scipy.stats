#  Electric Vehicle Data Analysis (Python)

##  Overview  
This project explores **Electric Vehicle (EV) data** using Python to uncover insights about pricing, performance, efficiency, and market trends. The analysis applies **data wrangling, visualization, and hypothesis testing** to answer practical business and customer-oriented questions.  

##  Dataset  
The dataset (`FEV-data-Excel.xlsx`) includes key EV attributes such as:  
-  Make & Model – Manufacturer and variant details  
-  Price (PLN) – Minimum retail price in Polish złoty  
-  Engine Power (KM) & Torque (Nm) – Performance measures  
-  Battery Capacity (kWh) & Range (WLTP) – Energy and efficiency  
-  Dimensions – Wheelbase, length, width, height  
-  Weight & Load Capacity – Vehicle mass and payload limits  
-  Performance – Top speed, acceleration (0–100 kph), energy consumption  
-  Charging – Max DC charging power  
-  Comfort – Number of seats, doors, boot capacity  

##  Problem Statement  
The goal is to analyze EV specifications and sales-related attributes to:  
- Identify vehicles that meet customer preferences (budget, range, efficiency).  
- Detect outliers in energy consumption.  
- Explore the relationship between battery capacity and driving range.  
- Provide personalized EV recommendations.  
- Statistically compare performance between manufacturers (e.g., Tesla vs. Audi).  

##  Tools & Libraries  
- **Python** – Core analysis  
- **Pandas, NumPy** – Data manipulation  
- **Matplotlib, Seaborn** – Visualization  
- **SciPy** – Hypothesis testing (t-test)  
- **OOP in Python** – EV Recommendation system  

##  Tasks & Analysis  
1. **Customer Filter** – EVs under 350,000 PLN with ≥400 km range, grouped by manufacturer, with average battery capacity calculated.  
2. **Outlier Detection** – Identified vehicles with unusual energy consumption levels.  
3. **Relationship Analysis** – Plotted battery capacity vs. range, deriving performance insights.  
4. **Recommendation System** – Built a Python class to recommend top 3 EVs based on user’s budget, range, and battery capacity preferences.  
5. **Hypothesis Testing** – Conducted a two-sample t-test to compare average engine power of Tesla vs. Audi vehicles.  

##  Key Outcomes  
- Highlighted EVs that best fit customer purchase criteria.  
- Identified outliers for deeper quality/performance checks.  
- Found strong correlation between **battery capacity and range**.  
- Built a recommendation tool to personalize EV selection.  
- Discovered statistical differences in performance between Tesla and Audi.  

##  Impact  
This project demonstrates how **Python and statistical analysis** can turn raw automotive data into insights for:  
- Customer purchase recommendations  
- Manufacturer benchmarking  
- Market strategy design  
- Improving EV adoption through data-driven decisions  

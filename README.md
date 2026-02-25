# **Data Engineering Practice Task 1 – Pandas**<br>

### **Task Overview**<br>
  This project presents an exploratory data analysis (EDA) of the NYC Yellow Taxi dataset, performed entirely using Jupyter Notebook.<br>
  The dataset was processed and analyzed using:<br>
    •	Pandas – Data cleaning and manipulation<br>
    •	Matplotlib – Data visualization<br>
    •	Seaborn – Statistical data visualization<br>
  A structured set of analytical questions was solved using these frameworks to extract meaningful insights from real-world transportation data.<br>

### **Dataset Information**<br>
  •	Source: NYC Yellow Taxi Data API<br>
  •	API Endpoint: https://data.cityofnewyork.us/resource/gi8d-wdg5.json<br>
  •	Type: Trip-level transportation data<br>
  •	Includes:<br>
          a. lpep_pickup_datetime<br>
          b. lpep_dropoff_datetime<br>
          c. store_and_fwd_flag<br>
          d. ratecodeid<br>
          e. pickup_longitude<br>
          f. pickup_latitude<br>
          g. dropoff_longitude<br>
          h. dropoff_latitude<br>
          i. passenger_count<br>
          j. trip_distance<br>
          k. fare_amount<br>
          l. extra<br>
          m. mta_tax<br>
          n. tip_amount<br>
          o. tolls_amount<br>
          p. improvement_surcharge<br>
          q. total_amount<br>
          r. payment_type<br>
          s. trip_type<br>
  This dataset contains detailed records of taxi trips in New York City.<br>

### **Tools & Technologies Used**<br>

  **Tool              Purpose**<br>
  Python            Programming language<br>
  Jupyter Notebook	Development and analysis environment<br>
  Pandas	          Data processing and analysis<br>
  Matplotlib	      Basic plotting<br>
  Seaborn	Advanced  Statistical visualizations<br>

### **Task Workflow (Executed in Jupyter Notebook)**<br>

  1️. **Data Loading**<br>
    •	Retrieved dataset from the NYC Yellow Taxi Data API<br>
    •	Loaded into a Pandas DataFrame inside Jupyter Notebook<br>
  
  2️. **Data Cleaning & Preparation**<br>
    •	Handled missing values<br>
    •	Converted datetime columns<br>
    •	Removed invalid records<br>
    •	Created new derived features (hour, day, trip duration, etc.)<br>
  
  3️. **Exploratory Data Analysis (EDA - Based on Real World Questions)** <br>
    a)	When do people take taxis the most?<br>
    b)	How long do taxi trips usually take?<br>
    c)	Do longer trips always mean higher fares?<br>
    d)	Which payment type generate the most revenue?<br>
    e)	Do passengers tip more for longer or shorter trips?<br>
    f)	Which payment type is most popular?<br>
    g)	Do more passengers mean higher fares?<br>
    h)	Vendor performance comparison<br>
  
  4. **Visual based Data Analysis** <br>
    a)	Line Plot:  How does the number of trips change over time (hourly or daily)?<br>
    b)	Histogram: What is the distribution of trip distance and total amount?<br>
    c)	Box Plot: How does fare amount vary by payment type or passenger count?<br>
    d)	Scatter Plot: Is there a linear relationship between distance and fare?<br>
    e)	Pie Chart: What proportion of trips use each payment type?<br>
    f)	Heatmap: At what hours and days is demand highest?<br>
    g)	Area Plot: How does cumulative revenue grow throughout the day?<br>
    h)	Stacked Bar Chart: How much of the fare is made up of taxes, tolls, tips, and base fare?<br>

### **Key Analysis Performed**<br>

•	Identified peak demand hours<br>
•	Calculated average trip fare<br>
•	Analyzed relationship between trip distance and fare<br>
•	Evaluated payment method distribution<br>
•	Examined revenue trends across time


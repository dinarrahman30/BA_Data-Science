# British Airways - Data Scientist

![British Airways](https://media.cntraveler.com/photos/577fcc03e0b5a6244f4c789c/16:9/w_2560%2Cc_limit/BritishAirways-Boeing777-AlamyF1KW8J.jpg)

## British Airways Customer Feedback Analysis

### Background
British Airways (BA) is the flag carrier airline of the United Kingdom (UK). Every day, thousands of BA flights arrive to and depart from the UK, carrying customers across the world. Whether it’s for holidays, work or any other reason, the end-to-end process of scheduling, planning, boarding, fuelling, transporting, landing, and continuously running flights on time, efficiently and with top-class customer service is a huge task with many highly important responsibilities.

As a data scientist at BA, it will be your job to apply your analytical skills to influence real life multi-million-pound decisions from day one, making a tangible impact on the business as your recommendations, tools and models drive key business decisions, reduce costs and increase revenue.

### Problems Statement
Understanding customer feelings, needs and feedback is essential to improving business and providing top-class customer service. British Airways is interested in analyzing customer review data to uncover insights about the airline. 

### Objectives
The main objectives of this project are,
1. Scrape data from the Skytrax website to get passenger reviews about British Airways. after that clean the data for analysis.
2. analyze cleaned data to find insights through sentiment analysis, wordcloud, and modeling.
3. Create PowerPoint slides containing data modeling results and metrics to summarize the main findings of the analysis, along with clear and concise explanations.
   
### Data
The dataset used was collected from the website [Skytrax.com](https://www.skytrax.com), using the web scraping method. After getting the data, the data just needs to be cleaned and prepared for analysis.

##### Feature
* `Reviews`: contains reviews from passengers

### Resource
##### Main Resource
| Resource    | Function | 
|:-------------|:------|
| Website Skytrax.com     |  for customer review data  | 
| Jupyter Notebook/Google Colab | For IDE |
| Python        | a high-level programming language that is interpreted and known to be used for machine learning and data analysis   | 
| PowerPoint Slide        |  for presenting the results and recommendations   | 

##### Library Python
| Library Python | Function | 
|:------------|:-------------|
| Numpy        | For scientific computation  |
| Pandas       | For data manipulation       |
| matplotlib and seaborn    | For visualization |
| OS | to provide an interface for interacting with the operating system |
| shutil | to provide high-level functionality for copying and deleting files and directories |
| BeautifulSoup | For scraping web |
| sklearn | For machine learning | 
| nltk | For text preprocessing | 
| wordclounds | For creating wordclouds |
| requests | For web scraping | 

### Methodology
The following steps will be taken to complete this project:

1. Data scraping and preparation: Scrape customer review data from Skytrax.com and clean and prepare the data for analysis using Python and libraries such as BeautifulSoup and Pandas.
2. Data analysis: Perform data analysis on the cleaned data using techniques such as topic modeling, sentiment analysis, and wordclouds to uncover insights about the content of the reviews.
3. Results and recommendations: Create a PowerPoint slide with visualizations and metrics to summarize the key findings of the analysis, along with clear and concise explanations.

### Result
##### Final Presentation
![Final Presentasion](https://github.com/user-attachments/assets/75a59643-ddfc-4278-bef0-8b05d9d99fac)
![wordclound](https://github.com/user-attachments/assets/a106c404-39f8-4e9f-8e04-a9b05607e314)

## British Airways Predictive Modeling of Customer Booking

### Background
Customers are more empowered than ever because they have access to a wealth of information at their fingertips. This is one of the reasons the buying cycle is very different to what it used to be. Today, if you’re hoping that a customer purchases your flights or holidays as they come into the airport, you’ve already lost! Being reactive in this situation is not ideal; airlines must be proactive in order to acquire customers before they embark on their holiday.

You must manipulate and prepare the customer order data provided so that you can build high-quality predictive models. With your predictive model, it is important to interpret the results to understand how “predictive” the data actually is and whether we can feasibly use it to predict target outcomes (customers who purchase during the holidays).

### Problem Statement
Build high-quality predictive models to predict target outcomes (customers who purchase during the holidays).

### Objective
The main objectives of this project are,
1. Conduct Exploratory Data Analysis from data provided by British Airways.
2. Build a high-quality predictive model to predict target outcomes (customers who purchased during the holidays).
3. Evaluate the machine learning model that has been created.
4. Create a PowerPoint slide with visualizations and metrics to summarize the key findings of the analysis, along with clear and concise explanations.

### Data
Data obtained from British Airways. different from before where we got data from Skytrax.com web scraping.

##### Feature
- `num_passengers` = number of passengers travelling
- `sales_channel` = sales channel booking was made on
- `trip_type` = trip Type (Round Trip, One Way, Circle Trip)
- `purchase_lead` = number of days between travel date and booking date
- `length_of_stay` = number of days spent at destination
- `flight_hour` = hour of flight departure
- `flight_day` = day of week of flight departure
- `route` = origin -> destination flight route
- `booking_origin` = country from where booking was made
- `wants_extra_baggage` = if the customer wanted extra baggage in the booking
- `wants_preferred_seat` = if the customer wanted a preferred seat in the booking
- `wants_in_flight_meals` = if the customer wanted in-flight meals in the booking
- `flight_duration` = total duration of flight (in hours)
- `booking_complete` = flag indicating if the customer completed the booking

### Resource
##### Main Resource
| Resource    | Function | 
|:-------------|:------|
| Python        | a high-level programming language that is interpreted and known to be used for machine learning and data analysis   | 
| Jupyter Notebook/Google Colab | For IDE |
| PowerPoint Slide        |  for presenting the results and recommendations   | 

##### Library Python
| Library Python | Function | 
|:------------|:-------------|
| Pandas       | For data manipulation |
| sklearn  | For machine learning      |

### Methodology
1. Exploratory Data Analysis: Understanding the data through visualization and summary statistics.
2. Build and train model machine learning: Choosing the appropriate model(s) and training them on the data (RandomForestClassification).
3. Evaluate Model: accuracy_score and classification_report provide metrics to evaluate the model’s performance on the test set.

#### Modelling
* RandomForestClassification: For more complex models and able to handle feature interactions.

* KFold: This class is used to split your dataset into K consecutive folds for cross-validation.

* Vader: Used to build a model for sentiment scoring.

### Result
##### Final Presentation
![Final task 2](https://github.com/user-attachments/assets/abeecbf4-95e8-40be-9ab9-9fbb54ec5287)

###### from Forage.com

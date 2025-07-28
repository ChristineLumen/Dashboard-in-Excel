# 👚 Dashboard in Excel
## Project Overview
This analysis was conducted to explore merchandise buying trends among the population and to create an interactive visualization of the key findings. Since the initial dataset was already cleaned, the data cleaning step was skipped. The analysis focused on creating ranges using <code>IF</code> statements and structuring the data using <code>PivotTables</code>. The findings were then visualized in dashboards.

### Data Source
The dataset used for this analysis was downloaded from Kaggle. It contains detailed information including but not limited to customer's age, price range, location and reviews. 
In total, it includes 15 columns and 7,394 rows.
<br/> 
Source: <a href="https://www.kaggle.com/datasets/adarsh0806/influencer-merchandise-sales">Kaggle, Merchandise Sales</a>

### Tools
- Excel - Data Analysis and Dashboards
- Python - Basic Sentiment Analysis
  

### Exploratory Data Analysis
The EDA explores the merchandise dataset to answer key questions, such as:
- Which merchandise categories are most popular across different age segments?
- What tag price range is most common within each age group?
- What are the overall monthly sales by merchandise category?

### Data Analysis
**Excel**:
- Group age into age ranges, such as _Professional_,_Students_, _Young Professionals_
  =IF([<sub>Cell</sub>Age]>=30, "Professionals", IF([<sub>Cell</sub>Age]<=23, "Students", "Young Professionals"))
  

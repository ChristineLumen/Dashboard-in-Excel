# 👚 Dashboard in Excel 
## Project Overview 
This analysis was conducted to explore merchandise buying trends among the population and to create an interactive visualization of the key findings. Since the initial dataset was already cleaned, the data cleaning step was skipped. The analysis focused on creating ranges using <code>IF</code> statements and structuring the data using <code>PivotTables</code>. The findings were then visualized in dashboards.

### Data Source 
The dataset used for this analysis was downloaded from Kaggle. It contains detailed information including but not limited to customer's age, price range, location and reviews. 
In total, it includes 15 columns and 7,394 rows.
<br/> 
Source: <a href="https://www.kaggle.com/datasets/adarsh0806/influencer-merchandise-sales">Kaggle, Merchandise Sales</a>

### Tools 
- Excel: Data Analysis and Dashboards
- Excel: Visualization
  
### Exploratory Data Analysis
The EDA explores the merchandise dataset to answer key questions, such as: 
- Which merchandise categories are most popular across different age segments? 
- What tag price range is most common within each age group? 
- What are the overall monthly sales by merchandise category? 

### Data Analysis 
  1. Prepare the data table for creating a Pivot Table
      - Group ages into ranges such as _Professional_,_Students_, _Young Professionals_
      - Group prices into ranges such as _Cheap_, _Mid-Range_, _Expensive_
      - Extract the month from [Order Date]
        
  2. Created Pivot Tables to answer the EDA questions
  3. Built a dashboard that visualizes all three Pivot Tables with slicers for Gender, Price Range, and International Shipping
  <img width="913" height="532" alt="Screenshot 2025-07-24 at 1 02 39 PM" src="https://github.com/user-attachments/assets/6fbcdd33-d731-4812-bbaa-d8d1f0607280" />

### Results
The analysis results are summarized as following:
- Cloth dominates sales across all consumer groups
- Clothing sales peaked notably in May and July
- Students have the highest preference for expensive items(34.5%)
  
## Recommendations
1. Students are the most profitable group, especially among females, despite the assumption of limited budgets
2. Clothing is the main revenue driver, so it’s worth considering expanding inventory and focusing marketing efforts in this category
3. Ornaments show seasonal interest, suggesting they could be marketed more heavily during those months

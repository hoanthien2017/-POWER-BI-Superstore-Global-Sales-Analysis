# -POWER-BI-Superstore-Global-Sales-Analysis
## I. Introduction
### 1. Introduction to Dataset
* Dataset: **Superstore database**
- Dataset stores sales information worldwide for a company called Superstore.
- Data tables:
    | Table number: 3             | Fact table: 1                                      | Dim table: 2                                      |
    |-----------------------------|---------------------------------------------------|-------------------------------------------------|
    | Orders,  | Orders                  | People,                        |  
    | People,        |                          |     Inventory           |
    | Inventory       |                          |                       |
  
### 2. Data Detail
- Contents of tables:
  - Orders: table storing transaction information
  - People: table storing information of sellers in each region
  - Returns: table recording returned transactions    
- Description How to record data in each table:
    - All tables follow the Snapshot data capture type. Each row records a product type in the order. For orders with n products, n rows will be recorded. Each area is considered a unique record for other attributes.
- Preliminary assessment of data quality:
    - null, distinct, quality rule, min/max
### 3. Business Questions
- Which markets and regions should the company focus on for expansion to maximize revenue growth?
- What are the most profitable product categories, and how can the company optimize its product strategy to increase profitability?
## II. Design Thinking Method
**Here are the five steps of design thinking:**
### Stage 1: Empathize 
![image](https://github.com/user-attachments/assets/c58edfa6-02f9-4c04-a2c0-29583f45d53f)
![image](https://github.com/user-attachments/assets/c8f20931-f1c1-4bd1-8211-e36c0434602c)

### Stage 2: Define POV 
![image](https://github.com/user-attachments/assets/d56b000c-6344-4f9c-bf0a-2c3e8f14f227)
![image](https://github.com/user-attachments/assets/076ab9ec-5acc-432d-b24f-fa991a0d7b62)

### Step 3 - Ideate
![image](https://github.com/user-attachments/assets/f2a9e268-777f-46c4-ad70-b05fe0ce4193)
![image](https://github.com/user-attachments/assets/571424b2-b806-4bdf-a33f-c81a6dd3234b)

### Step 4 - Prototype
![image](https://github.com/user-attachments/assets/04236226-ebcc-42a2-9323-85e1c3f298a7)

### Step 5 - Review
![image](https://github.com/user-attachments/assets/98330772-b751-4cd4-9d00-0a0e52692b7e)


## III. Visualization
### 1. Data Schema
![image](https://github.com/user-attachments/assets/3a8e20c0-a7c4-4f07-af3b-419f0dd0de6f)

### 2. Overall Business Performance
![image](https://github.com/user-attachments/assets/31a0cd91-d660-499f-a378-a052ade1b797)

### 3. Market Analysis
![image](https://github.com/user-attachments/assets/0904b095-eae9-4d4a-b964-cfef40a4e397)

### 4. Product Analysis
![image](https://github.com/user-attachments/assets/72a9b5a2-23d7-4f11-88f2-1c04c0a1f5bf)

## IV. Insights and recommendations 
1. **Focus on High-Growth Regions**  
- Insight: The Market Analysis dashboard shows significant revenue growth in the APAC (28%) and EU (23%) regions.
- Recommendation: Prioritize expanding market presence in these high-growth regions to capitalize on existing momentum and increase market share.

2. **Enhance Product Offerings in Technology**  
- Insight: Technology products lead in sales, contributing 38% of the total revenue as shown in the Product Analysis dashboard.
- Recommendation: Invest in developing and marketing new technology products to maintain and enhance the dominant market position in this category.

3. **Improve Customer Retention Strategies**  
- Insight: The Overall Business Performance dashboard indicates a total of 3050 product returns with a return rate of 5.9%.
- Recommendation: Implement quality improvement initiatives and enhanced customer support to reduce return rates and improve customer satisfaction

4. **Diversify Product Range in Emerging Markets**  
- Insight: The Revenue by Market analysis highlights untapped potential in South America and Africa.
- Recommendation: Introduce a diversified range of products tailored to the unique preferences and demands of customers in these emerging markets..

5. **Optimize Inventory Based on Seasonal Trends**  
- Insight: The Product Performance Over Time chart in the Product Analysis dashboard reveals seasonal spikes in sales, particularly in Q4.
- Recommendation: Align inventory management and marketing efforts with seasonal demand patterns to ensure product availability and maximize 


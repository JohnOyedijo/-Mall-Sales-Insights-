### Datasets of Shopping Malls in Turkey

**CUSTOMER SHOPPING DATASET (A CASE STUDY OF 10 SHOPPING MALLS IN TURKEY)**

Hi, I'm John Oyedijo, a data analyst. This is one of my documentations on Microsoft Excel for data cleaning, creating pivot charts, and interactive dashboards. Let's explore this dataset and discover the fascinating world of Istanbul shopping.

**Data Collection**

This dataset was obtained from Kaggle and includes shopping information from 10 different shopping malls in Turkey between 2021 and 2023. It provides a comprehensive view of shopping habits across various age groups and genders. You can download the dataset [here](https://www.kaggle.com/datasets/mehmettahiraslan/customer-shopping-dataset?resource=download).

**About the Dataset**

The dataset contains 10 columns: invoice number, customer ID, age, gender, payment method, product category, quantity, price, order date, and shopping mall location.

**Data Cleaning**

Before analysis, I ensured the dataset's accuracy and reliability through thorough data cleaning. The dataset was already cleaned and ready for analysis. Using Microsoft Excel, I imported the raw data and utilized functions like AVERAGE, MAX, MIN, MEAN, and MEDIAN to calculate summary statistics for Age, Quantity, and Price.

- **Age:** The average age was 43 years, with a range from 18 to 69 years.
- **Quantity:** The average number of items purchased per transaction was 3, with a range from 1 to 5 items.
- **Price:** The average price per item was 689.26 TL, with prices ranging from 5.23 TL to 5250 TL.

**Additional Calculations**

- **Age Bracket:** Grouped using the formula: `=IF(D2<25,"18-24", IF(D2<35,"25-34", IF(D2<45, "35-44", IF(D2<55,"45-54", IF(D2>=55, "55 and more")))))`.
- **Revenue:** Calculated by multiplying the price by the quantity: `Revenue = G2*H2`.

**Pivot Tables and Charts**

- **Payment Method:** Analyzed the percentage distribution of cash, credit card, and debit card payments. Cash was the most used at 44%.
- **Purchase by Gender:** Female customers had a 20% higher purchase rate than males, likely due to higher sales in clothing and cosmetics.
- **Purchase by Product Category:** Clothing had the highest sales, while books had the least.
- **Shopping Mall Sales:** Mall of Istanbul had the highest sales, with four prominent malls contributing to 65% of total sales.
- **Sales by Age Group:** The 55 and older age group had the highest sales at 28.46%, while the 18-24 age group had the least.

Let's analyse the data and uncover insights together!

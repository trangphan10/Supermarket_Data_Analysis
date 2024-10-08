# Supermarket Data Analysis - Data Science Talent Competition 2024

## 1. Introduction
This project is conducted as part of the **Data Science Talent 2024** competition, aiming to utilize sales data from a supermarket chain to uncover trends and customer shopping behaviors, thereby proposing strategies to optimize business performance.

## 2. Data
The provided data includes:
- **Shelf Information**: Shelf ID, Description, Location_x (center),	Location_y (center),	Width,	Height,	Length, Number of items, Shape
- **Item Information**: Shelf ID, Item ID,	Name,	Origin,	Location,	Weight (g),	Price,	NSX,	HSD,	Marketing strategy,	Discount,	Rate
- **Customer Information**: Shelf ID,	Person ID,	Timestamp,	Age,	Gender,	Height,	Weight,	Married status,	Moving speed (m/s),	Item ID	Looking at item (s),	Holding the item (s),	Holding the bag,	Picking up item,	Returning item,	Putting item into bag,	Taking item out of bag, Putting item into bag in the 2nd time

## 4. Methodology
### 4.1. Data Preprocessing
- Handle missing data: Process missing values in key columns.
- Data cleaning: Remove invalid records and standardize formats.
- Create new variables: Calculate key indicators such as total sales by date, time.

### 4.2. Exploratory Data Analysis (EDA)
1. List the top 5 items with the longest total viewing and holding time?
2. List the top 5 items that are frequently picked up and then put back the most?
3. Which products are most purchased by each of the following age groups: Teenagers (18-30), Middle-aged (31-60), Seniors (> 60)?
4. Which day of the week has the highest revenue?
5. Among the following age groups: Teenagers (18-30), Middle-aged (31-60), and Seniors (> 60), which group has the highest number of people going to the supermarket?
6. What are the top 5 discounted items most purchased by users?
7. What are the top 5 advertised items most purchased by users?
8. What are the top 3 shelves with the longest average interest time per interaction (interest corresponds to viewing and holding)?
9. What are the top 3 shelves with the highest number of products sold?
10. Between which 2 shelves do users frequently travel the most?
11. Are there any items that need to be rearranged in the store? (Contestants' answer should be no more than 500 words).
12. Analyze the effectiveness of advertising and sales campaigns for products. (Contestants' answer should be no more than 500 words).


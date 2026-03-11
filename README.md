# Week 4 Assignment
**Carlos Kimuyu**

## What is Data? Explain in your own words and give two Examples .
Data is raw inputs (facts, observations or values) that can be collected and analyzed to produce information or insight.  

#### Example 1: Phone Repair Shop Data	

| Phone Model | Problem | Repair Cost |
|---|---|---|
| Samsung A12 | Screen damage 2 | 3500 KES |
| iPhone 11 | Battery issue | 4500 KES |


A data analyst could use it to find:

- The most common phone problems

- Average repair cost

- Which brands fail most often   


#### Example 1: Customer Purchase Data

A supermarket collects the following data
		
| Customer ID | Product	Price | Date |
|---|---|---|
| 101	Bread | 60 KES2 | 10 Mar |
| 102	Milk | 80 KES | 10 Mar |

These entries are data.

A data analyst can analyze this to discover:

- Most purchased products

- Customer buying patterns

- Sales trends  

## Explain the difference between: Structured Data and Unstructured Data. Give_ two Examples of each.
***Structured data*** is data that is organized in a fixed format, usually in rows and columns like a table or spreadsheet.

It follows a *clear structure and predefined schema*, making it easy for computers to store, search, and analyze.

#### Examples of Structured Data

**Customer database table**

| Customer ID | Product	Price | Date |
|---|---|---|
| 101	Bread | 60 KES2 | 10 Mar |
| 102	Milk | 80 KES | 10 Mar |


**Phone repair records**

| Phone Model | Problem | Repair Cost |
|---|---|---|
| Samsung A12 | Screen damage 2 | 3500 KES |
| iPhone 11 | Battery issue | 4500 KES |

---

***Unstructured data*** is data that *does not follow a predefined format or table structure.*

It is usually *text-heavy or multimedia content* that is harder for computers to analyze directly.

#### Examples of Unstructured Data

1. Customer emails or messages: 
    - "My Samsung phone keeps restarting after the update."

2. Media files

    - Photos

    - Videos

    - Audio recordings

**Simple way to remember:**

- *Structured Data = Organized (Tables, Databases).*

- *Unstructured Data = Not Organized (Text, Images, Videos).*



## What is a  Schema Explain using a simple example.
A *schema* is a blueprint or structure that defines how data is organized in a database.

*Think of a schema like a youtube tutorial about Python syntax before writing a single line of code.*

It tells the database what the data should look like before storing it.

#### Simple Example
The schema defines the structure like this:

| Column Name | Data Type | Description                |
| ----------- | --------- | -------------------------- |
| Student_ID  | Number    | Unique ID for each student |
| Name        | Text      | Student name               |
| Age         | Number    | Student age                |
| Course      | Text      | Course the student studies |

This structure (columns and data types) is the schema.

Actual stored data may look like this:

| Student_ID | Name  | Age | Course         |
| ---------- | ----- | --- | -------------- |
| 101        | Amina | 21  | Data Science   |
| 102        | Brian | 23  | AI Engineering |

The schema defines the format, while the rows contain the real data.

>Schema = the blueprint of how data is organized.

## Bonus Question 
Explain the difference between:
- A list
- A dictionary

A ***list*** is a collection of items stored in order and can be accessed using its position (index).

#### Example
`Python`

`phones=["Samsung", "iPhone", "Tecno", "Nokia"]`

Here:

- "Samsung" is index 0

- "iPhone" is index 1

- "Tecno" is index 2

You access items using the index:

`Python`

`print(phones[0])`  # Samsung

---

A ***dictionary*** stores data as key–value pairs.
Instead of using positions, you access values using their keys.

`Python`

    phone={
    "brand": "Samsung",
    "model": "A12",
    "price": 15000
    }

Here:

- "brand" → key

- "Samsung" → value

You access values using the key:

`Python`
`print(phone["brand"])`  # Samsung

#### Simple way to remember

>List = items in order

>Dictionary = items with labels (keys).

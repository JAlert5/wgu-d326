# wgu-d326

					Business Report
This report will give an overview of the distribution of films in different categories of DVD rental business's inventory. It highlights how many films are available in each genre. It can also reveal any lack of availability in certain categories helping to decide where to expand to meet customer demand.


A1.  Identify the specific fields that will be included in the detailed table and the summary table of the report.
Detailed table fields
Category_id - Unique identifier for film category
Film_id - Unique identifier for film in database
Summary fields
catergory_id
film_count - total number of films in each category

A2. Describe the types of data fields used for the report

Integers
Category_id
film_id

A3.  Identify at least two specific tables from the given dataset that will provide the data necessary for the detailed table section and the summary table section of the report.

film_catergory
category
A4.  Identify at least one field in the detailed table section that will require a custom transformation with a user-defined function and explain why it should be transformed (e.g., you might translate a field with a value of N to No and Y to Yes).

The field “category_id” will be better off transformed with a user-defined function because it will be easier to communicate with stakeholders category names instead of numbers. Switching the id from being numeric to being an action, comedy exc. Will make a report more readable for those in non technical spaces.

A5. Explain the different business uses of the detailed table section and the summary table section of the report.  
We can make use of the summary table by observing the data pulled to decide on how to replenish stock. The business can decide whether or not they should add more to a specific category or perhaps increase the availability of popular titles. 

A6.  Explain how frequently your report should be refreshed to remain relevant to stakeholders.

A report should be refreshed weekly in order to remain relevant to stakeholders. This ensures that there is an up to date record of inventory based on category. This can help the business be proactive in their effort to restock and or purchase new titles. 

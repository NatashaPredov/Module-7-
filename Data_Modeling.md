## Data Modeling
Create an entity relationship diagram (ERD) by inspecting the provided CSV files. Part of the challenge here is to figure out how many tables you should create, as well as what kind of relationships you need to define among the tables. Feel free to discuss your database model design ideas with your classmates. You can use a tool like Quick Database Diagrams Links to an external site.to create your model.

# Hints:
- For the credit_card and transaction tables, the card column should be a VARCHAR (20) datatype rather than an INT.
- For the transaction table, the date column should be a TIMESTAMP datatype rather than DATE.

# Findings 
Based on reviewing the CSV files provided, I have summarized my findings and thinkings below which helped to organize the ERD.
1. The required feilds on all tables are: ID(identity - int), card (VARCHAR(20)) and name (/description of the item, choose a large size due to the uncertanity of name length - VARCHAR(60)) 
2. Tables: Merchant, Cardholder, Transaction, Merchant_Category, Credit_Card 
3. Since this information has to do with fraud and credit history, a reduction in redundency will be a main focus so that a conclusion of if fraud has occured can easily be determined 


For the building of the ERD I used QuickDBD (https://www.quickdatabasediagrams.com/) - a resource that was introduce to me during class time. 

<img width="931" alt="Screen Shot 2023-01-19 at 7 39 15 PM" src="https://user-images.githubusercontent.com/110856988/213593163-2df018d0-a7a7-4018-8989-e7ca1aa606d1.png">

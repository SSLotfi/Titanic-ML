# Titanic-ML
solution for the Titanic problem on Kaggle

- link of the problem on Kaggle : https://www.kaggle.com/c/titanic

#### Data preprocessing:
- removed the "Name" column
- removed the "Cabin" column as the data was missing alot of information and hence had no effect on the survival probability
- removed the "Embarked" column as the place where the passenger boarded the ship didn't affect the survival probability
- removed the "Ticket" column as the name of the ticket didn't have an effect
- replaced the genders from male and female to 0 and 1 
- added the missing age values with the average of ages

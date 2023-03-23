# Relational-Databases

 Relational Databases have more than one table and are linked using fields and represented with keys. **Information is meaningful data that has been structured or processed.**
 
 ### Entity relationships
 
 An entity is a category of object, person, event or thing of interest about which data needs to be recorded. Each entity in a database can have attributes. E.g Member(title, firstname, surname, email, etc)
 
 
 ![image](https://user-images.githubusercontent.com/110039102/227191389-b16aa4a4-de79-4b06-a038-03713f60f0ce.png)

Above is an example of a Flat File Database (FFD). They allow the user to specify data attributes for only one table at a time and store them independently. THere is no link between different tables. They have issues. E.g:

- Redundancy
- Update Issues (more than 1 place)
- Deletion issues (more than 1 place)
- Amendment Issues (more than 1 place)
![image](https://user-images.githubusercontent.com/110039102/227192115-a92d2e9c-8161-409b-8949-52f5008db75d.png)
![image](https://user-images.githubusercontent.com/110039102/227192213-63113b2d-9e56-4ec9-8a19-3abcbb60b594.png)
![image](https://user-images.githubusercontent.com/110039102/227192269-bdaa3786-104f-4ffa-be37-9b68924110bb.png)
![image](https://user-images.githubusercontent.com/110039102/227192299-590181f6-ad6e-4f13-a2f9-1270c6afac07.png)
![image](https://user-images.githubusercontent.com/110039102/227192370-ebd07b10-eb0e-4b9c-901a-3a1a35c4b41c.png)

### Keys

A **foreign** key is an attribute that creates a join between two tables (relations). It is the primary key (unique field) in the first relation. It is a field or collection of fields in one table, that refers to the primary key in another table. 
The table with the foreign key is called the child table, and the table with the primary key is called the referenced or parent table.

### Normalisation

There are a lot of ways of arranging data in tables within a database, and each arrangement can be given a label according to how its been arranged. These labels are called thier **'Normal Form'**.

There are 3 types of normal form: First Normal Form (1NF), Second Normal FOrm (2NF), Third Normal Form (3NF).

The concept of splitting up tables in a database and arranging the data to move it from 1NF -> 2NF -> 3NF is called normalisation.

Understand definitions of 1NF and 2NF only (no detailed exam questions) and design simple database into 3NF.

![image](https://user-images.githubusercontent.com/110039102/227194838-8a35e9c9-9a3f-41f7-ae4e-dbe427ae21a7.png)

https://www.youtube.com/watch?v=1YMdx97o1U8

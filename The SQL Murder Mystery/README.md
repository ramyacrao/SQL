## The SQL Murder Mystery

### There's been a Murder in SQL City!

**Task:**</br>
A crime has taken place in SQL City and the detective has reached out for help. The crime scene report shared by the detective has been misplaced and the only information on hand is that the crime was a ​murder​ that occurred sometime on ​Jan.15, 2018​ and that it took place in ​SQL City​.

**Prep**:</br>
To get an idea of the information I was working with, I first looked into the database schema. </br>

On querying, the database was found to have the following 9 tables - 8 tables with information pertaining to the crime, and the solution table to validate the result once done. </br>
 
<sub>List of tables in the database</sub></br>
![db_tables](https://github.com/user-attachments/assets/c622de26-0dab-4685-9acc-8c67bc317f6d)

<sub>Schema of the tables in the database</sub></br>
![db_table_schema](https://github.com/user-attachments/assets/aa0b91c9-7de8-4507-bc00-833732258728)

**Investigation**</br>

I started off by looking into the crime scene report for the details of the murder. </br>
![db_query1_output](https://github.com/user-attachments/assets/61e08241-b512-46ec-b25d-da115d36081c)

The next step was to look up the details of the witnesses based on the information in the crime scene report. </br>
![db_query2_output](https://github.com/user-attachments/assets/53cc4f51-e97a-4a5c-9c9a-481c3be7db23)

Once I had the names of the witnesses, it was time to find the transcript of their interview. </br>
![db_query3_output](https://github.com/user-attachments/assets/891e6d4c-cd98-4a7d-8f7d-346479701905)

Narrowing down the suspects to arrive at the solution based on the information provided by the witnesses. </br>
![db_solution](https://github.com/user-attachments/assets/75c99d68-8fd3-4586-9682-df16dba566ba)



   


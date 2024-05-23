Note : a database is just a bunch of tables . ( in a ratioanl database , at lease ) and tables , hold the data . 


## the importance of data type ==> what type of information is permitted in each column

SQL (Structured Query Language) supports a variety of data types that you can use to define the structure of the tables in a database. These data types specify the kind of data that each column in a table can hold. Understanding SQL data types is crucial for designing efficient and robust databases.

### Common SQL Data Types

SQL data types can be broadly categorized into several types:

1. **Numeric Data Types**
2. **String (Character) Data Types**
3. **Date and Time Data Types**
4. **Binary Data Types**
5. **Miscellaneous Data Types**

<hr>

  Choosing INT:
  
        Use INT for primary keys, foreign keys, and any fields where numerical data is stored and arithmetic operations are performed.
        Consider using UNSIGNED if negative values are not needed, to increase the positive range.
        
  Choosing VARCHAR:
  
        Use VARCHAR for text data that does not have a fixed length.
        Define an appropriate maximum length to balance storage efficiency and flexibility.

**Name:**  *CBoisen*  
**Date:** *November 25,2023*  
**Course:** *IT FDN 130 A*  
**Github:** 

# Assignment 7- Functions

### Introduction

Within SQL Server, functions serve as a set of statements that work to perform predefined operations. Both built in functions and user defined functions can be stored within the database and used to complete calculations, manipulate data, and return tables or single values. User defined functions can also be further subcategorized as scalar, inline, or multiple statement. By using different types of functions, complex code can be simplified, increasing overall database efficiency and accessibility. 

### Functions 

Functions are sets of SQL statements that accept inputs and parameters then work to perform a defined task. Each database in SQL Server comes with a set of “built-in” system functions but additional functions (also known as “User Defined Functions” or UDFs) can also be created by the user for more specific purposes. In the context of SQL databases, UDFs allow custom parameters and serve to increase code reusability within the defined environment. 

There are three types of UDFs in SQL: Scalar, Inline Table Valued, and Multi-Statement Table Valued. Each of these user defined functions returns either a single, scalar value or a table of values and (unlike views) can accept parameters to specify the results of the query. 

1. Scalar Functions return a single, scalar value as an expression. Similar to built in functions, they often return a single string date, or integer. These functions can return any scalar built-in SQL data type except TIMESTAMP. 
2. Inline Table Valued Functions contain a single transact statement that returns a table set. Unlike scalar UDFs, inline UDFs will return a table as a result. Limited to a single transact statement, the short scripts of inline functions limit more complex logic and are often equated to the functionality of views within SQL. 
3. Multi-Statement Table Valued Functions contain multiple transact statements that return a table set. While inline functions are thought to function more like views within SQL Server, multi-statement functions are thought to be treated more like stored procedures. These UDFs use many statements to create a returned table variable and can be used to contain more extensive logic than single statement inline functions. 


### Conclusion 

To simplify complex code and increase ease of data management, SQL functions can be used to manipulate and transform data. In addition to a wide range of built in functions, users can also define their own functions in SQL creating User Defined Functions (UDFs) to meet their own particular needs. UDFs include three subcategories, scalar, inline, or multiple statements, which each return a distinct type of result depending on the parameters defined. Through UDFs, complex and repetitive code can be simplified and made more readable, increasing speed of execution and overall ease of database access. 

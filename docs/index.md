#Assignment 07: Functions

##Introduction
Functions are SQL statements that perform a specific task or operation, they can be saved in the database and used by other users. Functions are similar to views but can accept parameters and return a table or a single value. This article will briefly introduce functions and discuss the difference between scalar and table-valued functions (TVFs). 

##When to use a SQL UDF.
The advantages of functions are that they maintain the code and allow for reusability.  It is necessary to use the two-part name of the database when working with function - the schema name with the table name (ie. Dbo.tblanama). 

##The differences between Scalar, Inline, and Multi-Statement Functions.
Scalar, inline and multi-statement functions are all user defined functions (UDFs). Scalar functions have one or more parameters, return a single value per row, and can also be used as a check constraint. They can be used any where in the SELECT statement. Table-valued functions output a table. They can be used after the FROM clause in a SELECT statement. There are two types of TVFs: inline and multi-statement.  Unlike scalar function, inline tabular functions do not require BEGIN/END block. A multi-statement function returns a table that is constructed in the script and can include multiple selection statements. 

##Summary 
This article covered two types of functions: Scalar that return a single value per row and table-valued function which output a table. The difference between Inline and multi-statement functions TVFs. Inline functions contain one select statement while multi-statement functions contain multiple select statements. 

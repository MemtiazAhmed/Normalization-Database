# Normalization-Database

For 1NF:

       – There are no duplicate rows and each row should have a unique identifier (or Primary key). 
      or 
       -All rows are unique.

For 2NF:
 
       - Satisfy 1NF
	   - any non-key columns must be dependent on the entire primary key. In the case of a composite primary key,
    	   this means that a non-key column cannot depend on only part of the composite key.
		
	   or,
 
       - Keys will be unique
       - create 2 tables and create the relationship between them

For 3NF:

       - Satisfy 2NF
       - All columns should depend directly on the primary key.
    	   Tables violate the Third Normal Form when one column depends on another column, which in turn depends on the primary key (a transitive dependency)	   
       or,
	   - all column depends on primary key(separate the column that are not dependent on primary key ).
# SQL Practice

**SQL** stands for **Structured Qurey Language** 
- it is a search language for you to instruct a database about what info you'd like retrived from it 

### Frist Command: SELECT

- Its the first instruction you need for any SQL statement thats fetching data
- Each query needs to end in a semi-colon (;). Thats how the database knows that your giving its instruction.

### Second Command: FROM

- Where to get the data
- If you want all the columns avaliable you can use a splat ( * )

### Third Command: ORDER BY

- For Example:
  - SELECT [stuff you want to select] FROM [the table it is in] ORDER BY [column you want]

### LIMIT and OFFSET

- If you want to limit the number of results that are returned you are can simply use the **LIMIT** command with a number of rows to LIMIT by
- You can also specify an **OFFSET** from where to start returning data

### Browsing the Schema

- The word schema is used to describe a collection of tables and their relationship in your database 

### WHERE

- **WHERE** is followed by the conditions you'd like to be filtered by 
- **Conditions** are simply statements that are either true or false

### AND - Requiring multiple conditions 

- You can add additional conditions by using **AND** operator between each new condition 

### OR - Requiring any condition

- You can use the **OR** to define multiple WHERE conditions
- Where you care whether not both but at least one of the conditions is true

### NOT

- You can leave out a condition by simply putting the **NOT** operator infront of it 

### Ordering and Parenthesis 

- You can use any number of **OR** and **AND** commands in your conjunction to describe your conditions 
- SQL has an order of operation

### Operators

- equal ( = )
- less than ( < )
- greater than ( > )
- greater than or equal to ( >= )
- less than or equal to ( <= )
- not eqaul ( ! )
- not equal ( <> )

### String Operators and Patterns

- LIKE = a string matches a pattern 
- ILIKE = case insensitive of LIKE
- SIMILAR TO = a string matches a regex pattern

#### LIKE

- Is the easy/ lightweight way to match a string to a pattern. A **pattern** is a string that can use some special symbols that represent wildcard characters 

#### ILIKE

- Use if you dont care about whether the letters are upper case or lowercase

#### SIMILAR TO

- **SIMILAR** is the more advanced way to match a string to a pattern

### Dealing with Nulls

- Every empty cells in a database are called null

### COUNT Function 

- Takes whatever you give it and returns the count of how many they are 

### Functions

- MAX = returns largest number in sets 
- MIN = returns smallest number in sets
- COUNT = returns a count of the # of values in a set 
- COUNT DISTINCT = returns a count of the # of unique (distinct) values in a set
- EVERY = returns true if all data inside is true 
- AVG = returns the average (mean) of the set of numbers 
- SUM = returns the sum of all thw values in a set 

### JOIN Relationships and JOINing

#### Tables

- It is possible to JOIN these table together to fetch results from both 


- POSTGRE SQL is a Relation Database, which means it stores data in tables that can have relationships (connections) to other tables 


- Primary key = a key in a column in a table that a unique indentifier for each row 
- Foreign key = are columns in a table that specify a link to a primary key in another table 

### DATE/ TIME Datatypes 

- TIMESTAMP = date and time
- DATE = date (no time)
- TIME = time
- INTERVAL = interval between 2 dates/ times

### UNION and UNION ALL

- 2 main differences
  - UNION = only keeps unique records
  - UNION ALL = keeps all records even duplicates 



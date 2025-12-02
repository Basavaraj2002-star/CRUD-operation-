# CRUD Operation Project (C# + SQL + ADO.NET)

This is a simple CRUD (Create, Read, Update, Delete) project built using C#, SQL Server, and ADO.NET.

## Features
- Add new record  
- View all records  
- Update record  
- Delete record  

## Technologies Used
- C#
- SQL Server
- ADO.NET
- Visual Studio

## Database Table
Use this SQL code:

```sql
CREATE TABLE Students (
    Id INT IDENTITY PRIMARY KEY,
    Name VARCHAR(100),
    Email VARCHAR(100),
    Mobile VARCHAR(15)
);
```

## How It Works
- SqlConnection → connects to SQL  
- SqlCommand → Insert, Update, Delete  
- SqlDataAdapter → Load data  
- DataTable → Display data  

## How to Run
1. Open project in Visual Studio  
2. Update your SQL connection string  
3. Run the project  
4. Perform CRUD operations  

## Author
Basavaraj

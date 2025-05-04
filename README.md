# Departments_SQL_Database
This table is typically part of an HR or organizational database structure where each department has a unique ID, a name, and may optionally be linked to a manager and a location.

## Brief Description:

**CREATE TABLE departments:** This command creates a new table named departments.

**department_id INT PRIMARY KEY:**
        department_id is an integer column.
        It serves as the primary key, meaning each value must be unique and not NULL.
        Uniquely identifies each department.

**department_name VARCHAR(30) NOT NULL:**
        Stores the name of the department, allowing up to 30 characters.
        NOT NULL means this field is mandatory — it cannot be empty.

**manager_id INT:**
        Optional integer column to store the ID of the manager for the department.
        It could reference another table (like employees), though no foreign key is defined here.

**location_id INT:**
        Optional column to store the location ID of the department.

<p align="Left">
  <img src="https://github.com/jahangirmayed1990/Departments_SQL_Database/blob/main/Department_SQL.JPG" alt="Department_SQL" width="600"/>
</p>

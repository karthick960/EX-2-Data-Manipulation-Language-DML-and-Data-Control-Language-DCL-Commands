# EX 2 Data Manipulation Language (DML) Commands and built in functions in SQL
## AIM:
To create a manager database and execute DML queries using SQL.


## DML(Data Manipulation Language)
<div align="justify">
The SQL commands that deal with the manipulation of data present in the database belong to DML or Data Manipulation Language and this includes most of the SQL statements. It is the component of the SQL statement that controls access to data and to the database. Basically, DCL statements are grouped with DML statements.
</div>

## List of DML commands: 
<div align="justify">
INSERT: It is used to insert data into a table.<br>
UPDATE: It is used to update existing data within a table.<br>
DELETE: It is used to delete records from a database table.<br>
</div>

## Create the table as given below:
```sql
create table manager(enumber number(6),ename char(15),salary number(5),commission number(4),annualsalary number(7),Hiredate date,designation char(10),deptno number(2),reporting char(10));
```

## insert the following values into the table
```sql
insert into manager values(7369,'Dharsan',2500,500,30000,'30-June-81','clerk',10,'John');
insert into manager values(7839,'Subu',3000,400,36000,'1-Jul-82','manager',null,'James');
insert into manager values(7934,'Aadhi',3500,300,42000,'1-May-82','manager',30,NULL);
insert into manager values(7788,'Vikash',4000,0,48000,'12-Aug-82','clerk',50,'Bond');
```

### Q1) Update all the records of manager table by increasing 10% of their salary as bonus.

### QUERY
![image](https://github.com/ganeshshanmugavel27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122046208/42e0d337-1e61-4e21-a22e-c527c03f8e8e)




### OUTPUT:
![image](https://github.com/ganeshshanmugavel27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122046208/871d54d8-75c6-4011-ae68-0791d786ca35)



### Q2) Delete the records from manager table where the salary less than 2750.


### QUERY:
![image](https://github.com/ganeshshanmugavel27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122046208/e979b5fb-7f5a-4289-8f80-7d0a30cb32b4)



### OUTPUT:
![image](https://github.com/ganeshshanmugavel27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122046208/ce31f407-aac1-4120-9b10-7139316d8295)



### Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)


### QUERY:
![image](https://github.com/ganeshshanmugavel27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122046208/451e0175-d9db-4dd6-a794-0ac89be77b8d)



### OUTPUT:
![image](https://github.com/ganeshshanmugavel27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122046208/d3940f73-9e3d-43dc-990b-dbc21dd2545b)



### Q4)	List the names of Clerks from emp table.


### QUERY:
![image](https://github.com/ganeshshanmugavel27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122046208/c4b9a902-a0c9-4375-9d65-5c92124875cf)



### OUTPUT:

![image](https://github.com/ganeshshanmugavel27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122046208/e8712716-d05a-484d-808d-9ec6e2e59377)




### Q5)	List the names of employee who are not Managers.


### QUERY:
![image](https://github.com/ganeshshanmugavel27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122046208/50641f00-de3a-4cf3-aab7-6da5cc77542e)


### OUTPUT:
![image](https://github.com/ganeshshanmugavel27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122046208/e8071e16-c3a0-45ee-8ba6-141ab03d2d75)



### Q6)	List the names of employees not eligible for commission.


### QUERY:
![image](https://github.com/ganeshshanmugavel27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122046208/4c7c30b0-ad1f-4c60-ade7-62df6ccf48c5)



### OUTPUT:
![image](https://github.com/ganeshshanmugavel27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122046208/1cf5bd02-fc24-494b-a1ca-01e2ad032bd0)



### Q7)	List employees whose name either start or end with ‘s’.


### QUERY:
![image](https://github.com/ganeshshanmugavel27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122046208/498fa7c6-a7ea-4d33-a00f-2032730b2d0c)



### OUTPUT:
![image](https://github.com/ganeshshanmugavel27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122046208/9eefc069-ab23-4e47-8ff1-2890d96b70ae)



### Q8) Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.


### QUERY:

![image](https://github.com/ganeshshanmugavel27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122046208/cff55a03-7fdd-4df8-9d10-3c0346aac95d)



### OUTPUT:
![image](https://github.com/ganeshshanmugavel27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122046208/1f2c9c02-6462-4ed9-a372-f1db7c50f137)




### Q9) List the Details of Employees who have joined before 30 Sept 81.


### QUERY:
![image](https://github.com/ganeshshanmugavel27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122046208/c6c2e5c1-ada7-4184-ade0-d052c54f8dd6)



### OUTPUT:
![image](https://github.com/ganeshshanmugavel27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122046208/342ba40e-7dc2-4720-bd92-7a0d86fbc635)



### Q10)	List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.


### QUERY:

![image](https://github.com/ganeshshanmugavel27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122046208/278b0bf4-8096-4c8a-9d43-1c492a364522)



### OUTPUT:
![image](https://github.com/ganeshshanmugavel27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122046208/8e728af3-f3d9-4551-9dff-3c563accacc5)



### Q11) List the names of employees not belonging to dept no 30,40 & 10


### QUERY:
![image](https://github.com/ganeshshanmugavel27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122046208/ee151af7-f458-401c-aa88-1f44a6370e07)



### OUTPUT:
![image](https://github.com/ganeshshanmugavel27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122046208/05d139fc-9bc6-4090-a982-7723ec96e3c3)



### Q12) Find number of rows in the table EMP

### QUERY:
![image](https://github.com/ganeshshanmugavel27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122046208/92f21fab-436b-4b8f-a033-f1569a5eaa98)



### OUTPUT:

![image](https://github.com/ganeshshanmugavel27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122046208/7e86e3d1-69a8-4346-be8c-ac7fa8f85966)


### Q13) Find maximum, minimum and average salary in EMP table.

### QUERY:
![image](https://github.com/ganeshshanmugavel27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122046208/e479ae08-1a71-41b3-8bf1-bc9e3cea16c3)



### OUTPUT:
![image](https://github.com/ganeshshanmugavel27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122046208/569faa4a-bf93-454b-b7ae-7f35e45bd538)



### Q14) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.

### QUERY:
![image](https://github.com/ganeshshanmugavel27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122046208/7d7ef160-e631-424a-a5a2-a22c09c36bdc)



### OUTPUT:
![image](https://github.com/ganeshshanmugavel27/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/122046208/b0f20b88-7d95-4115-b376-a543fa74c3d1)


### RESULT:
QUERIES EXECUTED SUCCESSFULLY.

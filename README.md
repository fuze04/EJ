# Programs

[Write a servlet code to store the bio data details of the user into the database](./Biodata_details.zip)


[create an html page with feilds eno name desg and salary now on submit the jsp page will update db](./emp_jsp_db.zip)


[create a jsp application to demostrate the use of Expression language](./ELLanguage.zip)


[create a application for download a file](./Practical_3a(Part2).zip)


[create a application for upload a file](./Practical_3a.zip)


[Develop a web app to provide set of 5 question to the user.........](./QuestionAnswerServlet.zip)


[create a jsp to accept eno ename and salary .Insert the records in emp and create table](./emp_jsp.zip)


[write a simple jsp application to demonstrate the use of implicit object](./implicitobjectsjsp.zip)


[write a jsp code to accept an employee id from user and delete the records of that employee](./DeleteEmployee.zip)


[Develop a web application to allow the user to enter invebtory details](./InventoryManagament.zip)


[Develop a EJB that calculates compund intrest and simple intrest for princpal..... ](./InterestCalculator.zip)

<hr>
#CLASS PRACTICALS
<br>

[Simple calculator using servlet](./Practical1A.rar)


[create a servlet for login page if login and pasword are same then hello username](./Practical1B.rar)


[registeration servlet using jdbc accept details like uname,pswd,email,cntry......](./Practical1C.rar)


[using request dispatcher interface create servelt which validate pswd enter by user ](./Practical2a.rar)


[Servlet demonstrating the use of session creation and destruction also check user has page n no of tme ](./Practical2c.zip)


[Create simple question ans app using db -3questions  ](./Practical_3b.rar)


[simple jsp application to display value obtain use of instrinct](./Practical4a.zip)


[Simple jsp application pass value from one page to another with validation,name,age,gender](./Practical4b.rar)


[reisteration and login jsp application to authenticate register based on jdbc uname and pswd ](./Practical4c.rar)


[jsp application to demonstrate the use of jstl](./Prac5c.rar)


[create currency convertor application using ejb](./Practical6a.zip)


[simple room reservation system ejb](./Practical6b.zip)


[simple shopping cart using ejb](./Prac6CShoppingCartApp.zip)


[ejb application to demonstrate servlet hit count using singleton session bean](./Practical7a.zip)


[marks entry application to demonstrate accessing db using ejb)](./Practical_7c.zip)








### Practical 3a and 3a part2 are download and upload file code

<hr>

# PDFs 

[EJ Lab Manual](./Pdfs/EJ%20Lab%20Manual.pdf)

[EJ Manual Enext](./Pdfs/EJ%20Manual%20(E-next.in).pdf)


<hr>
<br>
<br>




# Database Structures

## Inventory Code Database
```mysql
CREATE TABLE inventory (
    id int AUTO_INCREMENT PRIMARY KEY,
    productName VARCHAR(255),
    productPrice DECIMAL(10, 2),
    quantity int
)
```

```mysql
select * from inventory
```

## For loginregisterjsp
```mysql
create table usrpass(fname varchar(30),lname varchar(30),pass varchar(30),email varchar(30))
```
```mysql
select * from usrpass
```

## For Delete Employee Code

```mysql
CREATE TABLE IF NOT EXISTS employees (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100) NOT NULL,
    job VARCHAR(100) NOT NULL
);
```

```mysql
INSERT INTO employees(id, name, job) VALUES 
('1', 'Bob', 'Engineer'), 
('2', 'Rob', 'Manager'), 
('3', 'Hugh', 'Developer'),
('4', 'Peter', 'Assistant'), 
('5', 'Tom', 'Clerk');
```

```mysql
select * from employees;
```

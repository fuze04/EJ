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





























Practical 3a and 3a part2 are download and upload file code


//for inventory code database
CREATE TABLE inventory (
    id int AUTO_INCREMENT PRIMARY KEY,
    productName VARCHAR(255),
    productPrice DECIMAL(10, 2),
    quantity int
)

select * from inventory


//for loginregisterjsp
create table usrpass(fname varchar(30),lname varchar(30),pass varchar(30),email varchar(30))

select * from usrpass


//---for delete employee code

CREATE TABLE IF NOT EXISTS employees (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100) NOT NULL,
    job VARCHAR(100) NOT NULL
);

select * from employees;
INSERT INTO employees(id, name, job) VALUES 
('1', 'Bob', 'Engineer'), 
('2', 'Rob', 'Manager'), 
('3', 'Hugh', 'Developer'),
('4', 'Peter', 'Assistant'), 
('5', 'Tom', 'Clerk');

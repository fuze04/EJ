[Write a servlet code to store the bio data details of the user into the database](Biodata_details.zip)











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

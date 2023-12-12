Practical 3a and 3a part2 are download and upload file code


//for inventory code database
CREATE TABLE inventory (
    id int AUTO_INCREMENT PRIMARY KEY,
    productName VARCHAR(255),
    productPrice DECIMAL(10, 2),
    quantity int
)

select * from inventory

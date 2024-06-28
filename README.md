# Farmatech

## Overview

The Pharmacy Management System is a web-based application designed to manage the operations of a pharmacy. The system allows for the management of medicines, customers, and sales transactions. This project is implemented in Java using the Tomcat server and the H2 database.

## Features

- **Medicine Management**: Add, update, delete, and view medicine details.
- **Prescription Management**: Track and manage prescription levels of medicines.
- **User Authentication**: Secure login and user role management.

## Technologies Used

- **Backend**: Java
- **Web Server**: Apache Tomcat
- **Database**: H2 Database
- **Frontend**: HTML, CSS

## Installation

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- Apache Tomcat 9 or higher
- H2 Database

### Steps

1. **Clone the Repository**
   ```sh
   git clone https://github.com/raphaelgpalma/farmatech.git
   ```

2. **Set Up the Database**

- Navigate to the src/main/resources directory.
- Open the schema.sql file and execute the SQL commands in your H2 database console to create the necessary tables.

3. **Configure the Database Connection**

- Open the src/main/resources/application.properties file.
- Update the database URL, username, and password if necessary.

4. **Build the Project**
   ```sh
   mvn clean install
   ```

## Usage

1. **Login**
   - Use the default admin credentials to log in:
     - Username: `admin`
     - Password: `admin`
   - Change the default password after the first login.

2. **Medicine Management**
   - Navigate to the Medicines section to add, update, or delete medicine records.

3. **Customer Management**
   - Navigate to the Customers section to manage customer information.

4. **Sales Transactions**
   - Navigate to the Sales section to process sales transactions and view sales history.

5. **Inventory Management**
   - Monitor inventory levels and generate alerts for low stock.

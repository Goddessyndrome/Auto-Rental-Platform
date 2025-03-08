# Auto Rental Platform
Created a Vehicle Rental System using Java OOPs  concepts with an MVC architecture and JSwing, including features for user account management, vehicle inventory management, rental operations, and user roles (Admin, Client, User)

# Project Overview
The Auto Rental Platform is a Java-based application that enables users to rent, return, and manage vehicle rentals efficiently. The system follows an MVC (Model-View-Controller) architecture to ensure modularity and scalability.

# Project Structure

# 1. Controller (Business Logic)
The Controller package contains Java classes that handle the core functionality of the car rental system, including user actions, authentication, and car management.

* Key Classes & Functionalities:

* Account & User Management:


AddNewAccount.java – Handles account creation for users.

AddNewAdmin.java – Allows adding new admin users.

AddNewClient.java – Registers new clients in the system.

EditUserData.java – Edits user details such as name and contact information.

ChangePassword.java – Allows users to update their passwords.


* Car Rental Operations:


AddNewCar.java – Adds a new car to the rental inventory.
  
RentCar.java – Facilitates the process of renting a car.

ReturnCar.java – Manages the return of rented cars.

DeleteCar.java – Removes a car from the system.

UpdateCar.java – Updates car details like price, availability, and model.


* Rental History & Records:
  

ShowAllRents.java – Displays all rental records in the system.
  
ShowSpecUserRents.java – Shows rental history for a specific user.

ShowUserRents.java – Retrieves and displays rentals made by a logged-in user.
  

* Car Management & Views:

ViewCars.java – Displays a list of available cars for rent.
  
* System Control:

Main.java – The entry point of the application. It initializes the system and starts the user interface.
  
Quit.java – Exits the system safely.
  

# 2. Model (Data Representation)

The Model package contains Java classes that define the structure and attributes of key entities in the system.

* Key Classes:
  
* User & Authentication Models:
  

Admin.java – Represents admin users.

Client.java – Represents clients who rent cars.

User.java – General user class handling common attributes and behaviors.


* Car & Rental Models:


Car.java – Represents a car with attributes such as model, price, and availability.

Rent.java – Stores details of rental transactions.

Operation.java – Manages various rental and return operations.
  

* Database & Utility Classes:


Database.java – Manages database connections and queries.

CustomLabel.java, JButton.java, JComboBox.java, JPasswordField.java, JTable.java, JTextField.java – Various GUI components used for the user interface.


# Technology Stack

- Programming Language: Java (JavaSE-21)

- Architecture: MVC (Model-View-Controller)

- GUI Framework: Java Swing for UI components

- Database Management: Handled using Database.java




![Veh1](https://github.com/user-attachments/assets/c639bdc4-491a-42a2-b9a0-449076f52099)
![veh2](https://github.com/user-attachments/assets/1f610803-5de4-4a02-85b2-226d516ff2f3)
![veh3](https://github.com/user-attachments/assets/fe347b5e-6dd3-44b9-bad3-722c960b9ed6)
![veh4](https://github.com/user-attachments/assets/1cad1850-11f7-4e6e-9a18-e823c8fad1d0)
![veh5](https://github.com/user-attachments/assets/0893ef6a-f1cb-4451-9449-1ef74b7a8150)
![veh6](https://github.com/user-attachments/assets/be18a44d-a024-45b6-949d-7efdf03790a3)





## Resturant Management System


## Introduction


The RESTaurant Project is a full-stack web application designed for restaurant management. It includes a backend server that provides RESTful APIs to clients and a web frontend for managing restaurant operations.

## Tech Stack


### Backend:


**🟢 Node.js** – High-performance event-driven server.<br>
**🔥 Express.js** – Lightweight and efficient backend framework.<br>
**🔄 Redis** – Used for caching (currently caches access_token).<br>
**🗄️ MySQL** – Persistent datastore for structured data.<br>
**🔑 JWT Authentication** – Secure access control for users.


### Frontend:


**⚛️ React.js / Vue.js** – Interactive and dynamic user interface. <br>
**🎨 Tailwind CSS / Bootstrap** – Modern and responsive styling.<br>
**🌐 Axios** – Handles API requests between frontend and backend.


## Features


**✔️ User Authentication** – Secure login/logout with JWT-based authentication.<br>
**✔️ Restaurant Menu Management** – Add, update, and remove menu items.<br>
**✔️ Order Processing** – Customers can place orders, and staff can manage them.<br>
**✔️ Reservation System** – Customers can book tables in advance.<br>
**✔️ Admin Dashboard** – View orders, manage inventory, and analyze reports.<br>
**✔️ Role-Based Access** – Different privileges for Admins, Managers, and Staff.<br>
**✔️ Fast Performance** – Redis caching improves API response times.

## ScreenShots

![image](https://github.com/user-attachments/assets/5b7082fe-aca9-4cd0-9be3-a7b7031eb7a1)

![image](https://github.com/user-attachments/assets/67f0fb2f-134e-49e9-a4e9-680e746e4e06)


## Restaurant Manager

### The Restaurant Manager has access to the following functionalities:

Login at localhost/manager/login

Manage dining tables at localhost/tables

Manage dishes at localhost/dishes

Manage coupons at localhost/coupons and push coupons to customers

View pending orders at localhost/orders

Accept/Deny pending orders

View accepted orders in the schedule table


## Installation & Setup

### Prerequisites:

Ensure you have Node.js, Redis, and MySQL installed on your system.

## Backend Setup:

### Clone the repository:

git clone https://github.com/your-username/resturant-management.git<br>
cd restaurant-management

## Install backend dependencies:
npm Install

## Frontend Setup:

### Clone the repository:

git clone https://github.com/your-username/resturant-management.git<br>
cd restaurant-management

## Install backend dependencies:
npm Install


## Contributing

### Contributions are welcome! Follow these steps:

### Fork the repository.

Create a new branch (feature-branch).<br>

Commit your changes.<br>

Push to your branch.

## License

This project is licensed under the MIT License.

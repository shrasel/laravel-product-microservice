# Laravel Product Microservice

This repository contains a microservice-based architecture for managing products using Laravel. The project is designed to provide a scalable and modular solution for handling various product-related tasks within a larger system.

## Features

- **Microservice Architecture:** The project is built using a microservices architectural pattern, allowing for independent development and deployment of different components.

- **Product Management:** Manage product information, including details like name, description, price, and availability.

- **RESTful API:** The microservices offer a RESTful API for communication between different components, making it easy to integrate into various systems.

- **Database Abstraction:** Each microservice has its own database, ensuring separation of concerns and data isolation.

## Getting Started

Follow these instructions to get the project up and running on your local machine for development and testing purposes.

### Prerequisites

- PHP >= 7.4
- Composer
- Docker (optional, for database setup)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/shrasel/laravel-product-microservice.git
   cd laravel-product-microservice
```

### Migrate and Seed the Database

If you want to seed 1000 record as dummy data then just run the fillowing command.

```
php artisan db:seed
```

## Installation

### Install Dependencies

```
composer install
```

### **Configure the Environment**
Duplicate .env.example to .env and customize the environment variables as needed.


### Migrate and Seed the Database

If you want to seed 1000 record as dummy data then just run the fillowing command.

```
php artisan migrate --seed
```

### Usage

Start the Laravel development server:

```
php artisan serve
```

Access the API documentation and endpoints via http://localhost:8000.

### Contributing
Contributions are welcome! Please follow these guidelines when making pull requests:

- Fork the repository and create a new branch.
- Make your changes and test thoroughly.
- Submit a pull request, including a detailed description of your changes.

# **Laravel Product Microservice**

This repository serves as a comprehensive guide for setting up and using a microservice-based architecture for product management using Laravel. The architecture is designed to establish a scalable and modular solution that seamlessly handles various tasks related to products within a broader system.

## **Features**

- **Microservice Architecture:** The project embodies a microservices architectural pattern, enabling independent development and deployment of distinct components.

- **Product Management:** Effectively manage essential product information, encompassing attributes such as name, description, price, and availability.

- **RESTful API:** The microservices furnish a RESTful API that facilitates communication across diverse components, simplifying integration into various systems.

- **Database Abstraction:** Each microservice is equipped with its dedicated database, guaranteeing a clear separation of concerns and ensuring data isolation.

## **Getting Started**

Follow these guidelines to promptly set up and initiate the project on your local machine, specifically for development and testing purposes.

### **Prerequisites**

Make sure the following prerequisites are satisfied:

- PHP version >= 7.4
- Composer
- Docker (optional, for streamlined database setup)

### **Installation**

1. Clone the repository:

```bash
git clone https://github.com/shrasel/laravel-product-microservice.git
cd laravel-product-microservice
```

2. Install Dependencies:

Execute the subsequent command to install the required project dependencies:

```bash
composer install
```

3. Configure the Environment:

Replicate `.env.example` to `.env` and tailor the environment variables as per your necessities.

4. Migrate and Seed the Database:

If you wish to populate the database with 1000 sample records, execute the following command:

```bash
php artisan migrate --seed
```

### **Usage**

Initiate the Laravel development server:

```bash
php artisan serve
```

Access the API documentation and endpoints through the following URL: [http://localhost:8000](http://localhost:8000).

### **Contributing**

Contributions are enthusiastically encouraged! If you plan to make a pull request, kindly adhere to these guidelines:

1. Fork the repository and create a new branch.
2. Integrate your modifications and rigorously test them.
3. Submit a pull request, accompanied by an elaborate account of your alterations.

Feel free to contribute and help enhance this microservice-based product management solution. Your input is invaluable in refining this project further.

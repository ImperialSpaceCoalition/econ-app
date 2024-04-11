# ECON-APP

## Introduction

This project is a functional Express.js API designed to manage categories, products, and tags using Sequelize as the ORM (Object-Relational Mapping) tool for MySQL databases.

## Installation

To set up the project locally, follow these steps:

1. Clone the repository from GitHub:

git clone <repository-url>



2. Navigate to the project directory:

cd <project-directory>



3. Install dependencies using npm:

npm install

4. Create an environment variable file (.env) in the root directory of the project and add the following variables:

DB_NAME=<your-database-name>
DB_USER=<your-mysql-username>
DB_PASSWORD=<your-mysql-password>


## Usage

1. After setting up the environment variables, you can proceed to create the database schema and seed it with test data using the following commands:

npm run schema
npm run seed



2. Once the database is created and seeded, start the server by running:

npm start



3. The server will be started, and the Sequelize models will be synced with the MySQL database.

4. You can now use Insomnia Core or any other API testing tool to access the API endpoints:

- GET `/api/categories`: Retrieves data for all categories.
- GET `/api/products`: Retrieves data for all products.
- GET `/api/tags`: Retrieves data for all tags.

- POST `/api/categories`: Creates a new category.
- POST `/api/products`: Creates a new product.
- POST `/api/tags`: Creates a new tag.

- PUT `/api/categories/:id`: Updates an existing category by ID.
- PUT `/api/products/:id`: Updates an existing product by ID.
- PUT `/api/tags/:id`: Updates an existing tag by ID.

- DELETE `/api/categories/:id`: Deletes a category by ID.
- DELETE `/api/products/:id`: Deletes a product by ID.
- DELETE `/api/tags/:id`: Deletes a tag by ID.

## Contributing

Contributions to this project are welcome! 

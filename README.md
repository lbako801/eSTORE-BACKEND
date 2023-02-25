# eSTORE-BACKEND
eSTORE-BACKEND is a powerful backend application that provides APIs to manage an eCommerce store's categories, products, and tags. The application is built using Node.js and Express, and uses Sequelize as an ORM to interact with a MySQL database. With this application, you can easily create, read, update, and delete categories, products, and tags to power your online store. The application provides a flexible and scalable platform for eCommerce businesses to manage their store inventory, and integrates seamlessly with a variety of front-end applications.

# Installation
To install the dependencies for this project, run the following command in the root directory:

 - ```npm install```  

Before running the application, you'll need to set up a MySQL database and create a .env file in the root directory with the following content:


  ```DB_NAME=your_database_name```  
  ```DB_USER=your_database_user```  
  ```DB_PASSWORD=your_database_password```

To create the database tables, run the following command and enter your database username and password:

 - ```mysql -u your_database_user -p```

Then you will want to either run the schema.sql file. This can be done in the root directory or in the database directory.

If root directory run:

 - ```source ./db/schema.sql```

If database directory run:

 - ```source schema.sql```

To seed the database with sample data, run the following command:

 - ```npm run seed```

To start the server, run the following command:

 - ```npm start```

# Features
 - Create, read, update, and delete products, categories, and tags
 - Filter products by category or tag
 - Pagination support for retrieving products
 - Error handling for invalid requests

# Screenshots

# Demo

A live demo of this API is available at this link: 

# Contact
For any questions or comments, please reach out to here.
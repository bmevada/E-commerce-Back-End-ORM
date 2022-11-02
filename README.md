# E-Commerce Back End (ORM)

## Background

Internet retail, also known as **e-commerce**, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes.

A back end has been built for an e-commerce site by the availble modifying starter code. This has been configured with a working Express.js API to using Sequelize to interact with a MySQL database.

## Links to deployed application

[Link to deployed working application]:

[Link to Github]:

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN the manager adds the database name, MySQL username, and MySQL password to an environment variable file
THEN the manager is able to connect to a database using Sequelize
WHEN the manager enters schema and seed commands
THEN a development database is created and is seeded with test data
WHEN the manager enters the command to invoke the application
THEN the server is started and the Sequelize models are synced to the MySQL database
WHEN the manager opens API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN the manager tests API POST, PUT, and DELETE routes in Insomnia
THEN the manager is able to successfully create, update, and delete data in the database
```

## Mock-Up

The following video shows an example of the application being used from the command line:


## Deployed Application
  - GET tags

  - GET Categories

  - GET All Products

  - GET tag by id

  - GET Category by ID

  - GET One Product

  - DELETE Category by ID

  - CREATE Category

  - UPDATE Category
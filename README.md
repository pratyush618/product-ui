# Product Management System

A simple web application for managing products.

## Table of Contents
- [Description](#description)
- [Backend Repo for this UI](https://github.com/pratyush618/Product-Management-Backend)
- [Features](#features)
- [API Endpoints](#api-endpoints)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Backend Repository](https://github.com/pratyush618/Product-Management-Backend)

## Description

This project is a Product Management System implemented using React.js. It allows users to add, edit, and delete products. The user interface is built with a responsive navigation bar and clean forms for adding and editing products.

## Features

- View a list of all products on the home page.
- Add new products with details like name, description, price, and status.
- Edit existing products.
- Delete products from the list.

## API Endpoints

- **GET /api/products**: 
  - *Description*: Get a list of all products.

- **GET /api/products/:id**: 
  - *Description*: Get details of a specific product.
  - *Parameters*:
    - `id`: Product ID

- **POST /api/products**: 
  - *Description*: Add a new product.
  - *Request Body*:
    - *Example*:
      ```json
      {
        "productName": "Product Name",
        "description": "Product Description",
        "price": 19.99,
        "status": "Active"
      }
      ```

- **PUT /api/products/:id**: 
  - *Description*: Update details of a specific product.
  - *Parameters*:
    - `id`: Product ID
  - *Request Body*:
    - *Example*:
      ```json
      {
        "productName": "Updated Product Name",
        "description": "Updated Product Description",
        "price": 29.99,
        "status": "Inactive"
      }
      ```

- **DELETE /api/products/:id**: 
  - *Description*: Delete a specific product.
  - *Parameters*:
    - `id`: Product ID

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/product-management-system.git
```

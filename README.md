# PHP Facturation System CotizaYa

![Project Logo](https://github.com/Bryan18201/cotizador_php/assets/80865397/917925e5-c99c-483b-b086-08ab24ae3e3b)

A simple and flexible PHP-based Facturation System for managing invoices, clients, and payments.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
   - [Installation](#installation)
4. [Usage](#usage)
   - [Basic Functionality](#basic-functionality)
5. [Configuration](#configuration)
6. [Contributing](#contributing)
7. [License](#license)

## Introduction

The PHP Facturation System is a web-based application designed to simplify the process of creating and managing invoices, tracking clients, and recording payments. It provides an intuitive user interface and is highly customizable to meet various business needs.

## Features

- **Invoice Management**: Create, view, edit, and send invoices effortlessly.
- **Client Management**: Maintain a database of clients with contact details.
- **Payment Tracking**: Record payments and track outstanding balances.
- **Security**: Built-in security measures to protect your data.

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- PHP (>= 7.0)
- Web server (e.g., Apache, Nginx, WampServer, Xampp)
- Composer (for managing PHP dependencies)

  ### Installation

To install the PHP Facturation System, follow these steps:

1. Clone the repository:

   ```shell
   git clone https://github.com/Bryan18201/cotizador_php
   ```

2. Navigate to the project directory:
 
    ```shell
    cd cotizador_php
    ```
3. Install PHP dependencies using Composer:

   ```shell
   composer install
   ```
4. Start the PHP development server:

   ```shell
   php artisan serve 
   ```
   or use your favorite local server like Xampp and Wamp Server

5. Open the localhost

## Usage
### Basic Functionality

  • **Create concept:** fill in the first column to add a product or service, you can select the quantity and the unit price of the product.
    
  • **Customer information:** Fill in the second column with the customer's information.

  • **Generate quote:** in the right column you can generate the pdf and download it.

## Configuration

Go to folder app and open config.php 

In the followings lines of code: 

```shell
  // Customize
define('APP_NAME'  , 'Cotiza Ya!'); // The app name
define('APP_EMAIL' , 'bryann1820@gmail.com'); // The email address of the company sending the quotation
define('TAXES_RATE', 18); // That it is a percentage
define('SHIPPING'  , 99.50); // The price of shipping
```

## Contributing

If you want to contribute to this project, follow these steps:

1-Fork the repository.

2-Create a new branch for your contribution.

3-Make your changes and improvements.

4-Submit a Pull Request.

Remember to replace placeholders like `yourusername`, `/path/to/logo.png`, and adapt the content to your specific project. Additionally, you can include sections on troubleshooting, testing, and acknowledgments if necessary. The goal is to provide clear and concise information to users and potential contributors.

## License
This project is licensed under the MIT License - see the LICENSE file for details.








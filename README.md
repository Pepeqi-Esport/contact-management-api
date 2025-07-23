# Contact Management API Documentation

## Overview

This document outlines the setup and structure of Contact Management API. This apps are using :
* Express js as main framework
* MySql for database
* JWT for authentication
* Joi for request validator
* Prisma for ORM

## System Requirements

* Node Js 20.0 or higher
* MySQL 5.7 or higher
* Composer for dependency management

## Installation Steps

1. **Clone the Repository**

   Clone the project and move to project directory

```bash
   https://github.com/Pepeqi-Esport/contact-management-api.git
   ```

2. **Install Dependencies**

```bash
   yarn
   ```

3. **Setup Environment**
   
   Copy the `.env.example` file to `.env` and update the database and other configurations as necessary.

```bash
   cp .env.example .env
   ```

4. **Generate Prisma**

```bash
   npx prisma generate
   ```

5. **Run Migration**

```bash
   npx prisma migrate dev
   ```

6. **Run Application in Development**

```bash
   yarn dev
   ```

## Contributing

Contributions to the Contact Management API project are welcome.

## License

This Contact Management API is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

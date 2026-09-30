# Surevice Service Marketplace

Surevice is an academic home-services marketplace built with PHP and Microsoft SQL Server. It supports separate customer, service-provider, and administrator workflows for browsing services, managing listings, handling bookings, reviewing accounts, and related marketplace operations.

## Core Features

### Customers
- Registration and login
- Service browsing
- Booking workflows
- Profile/account management

### Service Providers
- Provider dashboard
- Service creation and management
- Multiple service images
- Service-category assignment
- Booking management

### Administrators
- Administrative dashboard
- User account review and status management
- Booking oversight
- Verification workflows
- Billing-related administration

## Authentication

The application uses PHP sessions. Passwords are stored using `password_hash()` and verified with `password_verify()`.

## Technology Stack

PHP, Microsoft SQL Server, SQLSRV PHP driver, HTML, CSS, JavaScript, Bootstrap

## Project Structure

```text
surevice-service-marketplace/
├── assets/
├── components/
├── dashboard/
├── user/
├── utils/
├── index.php
├── login.php
└── register.php
```

## Database Configuration

Database connection details are loaded from `utils/config.php`, which is excluded by `.gitignore`.

## Security Notes

Additional hardening is recommended before production use, including server-side authorization checks on every administrative action, CSRF protection, stronger file-upload validation, centralized safe error handling, and consistent input validation.

## Academic Use

This project was created for academic purposes.

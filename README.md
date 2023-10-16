# E-commerce-Back-End

## Overview

This project is the backend implementation of an ecommerce platform. It provides the necessary infrastructure to handle product listings, user authentication, shopping cart management, and order processing.

## Video 

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Configuration](#configuration)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Database Schema](#database-schema)
- [Authentication](#authentication)
- [Error Handling](#error-handling)
- [Testing](#testing)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Features

- User authentication and authorization
- Product management (CRUD operations)
- Shopping cart functionality
- Order processing
- User profile management
- Category and brand management
- Search functionality
- Pagination and filtering options
- Error handling and validation

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose
- JSON Web Tokens (JWT)
- bcrypt (for password hashing)
- Mocha and Chai (for testing)
- ...

## Getting Started

### Prerequisites

- Node.js (version >= 12)
- MongoDB
- ...

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/ecommerce-backend.git
cd ecommerce-backend
```

2. Install dependencies:

```bash
npm install
```

### Configuration

1. Create a `.env` file in the root directory and add the following variables:

```env
PORT=3000
MONGODB_URI=mongodb://localhost:27017/ecommerce
SECRET_KEY=mysecretkey
```

Replace `MONGODB_URI` and `SECRET_KEY` with your own values.

## Usage

To start the server, run:

```bash
npm start
```

The server will be running at `http://localhost:3000`.

## API Endpoints

See [API documentation](API.md) for a detailed list of endpoints and their usage.

## Database Schema

![Database Schema](schema.png)

## Authentication

This project uses JWT for authentication. When a user logs in or registers, a token is generated and sent in the response. This token should be included in the headers of subsequent requests to access protected routes.

## Error Handling

Errors are handled through custom middleware to provide meaningful error messages in the API responses. Detailed error messages are logged for debugging purposes.

## Testing

To run the tests, use:

```bash
npm test
```

## Deployment

Additional steps for deploying the application (e.g., using Docker, setting up a production environment) can be added here.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
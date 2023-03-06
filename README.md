# React E-Commerce App
https://youtu.be/iWGLs85kahU

This project is a web-based e-commerce application built using React, Sass, and Strapi CMS. I built this project as part of my learning journey with these technologies. The application allows users to browse products, add them to cart, and purchase them using Stripe payment gateway.

## Getting Started

### Prerequisites

- Node.js
- Strapi CMS
- Stripe API keys (Test or Live)

### Installation

1. Clone the repository and navigate to the project directory.
2. Install the dependencies using `npm install`.
3. Set up the environment variables in `.env` file located in the `frontend` directory:
  - `REACT_APP_STRIPE_DEV_APP_KEY`: Strapi cms API key for development environment.
  - `REACT_APP_STRIPE_APP_DEV_URL`: URL of the backend server for development environment.
  - `REACT_APP_STRIPE_PUBLISHABLE_KEY`: Stripe publishable key for payments.
4. Run the frontend using `npm start` command in the `frontend` directory.
5. Set up the environment variables in `.env` file located in the `backend` directory:
  - `HOST`: Server hostname.
  - `PORT`: Server port number.
  - `APP_KEYS`: Strapi app keys.
  - `API_TOKEN_SALT`: Salt for API tokens.
  - `ADMIN_JWT_SECRET`: Secret for admin JWT token.
  - `TRANSFER_TOKEN_SALT`: Salt for transfer tokens.
  - `DATABASE_CLIENT`: Database client.
  - `DATABASE_FILENAME`: Database filename.
  - `JWT_SECRET`: Secret for JWT token.
  - `STRIPE_KEY`: Stripe API key for payments.
  - `CLIENT_URL`: URL of the frontend server.
6. Run the backend using `npm run develop` command in the `backend` directory.

## Usage

Open the web browser and navigate to the URL of the frontend server. Browse products, add them to cart, and proceed to checkout. The Stripe payment gateway will be used to process the payment.

## Contributing

Contributions are welcome. Please open an issue or submit a pull request.


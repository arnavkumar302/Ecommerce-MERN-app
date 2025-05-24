# eComerce - MERN Ecommerce Application

This repository contains a full-stack ecommerce application built using the MERN stack (MongoDB, Express, React, Node.js). The application is divided into two main components:

- **Backend**: Built with Node.js and Express, located at [eComerce/MERN-ecommerce-backend](eComerce/MERN-ecommerce-backend).
- **Frontend**: Built with React and integrated with Stripe for payment processing, located at [eComerce/MERN-ecommerce-Frontend](eComerce/MERN-ecommerce-Frontend).

## Features

- **User Authentication & Management**  
- **Product Browsing & Search**  
- **Shopping Cart & Wishlist**  
- **Secure Payment Processing with Stripe**  
- **Order Tracking & Payment Status Updates**  
- **RESTful APIs for Backend Operations**

## Prerequisites

- Node.js (v12 or above)
- npm or yarn
- MongoDB database
- Stripe account for payment integration

## Installation

### Backend

1. Navigate to the backend directory:

    ```sh
    cd eComerce/MERN-ecommerce-backend
    ```

2. Install dependencies:

    ```sh
    npm install
    ```

3. Create a `.env` file and configure your environment variables (refer to [eComerce/MERN-ecommerce-backend/.env](eComerce/MERN-ecommerce-backend/.env)).

4. Start the server:

    ```sh
    npm start
    ```

### Frontend

1. Navigate to the frontend directory:

    ```sh
    cd eComerce/MERN-ecommerce-Frontend
    ```

2. Install dependencies:

    ```sh
    npm install
    ```

3. Configure your environment variables (e.g., API endpoints, Stripe public key).

4. Start the development server:

    ```sh
    npm start
    ```

## Default Admin Credentials

For accessing the admin panel, use the following default credentials:

- **Admin Email**: admin@gmail.com
- **Admin Password**: Shankha123

## Payment Integration

The payment process is handled in the frontend through the [CheckoutForm component](eComerce/MERN-ecommerce-Frontend/src/pages/CheckoutForm.js) which utilizes the Stripe API. Users are redirected appropriately based on payment status.

## Deployment

- **Frontend Build**:  
    Run the build script in the frontend directory:
    ```sh
    npm run build
    ```

- **Backend Deployment**:  
    Use your preferred hosting service. A sample deployment configuration is available in [eComerce/MERN-ecommerce-backend/vercel.json](eComerce/MERN-ecommerce-backend/vercel.json).

- Make sure to update the environment variables accordingly for production.

## Running Tests

Both backend and frontend projects include unit tests. Refer to the respective `package.json` files under [eComerce/MERN-ecommerce-backend](eComerce/MERN-ecommerce-backend) and [eComerce/MERN-ecommerce-Frontend](eComerce/MERN-ecommerce-Frontend) for test scripts.

## .gitignore

The repository uses a [`.gitignore`](eComerce/.gitignore) file to exclude unnecessary files and folders.

## Technologies

- **Backend**: Node.js, Express, MongoDB, Mongoose
- **Frontend**: React, Redux, Stripe, Tailwind CSS
- **Authentication**: Passport.js, JWT

## Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request with your improvements.

## License

This project is licensed under the MIT License.

## Contact

For questions or feedback, please open an issue in the repository.
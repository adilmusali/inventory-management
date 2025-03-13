# Inventory Management System

This project is an Inventory Management System built using a modern web stack. It includes a client-side application built with Next.js and a server-side application using Express.js and Prisma ORM for database management.

## Features

- **User Management**: Manage users with functionalities to add, update, and delete users.
- **Product Management**: Manage products including adding, updating, and deleting products.
- **Sales Tracking**: Track sales with detailed summaries and analytics.
- **Expense Tracking**: Track expenses with detailed summaries and analytics.
- **Dashboard**: A comprehensive dashboard displaying key metrics and summaries.

## Technologies Used

### Client-Side

- **Next.js**: A React framework for server-side rendering and static site generation.
- **React**: A JavaScript library for building user interfaces.
- **Redux Toolkit**: For state management.
- **Tailwind CSS**: For styling.
- **Recharts**: For data visualization.
- **TypeScript**: For static type checking.

### Server-Side

- **Express.js**: A web application framework for Node.js.
- **Prisma**: An ORM for database management.
- **PostgreSQL**: The database used for storing data.
- **TypeScript**: For static type checking.

## Getting Started

### Prerequisites

- Node.js
- PostgreSQL

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/inventory-management.git
    cd inventory-management
    ```

2. Install dependencies for both client and server:

    ```bash
    cd client
    npm install
    cd ../server
    npm install
    ```

3. Set up environment variables:

    Create a `.env` file in the `server` directory and add your database URL:

    ```env
    DATABASE_URL=your_database_url
    ```

4. Run database migrations and seed data:

    ```bash
    cd server
    npx prisma migrate deploy
    npm run seed
    ```

### Running the Application

1. Start the server:

    ```bash
    cd server
    npm run dev
    ```

2. Start the client:

    ```bash
    cd client
    npm run dev
    ```

3. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## Project Structure

### Client

- **`src/app`**: Contains the main application components and pages.
- **`src/state`**: Contains Redux state management logic.
- **`src/components`**: Reusable UI components.
- **`src/styles`**: Global styles and Tailwind CSS configuration.

### Server

- **`src`**: Contains the main server application code.
- **`prisma`**: Contains Prisma schema and migration files.
- **`routes`**: Contains route handlers for different API endpoints.
- **`seedData`**: Contains JSON files for seeding the database.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## Contact

For any questions or inquiries, please contact [adil.musali.1602@gmail.com](mailto:adil.musali.1602@gmail.com).

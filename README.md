## Installation Guide

### Prerequisites

1. **Install PostgreSQL**
   - Download and install PostgreSQL from the [official website](https://www.postgresql.org/download/).
   - Ensure PostgreSQL is running and accessible from your command line.

2. **Install Node.js and npm**
   - Download and install Node.js (which includes npm) from the [official website](https://nodejs.org/).
   - Verify the installation:
     ```sh
     node -v
     npm -v
     ```

3. **Install Nodemon**
   - Nodemon is a utility that automatically restarts your node application when file changes are detected. Install it globally using npm:
     ```sh
     npm install -g nodemon
     ```

### How to Start

1. **Set Up PostgreSQL Database**
   - Create a new database and user:
     ```sh
     psql -U postgres
     ```
     ```sql
     CREATE DATABASE perntodo;
     CREATE USER inventory_user WITH ENCRYPTED PASSWORD 'password';
     GRANT ALL PRIVILEGES ON DATABASE perntodo TO inventory_user;
     \q
     ```

2. **Clone the Repository**
   ```sh
   git clone https://github.com/kinloveko/PERN-STACK-TODO-.git
   cd PERN-STACK-TODO-

3. **Install Dependencies**

   cd client && npm install

5. Start the Application
   Run the server using Nodemon in cmd:
    ```sh
   -cd server && nodemon index
    ```
   Open new terminal:
    ```sh
   -cd client && npm run start
    ```

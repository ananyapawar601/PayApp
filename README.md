# PayApp

PayApp is a feature-rich payment application designed to facilitate seamless and secure transactions between users. It provides an intuitive interface for managing payments, tracking transaction history, and ensuring the security of financial data. Built with a focus on simplicity and efficiency, PayApp offers a robust backend integrated with modern payment gateways, providing a reliable platform for personal and business use.

## Features
- **User Registration & Authentication**: Secure user registration and login system with password hashing and authentication.
- **Transaction Management**: Easily send and receive payments, with real-time transaction updates.
- **Payment History**: Access detailed transaction history, including timestamps, amounts, and transaction statuses.
- **Integration with Payment Gateways**: Support for various payment gateways to process payments securely.
- **Security**: Implements best practices for secure data handling and encryption, ensuring user data privacy.

## Technology Stack
- **Frontend**: HTML, CSS, and JavaScript for an intuitive and responsive user interface.
- **Backend**: Node.js/Express.js for server-side logic and API management.
- **Database**: MongoDB for secure storage of user and transaction data.


To set up the PayApp MERN project from the GitHub repository you mentioned, follow these detailed steps:

### 1. Clone the Repository

```bash
git clone https://github.com/ananyapawar601/PayApp.git
cd PayApp
```

### 2. Set Up the Backend

1. **Navigate to the Backend Directory:**
   ```bash
   cd backend
   ```

2. **Create a `.env` File:**
   Add your MongoDB URL and Paytm credentials to a `.env` file:
   ```env
   MONGODB_URL=your_mongodb_url_here
   ```

3. **Install Dependencies:**
   ```bash
   npm install
   ```

4. **Start the Backend Server:**
   ```bash
   npm start
   ```

### 3. Set Up the Frontend

1. **Navigate to the Frontend Directory:**
   ```bash
   cd ../frontend
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Start the Frontend Development Server:**
   ```bash
   npm run dev
   ```

### 4. Test the Backend

1. **Import Postman Collection:**
   - Open Postman.
   - Click on "Import" and select the `Paytm.postman_collection.json` file from the `backend` directory (if it’s available) or ask for it if it’s not included.

2. **Run the Tests:**
   - Execute the requests in the Postman collection to test your backend.



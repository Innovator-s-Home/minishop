

# Ecommerce MERN Project


## Prerequisites

Before you begin, make sure you have the following software installed on your machine:
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) (Node Package Manager)

# Clone and Setup

## Clone the repository:

```bash
git clone 
```


# Install required packages and start the server:



## Backend Setup

### Node.js Backend

Install required packages and start the server:

```bash
cd backend
npm i
npm start

```

#### Configure The .env file
To generate the activation secret
https://www.vultr.com/resources/secure-password-generator/

To connect the database
https://www.mongodb.com/

To connect the payment gateway
https://stripe.com/

To upload the media files
https://cloudinary.com/

The Node.js backend server should now be running on http://localhost:8000.

#### Note
Check the cors origin in app.js, set up to the local client server and the remote as per the need




## Frontend Setup

### React.js Frontend

Install React.js packages and start the development server:

```bash
cd frontend
yarn

```

The React.js frontend development server should now be running on http://localhost:3000.

## Web Socket Setup

```bash
cd socket
npm i
npm run start

```



That's it! You have successfully set up the project on your local machine. Feel free to explore the website. If you encounter any issues, please refer to the documentation and feel free to reach out to us
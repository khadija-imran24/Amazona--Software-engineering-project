# Amazona ECommerce Website


Welcome to my React and Node tutorial to build a fully-functional e-commerce website exactly like amazon. Open your code editor and follow me for the next hours to build an e-commerce website using MERN stack (MongoDB, ExpressJS, React and Node.JS).


## Run Locally



### Setup MongoDB

- Local MongoDB
  - Install it from [here](https://www.mongodb.com/try/download/community)
  - Create .env file in root folder
  - Set MONGODB_URL=mongodb://localhost/amazona  
- Atlas Cloud MongoDB
  - Create database at [https://cloud.mongodb.com](https://cloud.mongodb.com)
  - Create .env file in root folder
  - Set MONGODB_URL=mongodb+srv://your-db-connection

### Run Backend

```
$ npm install
$ npm start
```

###  Run Frontend

```
# open new terminal
$ cd frontend
$ npm install
$ npm start
```

###  Seed Users and Products

- Run this on chrome: http://localhost:5000/api/users/seed
- It returns admin email and password
- Run this on chrome: http://localhost:5000/api/products/seed
- It creates 6 sample products

### Admin Login

- Run http://localhost:3000/signin
- Enter admin email and password and click signin
### functionality
User can buy products and give feedback etc where admin can add delete, and view products etc.

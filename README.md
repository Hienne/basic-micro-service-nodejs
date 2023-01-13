# basic-micro-service-nodejs
Setup basic microservice in NodeJS
Project uses:
  express
  nodemon
  fast-gateway: to setup routing to each service

How to build:
  Accessing each folder, after that, run the command: "npm run start"
  After running 3 apps (you need to run the api-gateway app last), you can connect to the routes:
    localhost:9001/order/order-list
    localhost:9001/payment/payment-list

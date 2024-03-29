# browserstack-demo-app
A shopping application to demonstrate real-world usage of BrowserStack testing methods, patterns, and workflows.

## Features
🛠 Built with [React](https://reactjs.org/), [Next](https://nextjs.org/)  
⚡️ Zero database dependencies  
🚀 Full-stack [Next](https://nextjs.org/)/[React](https://reactjs.org/) application with real-world features  
👮‍♂️ Local Authentication  


## Getting Started

BrowserStack Demo App is a full-stack Next/React application.

The app is bundled with [offers data](./src/constants/offers.json), [orders data](./src/constants/orders.json) and [products data](./src/constants/products.json) that contains everything you need to start using the app and run tests out-of-the-box.

The app also includes product images which are stored in [public/static](./public/static) folder.

> 🚩 **Note**
>
> You can login to the app with any of the example users `image_not_loading_user, existing_orders_user or fav_user` . The default password for all users is `testingisfun99`.  


### Prerequisites
You can run this project via [Docker](https://www.docker.com/) or [Node.js](https://nodejs.org/en/) **version 12** installed on your machine.

### Installation with node

```shell
yarn install
```

### Run the app

```shell
yarn dev
```

visit `http://localhost:3000/`

### Open Swagger UI

visit `http://localhost:3000/swagger`

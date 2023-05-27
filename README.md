# Liverr (Fiverr Clone)

1. Dual Account System: The Fiverr clone project includes a comprehensive buyer and seller account system, allowing users to create distinct profiles based on their roles and requirements.

2. Gig Creation and Purchase: Sellers are provided with the ability to create gigs, which are service offerings they can provide to potential buyers. Buyers can easily browse through the available gigs and make purchases using the secure Stripe payment gateway.

3. Review and Rating System: After purchasing a gig, buyers have the option to provide feedback by leaving a review and rating the seller's gig using a 5-star scale. This allows for transparent evaluation of the seller's performance and helps other buyers make informed decisions.

4. Centralized Gig Repository: The Fiverr clone project incorporates a dedicated page where all sellers' gigs are listed, allowing buyers to explore and compare various service offerings conveniently. This page acts as a hub for buyers to discover a wide range of services.

5. Chat Section: To facilitate effective communication, a chat section is implemented within the platform. After a gig purchase, buyers and sellers can interact with each other, discussing project details, providing updates, and addressing any concerns or questions. This enhances collaboration and ensures a seamless experience for both parties involved.

**This is an ongoing project, it will be tested with Jest, updation is coming soon.**

## Client App is Bootstrapped with

- react
- cloudinary for image upload
- axios for api requests
- sass 1.58.3
- react-router-dom 6.8.2
- @tanstack/react-query 4.29.5
- @stripe/stripe-j 1.52.1 for payments

## Server App is Bootstrapped with

- bycrypt 5.1.0 for password hashing
- cors 2.8.5 for cross origin config
- jsonwebtoken 9.0.0 for authentication
- mongoose 7.0.1
- express 4.18.2
- stripe 12.3.0

## Getting started

1. You need node installed globally on your local machine

```
$ git clone git@github.com:Afrin127329/full-stack-fiverr-app.git

```

#### Server Configuration

1. You need node installed globally on your local machine
2. Add a .env file in the server directory to add these environment variables for checking all of the functionalities of the app:
   - MONGO
   - JWT_KEY
   - STRIPE

```
$ cd server
$ npm install
$ npm start
```

#### Client Configuration

- Add a .env file in the client directory to add these environment variables for running the app successfully:
  - VITE_UPLOAD_API
  - VITE_CLIENT=http://localhost:5173
  - VITE_SERVER=http://localhost:8000

```
$ cd client
$ npm install
$ npm run dev
```

## 🤝 Contributing

At this time, I regret to inform you that contributions are not being accepted. However, I warmly welcome you to submit any issues or feature requests you may have. Your valuable input will be greatly appreciated.

## 😃 Sign up on [Liverr](https://full-stack-fiverr-app.vercel.app/) and give it a try. Would love to have a feedback

## Authors

**Afrin Nahar**

- Github: [@Afrin127329](https://github.com/Afrin127329)
- LinkedIn: [Afrin Nahar](https://www.linkedin.com/in/afrin-nahar-b849ba1a9/)
- Twitter: [@AfrinNahar10](https://twitter.com/AfrinNahar10)

### Show your support

- Give a ⭐ if you like this project

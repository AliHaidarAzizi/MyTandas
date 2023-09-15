# MyTandas

# Public Toilet Review App

## Description

This is an open-source app designed to review and rate public toilets. The main objective of this app is to encourage owners and users to maintain cleanliness in public toilets. It also features navigation to the toilets and a tipping feature to contribute or donate to the owners.

## Tech Stack

This project uses the MERN stack:
- **MongoDB**: A source-available cross-platform document-oriented database program for storage.
- **Express.js**: A back end web application framework for Node.js for building web applications and APIs.
- **React**: A JavaScript library for building user interfaces.
- **Node.js**: A JavaScript runtime built on Chrome's V8 JavaScript engine.

## Features

- **Toilet Reviews and Ratings**: Users can review and rate public toilets based on their cleanliness, facilities, and overall experience.
- **Navigation**: The app provides directions to the nearest public toilets.
- **Tips and Donations**: Users can contribute or donate to the toilet owners to support maintenance and cleanliness.

## Architecture

1. **Frontend (React.js)**: The frontend of your application will be built using React.js. You'll have various components such as:
   - Home: Where users can see a list of toilets, search for toilets, and navigate to other parts of the app.
   - Toilet Details: Where users can see details about a toilet, including reviews and ratings.
   - Review Form: Where users can submit their reviews and ratings.
   - Navigation: Where users can get directions to a toilet.
   - Donation: Where users can make a donation.

2. **Backend (Express.js & Node.js)**: Your server will be built with Express.js running on Node.js. It will expose APIs for the frontend to consume, such as:
   - GET /toilets: Fetch a list of toilets.
   - GET /toilets/:id: Fetch details about a specific toilet.
   - POST /reviews: Submit a review for a toilet.
   - GET /navigation/:id: Get directions to a toilet.
   - POST /donations: Make a donation.

3. **Database (MongoDB)**: MongoDB will be used to store data about toilets, reviews, and donations. You'll have collections such as:
   - Toilets: Stores data about each toilet.
   - Reviews: Stores user reviews and ratings for each toilet.
   - Donations: Stores donation data.

4. **User Authentication**: You might also want to consider adding user authentication so that users can create accounts, submit reviews, and make donations. This could be done using technologies like Passport.js or Firebase Authentication.

## Getting Started

### Prerequisites

List what software and libraries you will need and how to install them.

### Installation

Provide step by step series of examples that tell you how to get a development environment running.

## Usage 

After installing the app, users can create an account to access all features. Users can search for public toilets in their vicinity, view ratings and reviews, and get navigation directions. After visiting a toilet, users can leave their own rating and review. If they found the toilet well-maintained, they can leave a tip for the owner.

## Contributing

We encourage you to contribute to this project! Please check out the Contributing guidelines for guidelines about how to proceed.

### Contribution Guidelines

1. **Fork** the project on GitHub.
2. **Clone** the project locally into your machine.
3. **Commit** changes to your own branches
4. **Push** your work back up to your fork
5. Submit a **Pull request** so that we can review your changes

NOTE: Be sure to merge the latest from "upstream" before making a pull request!

### Best Practices 

- Write clear meaningful git commit messages.
- Always create PR to `dev` branch not `main`.
- Make sure your code lints.
- Issue that pull request!

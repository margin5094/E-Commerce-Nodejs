# Ecommerce Website (Node.js)

Welcome to the Ecommerce Website project! This web application is built using Express.js, Node.js, EJS, MongoDB, Mongoose, Nodemailer, SendGrid, PDFKit for bill generation, and Stripe for payment processing.


## Features

- User authentication and authorization.
- Product catalog and shopping cart functionality.
- Secure payment processing via Stripe.
- Generation and sending of PDF bills via Nodemailer and SendGrid.
- User-friendly interface with EJS templates.
- Database storage and retrieval of product and user data using MongoDB and Mongoose.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm installed.
- MongoDB installed and running.
- Stripe API keys (test and live) obtained.
- SendGrid API key obtained.

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/ecommerce-website.git


## Deployment

To deploy Ecommerce website, start by signing up for a Heroku account and installing the Heroku CLI. Initialize a Git repository ,create a `.gitignore` file to exclude unnecessary files, and commit your project to Git. Use the Heroku CLI to create a new Heroku app with a unique name, set your environment variables for configuration, and specify any necessary buildpacks. Finally, push the project to Heroku using `git push heroku master`, open the app with `heroku open`, and monitor logs with `heroku logs --tail`.
## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`STRIPE_SECRET_KEY`

`STRIPE_PUBLISHABLE_KEY`

`SENDGRID_API_KEY`


Open live link - https://lms-full-stack2-1z9u.vercel.app/
# Project Setup Guide

## Prerequisites

Before running this project, make sure you have the following installed:
- [Node.js](https://nodejs.org/en/download/) (Latest LTS version recommended)
- A code editor (VS Code recommended)

## Project Structure
This project consists of two main parts:
- Server (Backend)
- Client (Frontend)

⚠️ **Important**: Always deploy and run the server first before setting up the client.

## Server Setup

### 1. Required Services
You'll need to set up accounts and obtain API keys from the following services:

1. **MongoDB Atlas**
   - Register at [MongoDB Cloud](https://www.mongodb.com/cloud/atlas/register)
   - Create a cluster and obtain your MongoDB URI

2. **Cloudinary**
   - Sign up at [Cloudinary](https://cloudinary.com/users/register_free)
   - Get your cloud credentials

3. **Clerk**
   - Create an account at [Clerk](https://clerk.com/)
   - Set up authentication
   - Configure webhooks

4. **Stripe**
   - Register at [Stripe](https://dashboard.stripe.com/login)
   - Get your API keys

### 2. Deployment Steps
1. Push your project to GitHub
2. Deploy the backend on [Vercel](https://vercel.com/)
3. Once deployed, copy your backend URL
4. Configure the backend URL in:
   - Clerk webhooks
   - Stripe webhooks

## Client Setup

### 1. Installation
```bash
# Navigate to client directory
cd client

# Install dependencies
npm install
```

### 2. Configuration
1. Create a `.env` file in the client directory
2. Add your environment variables, including:
   - Backend URL (from server deployment)
   - Other required API keys

### 3. Running the Project
```bash
npm run dev
```

## Deployment
1. Ensure the server is deployed and running correctly
2. Deploy the client application
3. Verify all connections are working properly

## Support

If you encounter any issues:

- Contact support on [Instagram](https://instagram.com/hardik78278)


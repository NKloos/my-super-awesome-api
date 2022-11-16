# My Super Awesome API

> **Warning**  
> This is app is used for demonstration purposes only.

This is the backend repository for _my super awesome app_. It's built using NodeJS and ExpressJS. I mainly created it as a toy app to demonestrate a full-stack app deployment. Here's the tutorial [link](https://).

<sup>Frontend repo 👉 [kerolloz/my-super-awesome-app](https://github.com/kerolloz/my-super-awesome-app)</sup>

## Usage

You need a `.env` file with the following variables defined.
You can use the `.env.example` file as a template.

```bash
PORT=5000
MONGODB_URI=mongodb://localhost/your-database-name
JWT_SECRET_KEY=very-secret-key
SENDGRID_API_KEY=123
SENDGRID_FROM_EMAIL=your-email
FRONTEND_BASE_URI=http://localhost:3000
IMGBB_KEY=abc123
```

```bash
npm i            # install required dependencies
npm run dev      # start development server
npm run build    # build for production
```

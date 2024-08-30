# camphor

# Next.js Login Page

This is a simple **Login Page** built with Next.js. It includes validation, navigation, and role-based login for **Admin** and **Handler** roles.

## Features

- Simple and clean login UI.
- Role-based access:
  - **Admin**: email - `admin@gmail.com`, password - `admin`
  - **Handler**: email - `handler@gmail.com`, password - `handler`
- Redirects to respective dashboard pages upon successful login.
- Error handling for invalid credentials.

### Folder Structure

# Login Page (`/app/page.js`)

The login page includes two fields: `Email` and `Password`. Upon entering the correct credentials, the user is redirected to their respective dashboard (`Admin` or `Handler`). If the credentials are incorrect, an error message is displayed.

# User Flow

1. Users visit the login page at `localhost:3000`.
2. Upon entering the email and password:
   - **Admin** users are redirected to the `/admin` page.
   - **Handler** users are redirected to the `/handler` page.
3. If incorrect credentials are entered, an error message is displayed.

# Validation

- The login page uses `useState` to manage form data and errors.
- The role-based login uses dummy data for this example:
  - **Admin**: `admin@gmail.com` | `admin`
  - **Handler**: `handler@gmail.com` | `handler`

# Installation - npm install
Run the development server - npm run dev

Visit the login page at http://localhost:3000.



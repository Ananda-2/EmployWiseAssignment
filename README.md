# EmployWise Front End Assignment

This project is a React-based application that integrates with the [Reqres API](https://reqres.in/) to perform basic user management functions, including authentication, listing, editing, and deleting users.

---

## Features

### Level 1: Authentication Screen

- Allows users to log in using the following credentials:
  - **Email:** `eve.holt@reqres.in`
  - **Password:** `cityslicka`
- On successful login:
  - The token (returned by the API) is stored in local storage.
  - The user is redirected to the Users List page.

### Level 2: List All Users

- Displays a paginated list of users fetched from the `/api/users` endpoint.
- Shows user details:
  - First Name
  - Last Name
  - Avatar
- Includes pagination or lazy loading to navigate between user pages.

### Level 3: Edit, Delete, and Update Users

- **Edit:**
  - Clicking "Edit" opens a form pre-filled with the user’s data.
  - Users can update the first name, last name, and email.
  - Sends updates via the `PUT /api/users/{id}` endpoint.
- **Delete:**
  - Clicking "Delete" removes the user from the list.
  - Deletes are performed using the `DELETE /api/users/{id}` endpoint.
- Displays success or error messages based on API responses.

---

## Bonus Features

- Client-side search and filtering for users.
- Hosted on a NetLify
- Fully responsive UI for both desktop and mobile.

---

## Tech Stack

- **Frontend Framework:** React
- **HTTP Requests:** Fetch API
- **CSS Framework:** Tailwind CSS, lucide-react , or custom CSS
- **Routing:** React Router
- **API:** Reqres API ([Documentation](https://reqres.in/))

---

## Installation and Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Ananda-2/EmployWise-Assignment
   ```

## Live Demo Link

1. **Netlify host Link**
   ```bash
    https://employwise-assignment-ananda.netlify.app/
   ```

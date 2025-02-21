# Job Frontend

Job Frontend is a React-based application that serves as the frontend for the Job API Server. It provides a user-friendly interface for job management, including authentication and CRUD operations.

## Features:

- User authentication (Register, Login) with JWT.
- View, create, update, and delete job listings.
- Responsive UI with Styled Components.
- API integration using Axios.
- Redux Toolkit for state management.
- Notification system using React-Toastify.

## Tech Stack:

- **Frontend:** React `18.2.0`, React Router `6.6.1`
- **State Management:** Redux Toolkit `1.9.1`, React-Redux `8.0.5`
- **Styling:** Styled Components `5.3.6`, Normalize.css `8.0.1`
- **API Handling:** Axios `1.2.1`
- **Charts & UI Components:** Recharts `2.2.0`, React Icons `4.7.1`
- **Notifications:** React-Toastify `9.1.1`
- **Utilities:** Moment.js `2.29.4`

## Installation & Usage:

### 1. Clone the repository:

```bash
git clone https://github.com/MF-Vv/JOB-CLIENT.git
cd JOB-CLIENT
```

### 2. Install dependencies:

```bash
npm install
```

### 3. Start the development server:

```bash
npm start
```

### 4. Build the project for production:

```bash
npm run build
```

## Deployment:

To deploy the frontend, build the project and host it on a service like Vercel, Netlify, or any static file server.

```bash
npm run build
```

## API Reference:

This frontend communicates with the **Job API Server**.
For API documentation, please refer to the backend repository:

[Job API Server Repository](https://github.com/MF-Vv/JOB-API-SERVER)

## Deployment:

This API is deployed on Render:

```
https://job-api-server.onrender.com/api-docs
```

### Important Notice:

🚨 **Free-tier Limitation:** Since this API is hosted on a free account, the server may spin down due to inactivity, causing delays of up to 50 seconds when handling requests.

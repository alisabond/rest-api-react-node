<div align="center">

# React + Node.js REST API

</div>

A modern **monorepo** containing a full-stack web application with separate frontend and backend services.

##  Project Structure

```
Task_8/
├──  react-app-alisabond/     # React frontend application
├──  node-app-alisabond/      # Node.js + Express backend + SQLite DB
├──  package.json             # Root package configuration
└──  README.md                # This file
```

##  Technologies

### Frontend
- **React**
- **Create React App**

### Backend
- **Node.js**
- **Express.js**
- **SQLite**

##  Quick Start

>  **Note:** Each application can be run independently using instructions in their respective READMEs. The root scripts are provided for convenience only.

### 1️) Install Dependencies

```bash
# Install backend dependencies
cd node-app-alisabond && npm install && cd ..

# Install frontend dependencies
cd react-app-alisabond && npm install && cd ..
```

### 2️) Start Both Applications

```bash
npm start
```

This will launch both services concurrently:

-  **Frontend**: http://localhost:3000
- ️ **Backend**: http://localhost:5000

##  Individual Application Setup

For detailed setup instructions and API documentation, check the README files in each application directory:

-  [Frontend Documentation](./react-app-alisabond/README.md)
-  [Backend Documentation](./node-app-alisabond/README.md)

##  Development

The root package uses `npx concurrently` to run both applications simultaneously without adding global dependencies.


---

<div align="center">
Made with ❤️ for SoftServe Academy DevOps Task 8
</div>







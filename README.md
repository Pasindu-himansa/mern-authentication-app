<div align="center">
  <h1>MERN Authentication App</h1>
</div>

![home page](./images/homepage01.png)
![completed](./images/completed.png)
![update](./images/update.png)

### A full-stack authentication application built with **MongoDB, Express, React, and Node.js.** Designed as a clean, production-ready auth boilerplate that handles the heavy lifting of user identity, so you can focus on building your actual product on top of it.

### The backend exposes a secure REST API with user registration, login, and JWT-based protected routes. Passwords are never stored in plain text — they are salted and hashed using bcryptjs before hitting the database. Authentication tokens are signed with a secret key and validated on every protected request via a custom middleware layer.

### The frontend is built with React 19.2 and Vite, giving you an ultra-fast development experience with hot module replacement. Routing is handled by React Router DOM, API calls are managed through Axios, and the UI is styled with Tailwind CSS 4, keeping the interface clean, responsive, and easy to customize.

### Built with

- [![React][React.js]][React-url]
- [![Vite][Vite.js]][Vite-url]
- [![TailwindCSS][TailwindCSS]][Tailwind-url]
- [![Node.js][Node.js]][Node-url]
- [![Express][Express.js]][Express-url]
- [![MongoDB][MongoDB]][MongoDB-url]
- [![Axios][Axios]][Axios-url]
- [![bcryptjs][bcryptjs]][bcryptjs-url]
- [![JWT][JWT]][JWT-url]
- [![Mongoose][Mongoose]][Mongoose-url]

## Getting started

### Prerequisites

- Node.js v18+ : [Node.js download page](https://nodejs.org/en/download)
- A MongoDB Atlas account (or local MongoDB instance): [Go to the Atlas MongoDB](https://www.mongodb.com/products/platform/atlas-database)

## Installation

### Backend setup

1. Go to terminal

2. Clone the Repository

   ```bash
      git clone https://github.com/Pasindu-himansa/mern-authentication-app.git

   ```

3. Step into the project
   ```bash
   cd mern-authentication-app
   ```
4. Install dependencies
   ```bash
   npm install
   ```

### Setup environment variables

1. Create a `.env` file in the server folder
   ```
   New-Item -Path . -Name ".env" -ItemType "File"
   ```
2. Open the `.env` file and update the variables

   ```env
   ## database configurations

   MONGO_URI=<Your mongodb connection string>
   PORT=<Your PORT>
   JWT_SECRET=<your strong secret key>
   ```

### Start the server

```bash
cd Backend
npm run dev
```

The API will be available at `http://localhost:5000`.

### Frontend setup

1. Open a new terminal (Or split terminal)

2. Step in to the client side

```bash
cd ..
cd Frontend
```

3. Install dependencies

```bash
   npm install
```

4. Start the client

```bash
   npm run dev
```

The frontend will be available at `http://localhost:5173`.

## Security Notes

- Passwords are hashed with **bcryptjs** before storage — plain text is never saved.
- JWTs are signed with a secret and should be stored in `httpOnly` cookies on the client for best security.

> ⚠️ Never commit your `.env` file. Add it to `.gitignore`.

---

## Contact

Email: [subasinghe.info@gmail.com](mailto:subasinghe.info@gmail.com) | LinkedIn: [Pasindu Subasinghe](https://www.linkedin.com/in/pasindu-subasinghe/)

<!-- MARKDOWN LINKS & IMAGES -->

[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vite.js]: https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white
[Vite-url]: https://vitejs.dev/
[TailwindCSS]: https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white
[Tailwind-url]: https://tailwindcss.com/
[Node.js]: https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white
[Node-url]: https://nodejs.org/
[Express.js]: https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white
[Express-url]: https://expressjs.com/
[MongoDB]: https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white
[MongoDB-url]: https://www.mongodb.com/
[Axios]: https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white
[Axios-url]: https://axios-http.com/
[bcryptjs]: https://img.shields.io/badge/bcryptjs-003A70?style=for-the-badge&logo=npm&logoColor=white
[bcryptjs-url]: https://www.npmjs.com/package/bcryptjs
[JWT]: https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white
[JWT-url]: https://jwt.io/
[Mongoose]: https://img.shields.io/badge/Mongoose-880000?style=for-the-badge&logo=mongoose&logoColor=white
[Mongoose-url]: https://mongoosejs.com/

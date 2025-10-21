# Route Map for Javascript Fullstack

## STAGE 1: Fundamentals

**1.1 JavaScript Basics**

- Syntax, Variables, Data types.
- Operations, conditionals (if, else).
- Loops (for, while, forEach).
- Functions: regular, arrow functions, parameters.
- Scope(var, let, const) and hoisting.
- Error handling(try...catch).

**1.2 JSON**

- What is JSON?
- Convert between JSON -JavaScript

```js
JSON.parse(); // Converts JSON string → JS object
JSON.stringify(); // Converts JS object → JSON string
```

## STAGE 2: Frontend with JavaScript (No Frameworks)

**2.1 HTML & CSS**

- Semantic tags(header, main, footer).
- Flexbox, Grid, resposive design.

```bash
/frontend
 ├─ index.html
 ├─ styles/
 │   └─ main.css
 └─ scripts/
     └─ app.js
```

**2.2 DOM Manipulation & Events**

- querySelector, addEventListener
- Modify HTML/Classes/Text with JavaScript
- createElement for dynamic content

**2.3 Fetch API & API REST**

```js
fetch("https://api.com/users")
  .then((res) => res.json())
  .then((data) => console.log(data));
```

## STAGE 3: React

**3.1 Vite**

- Setup

```bash
npm create vite@latest my-app --template react
cd my-app
npm install
npm run dev
```

**3.2 Key Concepts**

- JSX
- useState/useEffect
- Routes
- Context/Redux
- APIs

## STAGE 4: Backend Node.js

- Node.js
- Express.js
- JSON in backend
- Rest API
- Database

## STAGE 5

- Connect React frontend ↔ Node.js backend
- Backend ↔ Database (MongoDB or SQL)
- Use environment variables (.env)
- Folder structure:

## STAGE 6

| Task                  | Tools                           |
| --------------------- | ------------------------------- |
| Deploy Frontend       | Vercel / Netlify                |
| Deploy Backend        | Render / Railway                |
| Cloud Database        | MongoDB Atlas / Supabase        |
| Environment Variables | `.env` (never upload to GitHub) |
| Documentation         | `README.md` + optional Swagger  |

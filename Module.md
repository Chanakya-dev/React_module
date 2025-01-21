
# Day 1: React Basics

### 1) How to Create a React App named `movie`?
**Answer:**  
`npx create-react-app movie`

---

### 2) How to Install Modules/Packages in React?  
**Answer:**  
`npm install package`

---

### 3) What is meant by `Index.js` and how is it useful?  
**Answer:**  
`Index.js` is the entry point of a React project. It observes changes in the `App.js` file and updates the Virtual DOM accordingly.

---

### 4) Why Do We Need to Use `npm install <package-name>`?  
**Answer:**  
The `npm install <package-name>` command is used to add a specific Node.js package or library into your project for additional functionalities.

---

# Day 2: React Components and JSX

### 1) How do you import a `HomePage` to `App.js` in React?  
**Answer:**  
```javascript
import Home from './pages/Home';
```

---

### 2) Prepare a Home Component and Return a Statement of "Hello World".  
**Answer:**  
```javascript
function Home() {
  return <div>Hello World</div>;
}
export default Home;
```

---

### 3) How do you use JSX to render a child component inside a parent component?  
**Answer:**  
```javascript
function App() {
  return (
    <Home />
  );
}
```

---

### 4) What is the purpose of the `export default` statement in React components?  
**Answer:**  
The `export default` statement allows you to export a single component, function, or value from a file, making it the default export. This enables importing it elsewhere without using curly braces.

---

### 5) What steps are needed to ensure this code runs in a React application?  
**Answer:**  
1. Create a React app using a tool like `create-react-app`.
2. Place the code in the appropriate files (`App.js` and `Home.js`).
3. Import the necessary components and libraries.
4. Run the app using `npm start` or `yarn start`.
```

You can save this content in a file named `Day1_and_Day2_Questions.md`. Let me know if you'd like to add more sections!

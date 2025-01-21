# Day 1 Questions

## 1) How to Create a React App named movie?
**Answer:**
```bash
npx create-react-app movie
```

## 2) How to Install Modules/Packages in React?
**Answer:**
```bash
npm install package
```

## 3) What is meant by Index.js and how it is useful?
**Answer:**
Index.js is called the first file of a React project. It is used to render the root component (typically `App.js`) into the DOM, updating the virtual DOM by observing changes in the app.

## 4) Why Do We Need to Use npm install <package-name>?
**Answer:**
The `npm install <package-name>` command is used to install a specific Node.js package or library into your project.

## 5) React Import Statement  
**Question:**  
Write the correct import statement to import React from the 'react' package.  

**Answer:**  
```javascript
import React from 'react';
```

## 6) Create APP Function in React  
**Question:**  
Create a functional component named 'App' that displays 'Hello, React!' in an h1 tag.  

**Answer:**  
```javascript
function App() {
  return (<h1>Hello, React!</h1>);
}
```

## 7) React JSX Styling  
**Question:**  
Write the inline style attribute that applies text alignment and margin-top to the APP.  

**Answer:**  
```javascript
function App() {
  return (
    <div style={{ textAlign: 'center', marginTop: '50px' }}>
      // Content goes here
    </div>
  );
}
```

## 8) React Export Statement  
**Question:**  
Write the correct export statement to export the App component from this file.  

**Answer:**  
```javascript
export default App;
```

---

# Day 2 Questions

## 9) How do you import a HomePage to App.js in React?
**Answer:**
```javascript
import Home from './pages/Home';
```

## 10) Prepare Home Component and Return a Statement of Hello World
**Answer:**
```javascript
function Home() {
  return <div>Hello World</div>;
}
export default Home;
```

## 11) How do you use JSX to render a child component inside a parent component?
**Answer:**
```javascript
function App() {
  return (
    <Home/>
  );
}
```

## 12) What is the purpose of the export default statement in React components?
**Answer:**
The `export default` statement allows you to export a single component, function, or value from a file, making it the default export. This allows you to import it elsewhere without using curly braces.

## 13) What Steps are needed to ensure this code runs in a React application?
**Answer:**
- Create a React app using a tool like `create-react-app`.
- Place the code in the appropriate files (App.js and Home.js).
- Import the necessary components and libraries.
- Run the app using `npm start` or `yarn start`.


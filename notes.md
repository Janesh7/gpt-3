To create a react app


```
npx create-react-app
```


 Basic imports 
 ```
 import React from 'react';
 import ReactDOM from 'react-dom'; //hook react app to index.html
 ```

 Too render a DOM

 ```
 ReactDOM.render(<App />, document.getElementById(' '));
 // render the app COMPONENT and take the root element
 // should have App.js in src folder and imported ... import App from ./App
 ```
 - App is the component that will be render with the Id pf root




Download es7 vsc extension for code snippets
```
rafce
```
- Creates a basic react functional components




Src folder have:
- components, whicnh for this project will have article,navbar,etc
- Inside each folder have Article.jsx ~ ... rafce
- Inside each folder add article.css ~ ( same folder name)
- Import css files to each jsx file
```
import './article.css';
```




Now in App.js we need to import these, can be done through
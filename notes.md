# To create a react app


```
npx create-react-app
```

# Start and File structure

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
```
import Article from './components/article/Article'
```
for all the files



Instead we can make an index.js file IN COMPONENTS and import all the components there using
```
export { default as Article } from './article/Article';
```
for al the files





Now to import all the components do this in App.js

```
import {Article, features, CTA} from './components';
```





<b> As components are used to structure files. Containers are used to structure bigger files , it contains multiple components, like header, footer, blog , etc </b>




These Containers would also have blog.jsx and blog.css ,etc


- These Containers folder will also have index.js with all the export statements

```
export { default as Header } from './header/Header';
```

for all files

and import it in Appp.js using

```
import {Header, Footer, Blog} from './containers';
```



Now everything is arranged to start coding


- In the return statement add a div, give it a *<div classname="App">*
- Make another div with clasname "gradeint__bg"
- Add components like Header and navbar using

```
<Navbar />
<Header />
```
- Close the div , and add other containers like Brand, WhatGPT3, Features,... using the above syntax
- Close the main div



Now everything is structure


src folder has an assest folder to store all the pictures,etc




# CSS

Refer App.css and index.css comments



import index.css to use vars throuhgout


IMP:


angrytools.com/gradeint
- Above site to get the gradient color , Use different options like gradient type and its axis
- This would give the code, copy and use it in code



animista.net
- Above site to get cool animations 




BEM -> Block Element Modifier : CSS naming conevntion like gpt3__navbar, under which gpt3__navbar__links and so on




Screen Sizes:
- Mobile: 550 px
- Tab: 700 px
- PC: 1050 px
<!-- TOC start (generated with https://github.com/derlin/bitdowntoc) -->

- [1. HTML: (The skeleton)](#1-html-the-skeleton)
- [2. CSS](#2-css)
- [3. JS](#3-js)
- [4. Some Small projects using JS](#4-some-small-projects-using-js)
- [5. Some Useless Advice:](#5-some-useless-advice)

<!-- TOC end -->

As some of you asked, what is the road map of your Web development journey? I have some suggestions. Here I have a plan to cover from HTML to JavaScript. Then select any framework of your choice. Recommendation: React or Next.

download any text editor of your choice, VSCODE recommended, and download some extensions along with it.

Extension List:

1. Code Formatter: ESLint or Prettier
2. Live Server
3. JavaScript (ES6) code snippets

Before deep-diving into the ocean of basic Web development, first see this structure:

![aa](https://github.com/Md-Kais/The-Guideline-of-HtmlCssJs/assets/62563474/008bec91-4f66-45d6-9047-b75a587649b4)


<!-- TOC --><a name="1-html-the-skeleton"></a>
## 1. HTML: (The skeleton)

To create a website, you have crystal clear idea about these following concepts.

1. **HTML Structure:**
    - Understand the basic structure with `<html>`, `<head>`, and `<body>` tags and know the use case of  `<title>` in the `<head>` for the webpage's title.
    
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>My Webpage</title>
    </head>
    <body>
        <!-- Content goes here -->
    </body>
    </html>
    ```
    
2. **Text Formatting:**
    - Headings: `<h1>` to `<h6>` .
        
        ```html
        <h1>This is Heading 1</h1>
        <h2>This is Heading 2</h2>
        <h3>This is Heading 3</h3>
        <!-- ... and so on up to h6 -->
        ```
        
    - Pararaphs: `<p>` for text
    - Lline breaks `<br>`
    - `<em>` and `<strong>` for emphasis and strong emphasis.
    
    ```html
    <p>This is a paragraph of text. It can contain
        <em>emphasized</em> or
        <strong>strongly emphasized</strong>
    text.</p>
    ```
    
3. **Lists:**
    - ordered lists `<ol>` and unordered lists `<ul>` using `<li>` for list items.
    
    ```html
    <ol>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
    </ol>
    <ul>
        <li>Item A</li>
        <li>Item B</li>
        <li>Item C</li>
    </ul>
    ```
    
4. **Links:**
    - `<a>` for hyperlinks, setting the `href` attribute to the target URL. `target="_blank"` to open links in a new tab.
        
        ```html
        <a href="https://www.example.com" target="_blank">Visit Example.com</a>
        ```
        
5. **Images:**
    - Insert images with `<img>` and use the `src` attribute for the image source.
    
    ```html
    <img src="image.jpg" alt="Description of the image">
    ```
    
6. **Forms:**
    - Utilize `<form>` to create forms and include various form elements like `<input>`, `<textarea>`, and `<button>`. Specify form actions using the `action` attribute.
    
    ```html
    <form action="/submit" method="post">
        <label for="username">Username:</label>
        <input type="text" id="username" name="username" required>
        <br>
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required>
        <br>
        <button type="submit">Submit</button>
    </form>
    ```
    
7. **Tables:**
    - Construct tables with `<table>`, `<tr>` for rows, `<td>` for data cells, and `<th>` for header cells.
    
    ```html
    <table>
        <thead>
            <tr>
                <th>Header 1</th>
                <th>Header 2</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Data 1</td>
                <td>Data 2</td>
            </tr>
            <tr>
                <td>Data 3</td>
                <td>Data 4</td>
            </tr>
        </tbody>
    </table>
    ```
    
8. **Semantic Elements:**
    - `header>`, `<footer>`, `<nav>`, `<article>`, `<section>`, and `<aside>` for better page structure.
    
    ```html
    <header>
        <h1>Website Header</h1>
    </header>
    
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    
    <section>
        <article>
            <h2>Article Title</h2>
            <p>Article content goes here.</p>
        </article>
    </section>
    
    <aside>
        <h3>Related Links</h3>
        <ul>
            <li><a href="#link1">Link 1</a></li>
            <li><a href="#link2">Link 2</a></li>
        </ul>
    </aside>
    
    <footer>
        <p>&copy; 2023 My Website</p>
    </footer>
    ```
    
9. **Attributes:**
    - `class`, `id`, `style`, and others.
    
    ```html
    <div class="container" id="main-container" style="background-color: #eee;">
        <!-- Content goes here -->
    </div>
    ```
    
10. **Comments:**
    - Use `<!-- comment -->` to add comments in your HTML code for documentation.
    
    ```html
    <!-- This is a comment. It won't be displayed on the webpage. -->
    ```
    

<!-- TOC --><a name="2-css"></a>
## 2. CSS (THE SKINS)

Advice: You can select any of the css library like bootstrap or talwind css. But you have to know the basics of CSS to use the library properly.

1. **Selectors:**
    - Understand different types of selectors, including element selectors, class selectors (`.`), and ID selectors (`#`).
2. **Box Model:**
    - Learn about the box model, which includes properties like `margin`, `padding`, `border`, and `width`/`height`.
        
        [The CSS Box Model | CSS-Tricks](https://css-tricks.com/the-css-box-model/)
        
3. **Typography:**
    - Use properties like `font-family`, `font-size`, `font-weight`, and `line-height` for text styling.
4. **Colors:**
    - Specify colors using properties like `color` for text color and `background-color` for background color.
5. **Layout:**
    - Position elements with properties like `position`, `display`, `float`, and `clear`.
    - Use `flexbox` and `grid` for more advanced and responsive layouts.
    
    [CSS Website Layout](https://www.w3schools.com/css/css_website_layout.asp)
    
6. **Flexbox: (IMPORTANT)**
    - Learn the basics of flex container properties (`display: flex`, `flex-direction`, `justify-content`, `align-items`).
    
    [A Complete Guide to Flexbox | CSS-Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
    
7. **Grid: (IMP)**
    - Learn the grid container properties (`display: grid`, `grid-template-rows`, `grid-template-columns`, `grid-gap`).
    
    [A Complete Guide to CSS Grid | CSS-Tricks](https://css-tricks.com/snippets/css/complete-guide-grid/)
    
8. **Responsive Design:**
    - Use media queries to create responsive designs that adapt to different screen sizes.
    
    ```css
    /*Code from CHATGPT*/
    /* Default styles for all screen sizes */
    body {
        font-family: 'Arial', sans-serif;
        color: #333;
        background-color: #f8f8f8;
        margin: 0;
    }
    
    .container {
        width: 80%;
        margin: 0 auto;
    }
    
    /* Media query for screens with a maximum width of 600 pixels */
    @media (max-width: 600px) {
        body {
            font-size: 14px;
        }
    
        .container {
            width: 100%;
        }
    }
    
    /* Media query for screens with a minimum width of 601 pixels and a maximum width of 1024 pixels */
    @media (min-width: 601px) and (max-width: 1024px) {
        body {
            font-size: 16px;
        }
    }
    
    /* Media query for screens with a minimum width of 1025 pixels */
    @media (min-width: 1025px) {
        body {
            font-size: 18px;
        }
    }
    ```
    
9. **Transitions and Animations:**
    - Apply smooth transitions using `transition` for properties like `color` or `width`.
    - Create animations with `@keyframes` and `animation` properties.
10. **Transforms:**
    - Utilize the `transform` property for 2D and 3D transformations, such as scaling, rotating, and translating elements.
11. **Selectors and Combinators:**
    - Understand advanced selectors and combinators, like descendant ( ``), child (`>`), and sibling (`~`) selectors.
12. **Units:**
    - Be familiar with different units like pixels, percentages, ems, and rems for defining sizes and distances.
    
    [What's The Difference Between PX, EM, REM, %, VW, And VH?](https://elementor.com/help/whats-the-difference-between-px-em-rem-vw-and-vh/)
    
13. **Positioning:**
    - Use the `position` property for absolute, relative, fixed, or sticky positioning.
    
    [CSS Positioning – Position Absolute and Relative Example](https://www.freecodecamp.org/news/css-positioning-position-absolute-and-relative/)
    
14. **Responsive Images:**
    - Employ techniques like `max-width: 100%` to ensure images scale with the size of the viewport.

<!-- TOC --><a name="3-js"></a>
## 3. JS (THE BRAIN)

ThatJSDude is the english website of JHANKAR MAHBUB and his team.

You can get some interview question idea from this 3 links:

https://www.thatjsdude.com/interview/js1.html

https://www.thatjsdude.com/interview/js2.html

https://www.thatjsdude.com/interview/dom.html

More at:

https://github.com/khan4019/front-end-Interview-Questions

JavaScript is a programming language like python and c++ and Java.

If you have crystal clear idea about any of these PL, you can easily grasp JS.

1. You have to know Variables, data types, operators, arrays, Control Flow, Functions,debugging
    
    Follow this website to learn it: 
    
    [Learn JavaScript for Beginners – JS Basics Handbook](https://www.freecodecamp.org/news/learn-javascript-for-beginners/)
    
2. **Objects:**
    - Understand how to create and manipulate objects, including accessing properties and methods.
3. **DOM Manipulation:**
    - Learn how to interact with the Document Object Model (DOM) to dynamically update and manipulate the content of a webpage.
        
        [DOM Manipulation in JavaScript – A Comprehensive Guide for Beginners](https://www.freecodecamp.org/news/dom-manipulation-in-javascript/)
        
4. **Scope:**
    - Understand the concepts of global and local scope. Learn about block scope introduced with `let` and `const`.
5. **Error Handling:**
    - Learn about try-catch blocks for handling errors and exceptions in your code.
6. **Events:**
    - Handle user interactions by attaching event listeners to HTML elements. Respond to events like clicks, keypresses, and form submissions.
7. **AJAX and Fetch API:**
    - Understand asynchronous programming and how to make HTTP requests using the Fetch API for data retrieval.
8. **Closures:**
    - Grasp the concept of closures and how they allow functions to maintain access to variables from their outer scope.
        
        [JS: scope & closure](https://www.thatjsdude.com/jsConcepts/concepts/scope.html)
        
9. **Promises and Async/Await:**
    - Understand asynchronous programming with promises and the more recent async/await syntax for handling asynchronous operations.
    
    [Async/await](https://javascript.info/async-await)
    

<!-- TOC --><a name="4-some-small-projects-using-js"></a>
## 4. Some Small projects using JS

1. **Interactive To-Do List:**
    - Create a simple to-do list where users can add, remove, and mark tasks as complete.
    - Use HTML for the structure, CSS for styling, and JavaScript for dynamic updates.
    - Practice DOM manipulation to add and remove elements based on user actions.
    - Implement local storage to save tasks, so they persist even when the page is refreshed.
2. **Image Slider:**
    - Build a basic image slider that displays a set of images in a rotating fashion.
    - Use HTML for the structure, CSS for styling, and JavaScript for functionality.
    - Implement features like automatic image transitions and manual navigation controls (next/previous buttons).
    - Explore CSS transitions or JavaScript animations for smooth image transitions.
    

<!-- TOC --><a name="5-some-useless-advice"></a>
## 5. Some Useless Advice:

This is the front end code of our website: 

https://github.com/Md-Kais/CUERS-New

For some security reasons we can’t share server code.

This code is the result of 4 months of hard work and 1.5 years of learning, don’t look this code and burn your head afterwards.

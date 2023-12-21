# CS260 github.md

### What I learned? 
In this assigment I learned how to use github and VS code to pull, commit and push any changes made in my code and I learn how to create a note and formatting syntex. 

**Basic git commands are:**
```
    git add . 
    git status
    git commit -m
```

### Midterm questions/review

What does the link element do?

The element in HTML is typically used to link external resources, such as stylesheets or icons, to a web page. It's commonly used to associate a CSS file with an HTML document to style the page.

What does a div tag do?

The tag is a block-level container in HTML used to group and structure content on a web page. It is often used to apply CSS styles, create layout structures, or group related elements together.

Difference between #title and .grid selector?

In CSS, #title refers to an element with the ID "title," while .grid refers to elements with the class "grid." IDs are unique in a document, while classes can be applied to multiple elements. So, #title selects a single element with the "title" ID, while .grid selects multiple elements with the "grid" class.

Difference between padding and margin?

Padding: It is the space between the content of an element and its inner boundary. It affects the space within the element.
Margin: It is the space outside of an element, affecting the space between that element and adjacent elements.


What does padding CSS do?

The CSS padding property defines the space between the content of an element and its border. It can be set for all sides or individually (e.g., padding: 10px; or padding-left: 20px;).

Code using arrow syntax function declaration?

Arrow functions in JavaScript are a concise way to declare functions. A typical arrow function looks like this:

javascript
Copy code
const add = (a, b) => a + b;
It's used for creating anonymous functions with a shorter syntax.

True statements about the DOM?

The Document Object Model (DOM) is a programming interface for web documents, allowing scripts to manipulate the content and structure of a web page.

Default display property of the HTML span element?

The default display property value for an HTML span element is typically "inline." This means it will not create a new line and will flow with the surrounding content.

Change all div elements to have a background color of red using CSS?

To set the background color of all div elements to red using CSS, you can use:

css
Copy code
div {
  background-color: red;
}

Display an image with a hyperlink in HTML?

You can use an anchor (a) element to create a hyperlink, and include an image (img) inside it. Here's an example:

html
Copy code
a href="https://example.com"
  img src="image.jpg" alt="Description of the image"
/a
Ordering of box layers in the CSS box model?

The layers in the CSS box model, from the inside out, are:

Content
Padding
Border
Margin

CSS to set text to green for "troubl" only?

To set the text "troubl" to green and leave the rest unaffected, you can use the :nth-child or :nth-of-type selector, or you can wrap "troubl" in a specific element with a class or ID and style it.

JavaScript to select an element with the id of “byu” and change text color to green?

You can use the following JavaScript code:

javascript
Copy code
document.getElementById("byu").style.color = "green";

Opening HTML tags for various elements?

Paragraph: p
Ordered List: ol
Unordered List: ul
Second Level Heading: h2
First Level Heading: h1
Third Level Heading: h3

How to declare the HTML document type?

You declare the document type (DOCTYPE) in HTML5 like this:

html
Copy code
!DOCTYPE html

Valid JavaScript syntax for if, else, for, while, switch statements?

If Statement: if (condition) { /* code */ }
Else Statement: else { /* code */ }
For Loop: for (initialization; condition; increment) { /* code */ }
While Loop: while (condition) { /* code */ }
Switch Statement:
javascript
Copy code
switch (expression) {
  case value1:
    // code for value1
    break;
  case value2:
    // code for value2
    break;
  default:
    // code for default case
}

Correct syntax for creating a JavaScript object?

You can create an object using the object literal syntax:

javascript
Copy code
const obj = { key1: value1, key2: value2 };
Adding new properties to JavaScript objects?
Yes, you can add new properties to JavaScript objects at any time, even after the object is initially defined. For example:

javascript
Copy code
obj.newProperty = "new value";
Tag to include JavaScript in HTML?
To include JavaScript in HTML, you use the script tag. For example:

html
Copy code
script type="text/javascript" src="script.js"></ script
JavaScript to change text from "animal" to "crow"?
To change the text "animal" to "crow" using JavaScript, you can do:

javascript
Copy code
document.getElementById("elementId").textContent = "crow";
Correct description of JSON?
JSON stands for "JavaScript Object Notation" and is a lightweight data interchange format. It is used for data storage and exchange between a server and a client, or between different parts of an application. JSON is a text format and is easy for humans


Final notes:

Ports for HTTP, HTTPS, SSH:

HTTP uses port 80 by default.
HTTPS uses port 443 by default.
SSH (Secure Shell) uses port 22 by default.
HTTP status codes in the 300, 400, 500 range indicate:

300 Range: Redirection. These codes indicate that the client must take additional action to complete the request, such as following a redirect.
400 Range: Client Errors. These codes indicate that there was a problem with the client's request, like a syntax error or invalid request.
500 Range: Server Errors. These codes indicate that the server encountered an error while processing the request and couldn't fulfill it.
The HTTP header Content-Type allows you to specify the type of data being sent in the HTTP response body. It tells the recipient how to interpret the data. Common values for Content-Type include text/html for HTML, application/json for JSON data, image/png for PNG images, and so on.

Cookie attributes:

Domain: Specifies the domain for which the cookie is valid.
Path: Specifies the URL path for which the cookie is valid.
SameSite: Defines when a cookie should be sent in cross-origin requests.
HTTPOnly: When set to true, the cookie cannot be accessed through JavaScript, enhancing security.
Without the Express middleware code, I cannot provide the console.log output for an HTTP GET request with a URL path of /foo/bar. Please provide the middleware code for a more specific answer.

Without the Express service code, I cannot determine the return value of a JavaScript fetch request. Please provide the code for more information.

The MongoDB query { cost: { $gt: 10 }, name: /fran.*/ } will select all documents where the "cost" field is greater than 10, and the "name" field matches the regular expression /fran.*/ (e.g., "frank", "francis", etc.).

User passwords should be securely hashed and salted before storing them in a database. Hashing algorithms like bcrypt are commonly used for this purpose to protect user data.

Without the Node.js service code, I cannot provide the console.log output for websockets. Please provide the relevant code for a specific answer.

WebSocket protocol is used for real-time, bidirectional communication between a client and a server over a single, long-lived connection. It is commonly used in web applications for features like chat, notifications, and online gaming.

JSX (JavaScript XML) is a syntax extension for JavaScript that allows you to write HTML-like code within JavaScript. Curly braces {} are used to embed JavaScript expressions or variables within JSX, and they are rendered as the result of evaluating those expressions.

The given React component code will generate three "Welcome" components with different names inside a "div" element. It will render as:

Copy code
Hello, Sara
Hello, Cahal
Hello, Edite
The given React component code will generate an unordered list with list items containing numbers 1 to 5. It will render as:
Copy code
1
2
3
4
5
The provided React component (Example) is a functional component that uses the useState hook to manage and display a count variable. It renders a paragraph showing the current count and a button to increment the count when clicked.

React Hooks are used to add state and other React features to functional components. They allow functional components to manage local component state, perform side effects, and more.

The useEffect hook in React is used for performing side effects in functional components. It allows you to run code after the component has rendered or when certain dependencies change. Common use cases include data fetching, DOM manipulation, and setting up subscriptions.

The provided code is defining routes for a React application using the React Router library. It sets up routes for different URLs, rendering corresponding components when the URL matches. The layout consists of "Home," "Blogs," "Contact," and a "NoPage" component for any other unmatched route.

npm (Node Package Manager) plays a crucial role in web development by managing and distributing JavaScript packages and libraries. It allows developers to easily install, manage, and share dependencies for their projects.

The package.json file in an npm project serves as a manifest file that contains metadata about the project and its dependencies. It also includes scripts for various project tasks and configuration settings.

The fetch function in JavaScript is used to make network requests (typically HTTP) to fetch resources like data from a server. It returns a Promise that resolves to the Response to that request.

Node.js is a JavaScript runtime that allows you to run JavaScript on the server-side. It provides a platform for building scalable and efficient server-side applications.

Vite is a build tool and development server for modern web development. It is designed to be fast and efficient, especially for development with JavaScript frameworks like Vue.js and React. Vite's development server provides features like hot module replacement for a smooth development experience.
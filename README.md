# Interview-Questions
<h2>JavaScript</h2>

<h3>Q1) JavaScript is a single threaded language. What does this mean?</h3>
<h4>JavaScript operates using a single thread of execution, which means that only one set of instructions is executed at a time. Unlike multi-threaded languages, where multiple threads can run concurrently, JavaScript executes code sequentially, one statement at a time.</h4>
<h3>Q2) Difference between let and var</h3>
<h4>let -> block scoped, var -> function scoped.
    let -> Hoisting (NO), var -> Hoisting (Yes) 
</h4>
<h3>Q3) Difference between Arguments and Parameters</h3>
<h4>function greet(name) { // 'name' is a parameter
    console.log(`Hello, ${name}!`);
}

greet("Alice") // Calling the function with an argument "Alice"</h4>
<h3>Q4) What is BOM and what is it's advantages</h3>
<h4>
BOM stands for Browser Object Model. It represents a set of objects provided by web browsers to interact with the browser window. While DOM (Document Object Model) represents the structure of the HTML document, BOM provides methods and properties to interact with the browser itself, such as manipulating the browser history, controlling the browser window, and managing cookies.
Advantages :-
<li>Access to Browser Functionality: BOM provides access to various browser functionalities and features that are not directly related to the document content. This includes manipulating the browser window, controlling navigation, managing cookies, and interacting with the user's screen.</li>
<li>Browser Interaction: BOM allows developers to interact with the browser and respond to user actions in real-time. For example, developers can prompt users with alert or confirmation dialogs, handle window resizing and scrolling events, and capture keyboard and mouse input.</li>
<li>Client-Side Validation: BOM can be used for client-side form validation, enabling developers to validate user input before submitting data to the server. This helps improve the user experience by providing instant feedback to users and reducing the need for server round trips.</li>
<li>Cookie Management: BOM provides methods for managing cookies, such as setting, getting, and deleting cookies. Cookies are commonly used for session management, user authentication, and tracking user behavior across multiple visits to a website.</li>
<li>Browser History Manipulation: BOM allows developers to manipulate the browser's history, enabling them to navigate backward and forward through the user's browsing history programmatically. This is useful for building single-page applications (SPAs) and implementing custom navigation controls.</li></h4>
<h3> Q5) What will be the output of [1,2,3] === [1,2,3]</h3>
<h4>
    false because JavaScript compares arrays by reference, not by their content.
</h4>
    

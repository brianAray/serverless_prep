# Serverless Prep

This training stack relies on JavaScript heavily. We will be using it for both the backend API development (Node.js) and the frontend UI development (TypeScript/React). The goal is to be prepared without going overboard, so for these reading materials, we will be focusing mostly on JavaScript and Node.js. The next aspect is NoSQL (Not Only SQL) databases, which if you are familiar with SQL databases, will be a little confusing at first, and so reading materials have been provided to improve your understanding.

Your first priority will be to be comfortable with the syntax of JavaScript, then to learn more about NoSQL databases. Remember, there is no replacement for learning coding other than coding so what you learn must be put into practice in order for you to remember.

---

## JavaScript

- [Java vs JavaScript](https://www.codecademy.com/resources/blog/java-vs-javascript/)
- [Modern JavaScript Tutorial](https://javascript.info)
- [JavaScript beginners guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)
- [Learn JavaScript in 1 Hour (video)](https://youtu.be/W6NZfCO5SIk)
- [Introduction to Node](https://nodejs.dev/en/learn/)

### Questions
<ol>
<li>
    <details>
    <summary>What is JavaScript?</summary>
    JavaScript is a high-level, interpreted programming language primarily used for adding interactivity to websites by enabling client-side scripting.
    </details>
</li>

<li>
    <details>
    <summary>What is Node.js?</summary>
    Node.js is a JavaScript runtime that allows you to execute JavaScript code on the server-side, outside of a web browser. It's designed to be efficient and asynchronous, making it suitable for building scalable network applications.
    </details>
</li>

<li>
    <details>
    <summary>What are the data types in JavaScript</summary>
    Number, BigInt, String, Boolean, Undefined, Null, Object, and Symbol.
    </details>
</li>

<li>
    <details>
    <summary>How do you declare a variable in JavaScript?</summary>
    You can declare a variable using the var, let, or const keyword. For example: var x;, let y;, const z;.
    </details>
</li>

<li>
    <details>
    <summary>What is the difference between let, const, and var for variable declaration?</summary>
    <ul>
        <li>var has function scope and can be re-declared within the same scope.</li>
        <li>let and const have block scope and cannot be re-declared within the same scope.</li>
        <li>const additionally cannot be reassigned after declaration.</li>
    </ul>
    </details>
</li>

<li>
    <details>
    <summary>How do you write a single-line comment in JavaScript?</summary>
    Use `//` to write a single-line comment. For example: 

    ```javascript
    // This is a comment.
    ```

    </details>
</li>

<li>
    <details>
    <summary>How do you write a multi-line comment in JavaScript?</summary>
    Use /* to start and */ to end a multi-line comment. For example:

    ```javascript
    /*
    This is a
    multi-line
    comment.
    */
    ```

    </details>
</li>

<li>
    <details>
    <summary>What is the purpose of the === operator in JavaScript?</summary>
    The `===` operator is used for strict equality comparison. It compares both value and type of the operands.
    </details>
</li>

<li>
    <details>
    <summary>How do you create a function in JavaScript?</summary>
    You can create a function using the function keyword. For example:

    ```javascript
    function myFunction() {
        // Function body
    }
    ```

    </details>
</li>

<li>
    <details>
    <summary>How do you call a function in JavaScript?</summary>
    To call a function, use its name followed by parentheses. For example: `myFunction()`;
    </details>
</li>

<li>
    <details>
    <summary>How do you write an if statement in JavaScript?</summary>
    You can write an if statement like this:

    ```javascript
    if (condition) {
        // Code to execute if condition is true
    }

    ```

    </details>
</li>

<li>
    <details>
    <summary>How do you loop through an array in JavaScript?</summary>
    You can use a for loop or a forEach method to loop through an array. For example:

    Using a for loop:

    ```javascript
    for (let i = 0; i < array.length; i++) {
        // Code using array[i]
    }
    ```

    Using forEach:

    ```javascript
    array.forEach(function(item) {
        // Code using item
    });
    ```

    </details>
</li>

</ol>

---

## NoSQL

- [What is NoSQL?](https://www.geeksforgeeks.org/introduction-to-nosql/)
- [SQL vs NoSQL](https://www.ibm.com/blog/sql-vs-nosql/)

<ol>
<li>
    <details>
    <summary>What is a NoSQL database?</summary>
    A NoSQL (Not Only SQL) database is a type of database that provides a flexible and schema-less data model. It's designed to handle large amounts of unstructured or semi-structured data and offers high scalability and performance.
    </details>
</li>

<li>
    <details>
    <summary>What is the main difference between SQL and NoSQL databases?</summary>
    The main difference lies in the data model and querying approach. SQL databases use a structured, tabular data model and SQL (Structured Query Language) for querying. NoSQL databases use various data models (document, key-value, etc.) and offer different query languages or APIs tailored to their data models.
    </details>
</li>

<li>
    <details>
    <summary>When would you choose a NoSQL database over a SQL database?</summary>
    You might choose a NoSQL database when:
    <ul>
        <li>Dealing with large volumes of unstructured data</li>
        <li>Needing horizontal scalability (adding more servers to accommodate load)</li>
        <li>Seeking flexibility to evolve the data model as requirements change</li>
        <li>Prioritizing high availability and fault tolerance</li>
    </ul>
    </details>
</li>

<li>
    <details>
    <summary>What are the trade-offs of using NoSQL databases?</summary>
    While NoSQL databases offer advantages like scalability and flexibility, they also have trade-offs:
    <ul>
        <li>Lack of ACID transactions in some cases (though some NoSQL databases provide eventual consistency)</li>
        <li>Potential data consistency challenges in distributed environments</li>
        <li>Less mature ecosystem compared to traditional SQL databases</li>
    </ul>
    </details>
</li>

</ol>

---

## Project Ideas

Once you have finished reading through these materials and answering the questions, attempt to make some projects. You may not have the knowledge to make a database and backend API right now, but you have access to JavaScript, a versatile and highly used language for web development. There is a section with projects that you can find in this repository, within them there is some more resources including further reading and starter code to help get you started.

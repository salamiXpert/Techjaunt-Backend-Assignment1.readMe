Assignment Details
Backend & JavaScript Assignment
Intro to Backend • Variables • Datatypes • Coding
Section A — Intro to Backend (Theory: 12 Questions)

What is backend development and how is it different from frontend development?
Backend development refers to the server-side aspect of web development, focusing on creating and managing the server logic, databases, and APIs. It involves handling user authentication, authorization, and processing user request

Mention three backend programming languages.
1. JavaScript 2. Python 3. Go
   
What is a server? Explain its role in backend development.

A server is a computer or system designed to store data, manage resources, and deliver services or content to other computers—called clients—over a network. In simple terms, it “serves” information when requested.

Role of a Server in Backend Development
In backend development, the server is the central engine that:

1. Receives and Processes Client Requests

When a user interacts with a website or app (e.g., clicking “login”), the request is sent to the server.

The server interprets the request, runs the necessary logic, and prepares a response.

2. Runs Backend Logic

Servers execute the application’s backend code—handling everything from calculations and data validation to decision-making based on business rules.

3. Connects to Databases

Servers handle reading, writing, updating, and deleting data.
They ensure smooth communication between the app and the database.

4. Manages Authentication & Authorization

Servers verify user identity (authentication) and control what each user is allowed to access (authorization).

5. Hosts APIs

Backend servers expose APIs that allow clients (web browsers, mobile apps, other servers) to interact with the application.

6. Ensures Security & Reliability

Servers implement encryption, error handling, rate limiting, and other measures to keep the application stable and secure.

Define an API and explain its purpose.

An API (Application Programming Interface) is a set of rules, protocols, and tools that allows different software systems to communicate with each other. It defines how requests should be made, what data can be exchanged, and how responses are delivered.

Purpose of an API
1. Enables Communication Between Systems

APIs allow one application to interact with another without needing to understand its internal workings.
Example: A mobile app using a backend server to fetch user data.

2. Simplifies Development

Developers can use prebuilt functions from an API instead of building everything from scratch.
Example: Using a payment API instead of writing your own payment system.

3. Provides Access to Data and Services

APIs expose specific data or functionalities in a controlled and secure way.
Example: Weather APIs provide temperature and forecast data to apps.

4. Ensures Consistency

By defining standard rules for communication, APIs ensure predictable, structured interactions between software components.

5. Supports Integration

APIs let independent systems work together—backend services, databases, third-party platforms, microservices, etc.

What is a database and why is it important in backend systems?

database is an organized system for storing, managing, and retrieving data. Instead of keeping information in scattered files, a database provides a structured, efficient, and secure way to handle large amounts of data that applications rely on.

Why a Database Is Important in Backend Systems
1. Centralized Data Storage

Backend systems need a reliable place to store user information, product details, transactions, logs, and more.
A database keeps all of this organized and accessible.

2. Fast and Efficient Data Retrieval

Databases are optimized for quick searches, filtering, and querying—much faster and more reliable than manual file-based storage.

3. Data Integrity and Accuracy

Databases enforce rules (constraints) to ensure the data remains valid, consistent, and error-free.

4. Security and Access Control

Backend systems often handle sensitive information.
Databases provide mechanisms such as authentication, encryption, and role-based permissions to protect data.

5. Supports Application Functionality

Login systems, dashboards, ecommerce carts, analytics, and messaging features all rely on stored data.
Without a database, these features couldn’t function.

6. Scalability

Databases can handle increasing amounts of data and users as an application grows.

7. Backup and Recovery

Databases offer tools for restoring data if something goes wrong (e.g., server crash, accidental deletion).

List two differences between SQL and NoSQL databases.

1. Data Structure

SQL: Stores data in structured tables with rows and columns (relational model).

NoSQL: Uses flexible structures like documents, key-value pairs, graphs, or wide-column stores (non-relational model).

2. Schema

SQL: Requires a fixed, predefined schema. Data must conform to the table structure.

NoSQL: Schema-less or flexible schema, allowing fields to vary between records.

What is a backend framework? Mention one example.

A backend framework is a collection of tools, libraries, and pre-built components that simplifies building server-side applications. It provides structure for handling routing, database interactions, authentication, middleware, and other core backend tasks—allowing developers to focus on application logic instead of rewriting everything from scratch.

Example: Django (a popular Python backend framework).

Explain what HTTP is and why it is important.

HTTP (Hypertext Transfer Protocol) is the communication protocol that defines how data is requested and transferred between a client (like a browser or mobile app) and a server on the web. It sets the rules for how messages are formatted, sent, and received over the internet.

Why HTTP Is Important
1. Foundation of Web Communication

Every time you visit a website, submit a form, or fetch data, HTTP is the protocol that handles the interaction between your device and the server.

2. Standardized Request–Response System

HTTP provides a consistent structure (methods like GET, POST, PUT, DELETE) that makes communication predictable and interoperable across different systems.

3. Supports Modern Web Technologies

APIs, web apps, mobile apps, and microservices all rely on HTTP to exchange data, often in formats like JSON.

4. Stateless and Scalable

HTTP doesn’t store session information between requests, making web applications easier to scale.

5. Secure Communication via HTTPS

When combined with SSL/TLS (becoming HTTPS), HTTP ensures data privacy, integrity, and protection from attackers.

Mention two responsibilities of a backend developer.

1. Building and Maintaining Server-Side Logic

They create the core functionality of an application—processing requests, applying business rules, and ensuring everything runs smoothly behind the scenes.

2. Managing Databases and Data Storage

They design, query, and optimize databases to store, retrieve, and update application data securely and efficiently.

What does CRUD stand for? Explain each word.

CRUD stands for Create, Read, Update, Delete—the four basic operations performed on data in most applications.

1. Create

Adding new data to the database.
Example: Adding a new user or creating a new product record.

2. Read

Retrieving or viewing existing data.
Example: Fetching user details or listing all orders.

3. Update

Modifying existing data.
Example: Editing a user’s profile information.

4. Delete

Removing data from the database.
Example: Deleting a post or removing an item from inventory.

What is authentication and why is it important for backend applications?

Authentication is the process of verifying a user’s identity—confirming that they are who they claim to be. This usually involves checking credentials such as a username and password, an email link, a fingerprint, or a login token.

Why Authentication Is Important for Backend Applications
1. Protects Sensitive Data

It ensures that only legitimate users can access personal information, dashboards, or private features.

2. Prevents Unauthorized Access

Without authentication, anyone could access user accounts, manipulate data, or misuse the system.

Authentication is the first line of defense in backend security, making it essential for any application that handles user data or restricted functionality.

What is the difference between a GET request and a POST request?
| Aspect            | **GET Request**                               | **POST Request**                                                   |
| ----------------- | --------------------------------------------- | ------------------------------------------------------------------ |
| **Purpose**       | Retrieve data from the server                 | Send data to the server (create/update resources)                  |
| **Data Location** | Sent in the URL (query parameters)            | Sent in the request body                                           |
| **Visibility**    | Visible in the URL, can be bookmarked         | Not visible in the URL, more secure for sensitive data             |
| **Idempotence**   | Safe and idempotent (repeating has no effect) | Not necessarily idempotent (repeating can create multiple entries) |
| **Typical Use**   | Fetching web pages, retrieving user info      | Submitting forms, uploading files, creating new records            |


Section B — JavaScript Variables & Datatypes (Theory: 10 Questions)

What is a variable in JavaScript?

A variable is a named storage that holds data values. It allows you to store, modify, and retrieve information during the execution of a program.

List the three ways to declare variables in JavaScript.
Var
Let
Const

Explain the difference between let and const.

let: The value of the variable can be changed (mutable).

const: The value cannot be reassigned (immutable).


Mention the seven primitive datatypes in JavaScript.
String

Number

Boolean

Null

Undefined

BigInt

Symbol

What datatype is assigned to the value: true?

Boolean

What datatype is a JavaScript array?

Object (Arrays are specialized objects in JavaScript.

Give one example of a string in JavaScript.

let FullName = "Salami Emmanuel"

Give one example of a number in JavaScript.

var Weight = 240

What will be the output of this expression?
typeof "123"

"String"

Explain the difference between null and undefined.

null: Represents the intentional absence of any value; it must be assigned explicitly.

undefined: Represents a variable that has been declared but not assigned a value.


Section C — Coding Questions (8 Questions)

Declare a variable using let and assign your name to it.

Let Name = "Salami Emmanuel"

Write JavaScript code to add two numbers and log the result.

function TotalFruits() {
var Basket1 = 50;
var Basket2 = 20;
var TotalFruitBasket = Basket1 + Basket2;
console.log(TotalFruitBasket);
};
TotalFruits();



Create an object called student with properties: name, age, and department.

var Student = {
 name :"Salami Emmanuel",
 age : 25,
 department :"BackEnd Developmnet"
};
console.log(Student.name);
console.log(Student.age);
console.log(Student.department);


Write a JavaScript function called greet() that prints "Hello World".

function greet(){
console.log("Hello World");
}
greet();

Write a program that checks if a number is even or odd.
let number = 7;
if (number % 2 === 0) {
    console.log("Even");
} else {
    console.log("Odd");
}
// Output: Odd


Create an array of 5 colors and print the first color.

let colors = ["Red", "Blue", "Green", "Yellow", "Purple"];
console.log(colors[0]); // Output: Red


Write a function that returns the square of a number passed into it.

function square(num) {
    return num * num;
}
console.log(square(5)); // Output: 25


Write a small code snippet that converts a string to a number:
let value = "42";
let numberValue = Number(value);
console.log(numberValue); // Output: 42

let value = "42";
// convert to number here

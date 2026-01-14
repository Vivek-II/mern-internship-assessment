# MERN Stack Developer Internship – Assessment

## Section 0: Candidate Details

- **Full Name:** Vivek  
- **Email Address:** (your email)  
- **College / Company Name:** (your college name)  
- **GitHub Profile:** https://github.com/Vivek-II  
- **Internship Batch / Group Name:** MERN Internship Batch

---

## Section 1: Git & GitHub

### 1. Difference between Git and GitHub
Git is a distributed version control system used to track changes in code locally. GitHub is a cloud-based platform that hosts Git repositories and allows developers to collaborate online.

### 2. Explain git clone, git pull and git fetch
- **git clone** creates a copy of a remote repository on your local system.  
- **git pull** downloads and merges changes from a remote repository to your local branch.  
- **git fetch** only downloads changes without merging them.

### 3. What is a merge conflict and how do you resolve it?
A merge conflict occurs when two branches modify the same part of a file. It is resolved by manually editing the conflicting file and choosing which changes to keep, then committing again.

### 4. Difference between git merge and git rebase
Git merge creates a new commit combining branches. Git rebase moves commits from one branch to another, creating a cleaner commit history.

### 5. What is .gitignore and why is it important?
.gitignore is a file that tells Git which files to ignore so that unnecessary files like node_modules are not uploaded.

### 6. GitHub Repository Link
https://github.com/Vivek-II/mern-internship-assessment

---

## Section 2: MySQL & PostgreSQL

### 1. Difference between MySQL and PostgreSQL
MySQL is faster for read-heavy operations while PostgreSQL supports advanced data types and complex queries.

### 2. What is a Primary Key and a Foreign Key?
Primary key uniquely identifies a record. Foreign key links one table to another.

### 3. Difference between WHERE and HAVING
WHERE filters rows before grouping. HAVING filters grouped data.

### 4. Difference between DELETE and TRUNCATE
DELETE removes rows one by one. TRUNCATE removes all rows instantly.

### 5. What is database normalization?
It is a process of organizing data to reduce redundancy.

### 6. Explain INNER JOIN, LEFT JOIN and RIGHT JOIN
- INNER JOIN returns matching records  
- LEFT JOIN returns all left table records  
- RIGHT JOIN returns all right table records

### 7. SQL Queries

```sql
INSERT INTO users VALUES (1, 'Vivek');
SELECT * FROM users;
UPDATE users SET name='Vivek Kumar' WHERE id=1;
DELETE FROM users WHERE id=1;
---

## Section 3: React Fundamentals

### 1. What is React and why is it used?
React is a JavaScript library used to build fast and interactive user interfaces. It allows developers to create reusable UI components.

### 2. Difference between state and props
State is data managed inside a component, while props are used to pass data from parent to child components.

### 3. What are React hooks?
Hooks allow functional components to use state and other React features without writing class components.

### 4. Explain useEffect with an example
useEffect is used to perform side effects like fetching data or updating the DOM after rendering.

Example:
```js
useEffect(() => {
  console.log("Component loaded");
}, []);
5. What is lifting state up?

It means moving shared state to the nearest common parent component.

6. React Practical Task

React practical code is added in the folder:
/react-task
---

## Section 4: TypeScript Basics

### 1. What is TypeScript and why is it used?
TypeScript is a strongly typed superset of JavaScript that helps developers catch errors during development.

### 2. Difference between any and unknown
`any` allows any type, while `unknown` requires type checking before using the variable.

### 3. What are interfaces in TypeScript?
Interfaces define the structure of objects and enforce type safety.

### 4. What is type inference?
TypeScript automatically determines the type of a variable based on its value.

### 5. Explain optional and readonly properties
Optional properties may or may not exist, and readonly properties cannot be modified after initialization.

### 6. TypeScript Practical Code
TypeScript code is added in the folder:
`/typescript-task`
---

## Section 5: General Web Development

### 1. What is a REST API?
A REST API allows communication between client and server using HTTP methods like GET, POST, PUT, and DELETE.

### 2. Difference between PUT and PATCH
PUT replaces the entire resource, while PATCH updates only a part of the resource.

### 3. What is CORS?
CORS (Cross-Origin Resource Sharing) is a security feature that controls which domains can access APIs.

### 4. Difference between SQL and NoSQL databases
SQL databases use tables and structured data, while NoSQL databases store data in document or key-value format.

### 5. Explain MVC Architecture
MVC stands for Model-View-Controller.  
Model handles data, View handles UI, and Controller manages the application logic.

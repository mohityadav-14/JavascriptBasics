# 📘 JavaScript Interview Notes (Beginner → Intermediate)

This repository contains **well-structured JavaScript notes with examples**, covering all **core concepts frequently asked in interviews**.  
Each topic includes **clean explanations + code snippets** for quick revision.

---

## 📌 Table of Contents

- Variables & Scope  
- Data Types  
- Functions  
- Operators  
- Array Methods  
- ES6 Higher Order Functions  
- Destructuring  
- Object Methods  
- Spread & Rest Operators  
- Loops  
- Conditional Statements  
- Scope  
- DOM Basics  
- Asynchronous JavaScript  
- Closures  
- Local & Session Storage  
- Call, Apply & Bind  
- API Fetch Example  

---

## 🟢 Variables (var, let, const)

```js
var a = 10;
a = 12;
var a = 13;
console.log(a); // function scope

let b = 20;
b = 22; // block scope
console.log(b);

const c = 30; // block scope
console.log(c);


## 🟢 Data Types in JavaScript

JavaScript data types are divided into **Primitive** and **Non-Primitive** types.

---

### 🔹 Primitive Data Types

Primitive data types store **single values** and are **immutable**.

| Type | Description |
|-----|-------------|
| String | Textual data |
| Number | Numeric values |
| Boolean | true / false |
| Undefined | Variable declared but not assigned |
| Null | Intentional empty value |
| BigInt | Large integers |
| Symbol | Unique identifier |

```js
let string = "hello";
let num = 23;
let boolean = true;
let un = undefined;
let n = null;
let bigint = 21525558568345346n;
const sym1 = Symbol("description");

console.log(string, num, boolean, un, n, bigint, sym1);

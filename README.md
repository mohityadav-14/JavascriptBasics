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

```
 ## 📌 JavaScript Data Types

JavaScript data types define **what kind of value** a variable can hold.  
They are mainly divided into **Primitive** and **Non-Primitive (Reference)** data types.

---

## 🔹 Primitive Data Types

Primitive data types store **single, immutable values**.  
They are stored **by value**.

#### Example:
```js
let string = "hello";
let num = 23;
let boolean = true;
let un = undefined;
let n = null;
let bigint = 21525558568345346n;
const sym1 = Symbol("description");

console.log(string, num, boolean, un, n, bigint, sym1);

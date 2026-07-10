# Understanding HTTP Status Codes

🌐 **Live Demo:** https://understanding-http-status-codes.pages.dev

A practical field guide to HTTP status codes built using **pure HTML only**.

This project explains the different categories of HTTP response status codes and provides examples, tables, explanations, and interactive HTML elements to help beginner developers understand how HTTP communication works between clients and servers.

---

## 📌 Project Overview

**Understanding HTTP Status Codes** is a static HTML article page that teaches:

- What HTTP status codes are
- How status code categories work
- Commonly used HTTP responses in REST APIs
- The difference between client errors and server errors
- Important HTTP terminology
- Real examples of HTTP responses

The project was created as an HTML practice project focusing on semantic HTML structure without using CSS or JavaScript.

---

## 🎯 Purpose

The goal of this project is to practice:

- Writing clean semantic HTML
- Structuring long-form documentation pages
- Using HTML5 semantic elements
- Creating accessible content structures
- Working with tables, forms, lists, and media elements

---

## 🛠️ Technologies Used

- HTML5

No external frameworks, CSS, or JavaScript were used.

---

## 📚 Features

### HTTP Status Code Sections

The page includes explanations for:

### 1xx — Informational Responses

Examples:

- 100 Continue
- 101 Switching Protocols
- 102 Processing
- 103 Early Hints

---

### 2xx — Successful Responses

Examples:

- 200 OK
- 201 Created
- 202 Accepted
- 204 No Content

Includes:

- HTTP request/response cycle example
- Explanation of when to use 200 vs 201

---

### 3xx — Redirection Messages

Examples:

- 301 Moved Permanently
- 302 Found
- 304 Not Modified
- 307 Temporary Redirect
- 308 Permanent Redirect

---

### 4xx — Client Errors

Examples:

- 400 Bad Request
- 401 Unauthorized
- 403 Forbidden
- 404 Not Found
- 409 Conflict
- 422 Unprocessable Content
- 429 Too Many Requests

Includes:

- Raw HTTP response example
- Browser DevTools instructions
- Console output example

---

### 5xx — Server Errors

Examples:

- 500 Internal Server Error
- 502 Bad Gateway
- 503 Service Unavailable
- 504 Gateway Timeout

Includes:

- Production failure scenario example using `<aside>`

---

## 🧩 HTML Elements Practiced

This project intentionally uses many HTML5 elements, including:

### Document Structure

- `<header>`
- `<nav>`
- `<main>`
- `<section>`
- `<footer>`

### Text Content

- `<h1>` - `<h3>`
- `<p>`
- `<blockquote>`
- `<abbr>`
- `<mark>`
- `<sup>`

### Lists

- `<ul>`
- `<ol>`
- `<dl>`

### Tables

- `<table>`
- `<thead>`
- `<tbody>`
- `<tfoot>`
- `<tr>`
- `<th>`
- `<td>`

### Interactive Elements

- `<details>`
- `<summary>`

### Code Documentation

- `<pre>`
- `<code>`
- `<kbd>`
- `<samp>`

### Forms

- `<form>`
- `<fieldset>`
- `<legend>`
- `<label>`
- `<select>`
- `<option>`
- `<button>`

---

## 📖 Glossary Included

The page contains explanations for important HTTP concepts:

- Idempotent
- Safe Method
- Payload
- Header
- Status Line

---

## 🔗 Further Reading

External references included:

- RFC 9110 — HTTP Semantics
- MDN HTTP Status Codes
- MDN HTTP Methods
- IANA HTTP Status Code Registry
- HTTP Working Group Specifications

---

## ⚠️ Note About Deprecated HTML Attributes

This project intentionally uses some deprecated HTML tags and attributes:

Examples:

- `<center>`
- `leftmargin`
- `border`
- `cellpadding`
- `cellspacing`

They were used because the project was created without CSS, and they helped with basic visual formatting.

In modern web development, these should be replaced with CSS.
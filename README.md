# Understanding HTTP Status Codes 🌐

🌐 **Live Demo:** https://understanding-http-status-codes.pages.dev

A practical field guide to HTTP status codes built using **pure HTML5**.

The project presents a single-page technical article explaining how HTTP response status codes work, covering all five status code categories with examples, tables, definitions, and interactive elements aimed at beginner developers.

## Overview

Understanding HTTP Status Codes is a semantic HTML article project created to practice building a long-form documentation page without using CSS or JavaScript.

The goal of this project was to focus on:
- HTML document structure for long-form content
- Semantic HTML5 elements
- Tables for structured reference data
- Interactive elements without JavaScript
- Code documentation markup
- Proper use of HTML attributes

## Features

### 1xx – Informational
- Table of informational status codes (100, 101, 102, 103) with meanings

### 2xx – Success
- Table of success status codes (200, 201, 202, 204)
- `<details>`/`<summary>` explaining when to use 200 vs 201

### 3xx – Redirection
- Definition list (`<dl>`) covering 301, 302, 304, 307, 308

### 4xx – Client Errors
- Table of client error codes (400, 401, 403, 404, 409, 422, 429)
- `<pre>`/`<code>` block showing a raw HTTP response
- DevTools instructions using `<kbd>`, sample output using `<samp>`

### 5xx – Server Errors
- Table of server error codes (500, 502, 503, 504)
- `<aside>` describing a real-world production failure scenario

### Glossary & Further Reading
- Definition list of HTTP terminology
- Ordered list of external references (RFC 9110, MDN, IANA)

## Technologies Used

- HTML5

No external libraries, frameworks, CSS, or JavaScript were used.

## Semantic HTML Elements Practiced

This project uses many HTML5 elements across a single page:
- `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`
- `<h1>`–`<h3>`, `<p>`, `<blockquote>`, `<abbr>`, `<mark>`, `<sup>`
- `<ul>`, `<ol>`, `<dl>`
- `<table>`, `<thead>`, `<tbody>`, `<tfoot>`, `<tr>`, `<th>`, `<td>`
- `<details>`, `<summary>`
- `<pre>`, `<code>`, `<kbd>`, `<samp>`
- `<form>`, `<fieldset>`, `<legend>`, `<label>`, `<select>`, `<option>`, `<button>`

## Glossary Included

The page contains explanations for important HTTP concepts:
- Idempotent
- Safe Method
- Payload
- Header
- Status Line

## Notes

This project intentionally uses some deprecated HTML tags and attributes:
- `<center>`
- `leftmargin`
- `border`
- `cellpadding`
- `cellspacing`

They were used because the project was created without CSS, and they helped with basic visual formatting. In modern web development, these should be replaced with CSS.

## Project Purpose

This project is part of my HTML learning journey and focuses on writing clean, semantic, long-form documentation markup before adding styling and interactivity.

## Future Improvements

Possible improvements:
- Add responsive CSS styling
- Replace deprecated HTML attributes with CSS
- Add JavaScript-powered interactive quiz scoring
- Add search/filter functionality across status codes
- Add Web Accessibility (ARIA roles and attributes)

## Author

**Fares Mohamed**

© 2026 Understanding HTTP Status Codes
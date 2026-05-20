# 🌐 HTML CSS Master — Part 1
### HTML5 Deep Dive + Semantic HTML + Forms + Accessibility + SEO + 75 Questions

> Complete HTML5 interview preparation for **Frontend Developers / Senior Developers / Leads / Architects**

![HTML5](https://img.shields.io/badge/HTML5-orange?style=for-the-badge&logo=html5)
![CSS3](https://img.shields.io/badge/CSS3-blue?style=for-the-badge&logo=css3)
![Accessibility](https://img.shields.io/badge/WCAG-Accessibility-green?style=for-the-badge)
![Frontend](https://img.shields.io/badge/Frontend-UI-red?style=for-the-badge)

---

# 📌 Table of Contents

- [HTML5 Overview](#html5-overview)
- [HTML Document Structure](#html-document-structure)
- [HTML Tags](#html-tags)
- [Semantic HTML](#semantic-html)
- [Forms Deep Dive](#forms-deep-dive)
- [Input Types](#input-types)
- [Tables](#tables)
- [Media Elements](#media-elements)
- [SEO in HTML](#seo-in-html)
- [Accessibility (WCAG)](#accessibility-wcag)
- [HTML Performance Optimization](#html-performance-optimization)
- [75 Senior HTML Questions](#senior-html-interview-questions)

---

# HTML5 Overview

HTML:

```text
HyperText Markup Language
```

Purpose:

```text
Structure Web Pages
```

HTML5 introduced:

✅ Semantic elements  
✅ Audio & Video  
✅ Better Forms  
✅ Accessibility improvements  
✅ Local storage support

---

## Why HTML5 Important?

Benefits:

```text
SEO Friendly
Accessibility
Cleaner Code
Better Performance
Responsive Support
```

---

# HTML Document Structure

Basic structure:

```html
<!DOCTYPE html>

<html lang="en">

<head>

  <meta charset="UTF-8" />

  <meta
   name="viewport"
   content="width=device-width, initial-scale=1.0"
  />

  <title>
   My Website
  </title>

</head>

<body>

  <h1>Hello</h1>

</body>

</html>
```

---

## Why DOCTYPE?

Tells browser:

```text
HTML5 document
```

---

## lang Attribute

Example:

```html
<html lang="en">
```

Benefits:

```text
Accessibility
SEO
Screen readers
```

---

# HTML Tags

---

## Heading Tags

```html
<h1>Main Heading</h1>
<h2>Sub Heading</h2>
<h3>Heading</h3>
```

Best Practice:

Only:

```text
1 h1 per page
```

---

## Paragraph

```html
<p>
 Lorem ipsum
</p>
```

---

## Anchor Tag

```html
<a href="/home">

 Home

</a>
```

---

## Image Tag

```html
<img
 src="image.jpg"
 alt="Profile"
/>
```

---

## Why alt Important?

Benefits:

```text
Accessibility
SEO
Screen readers
```

---

## Lists

### Ordered List

```html
<ol>

 <li>React</li>

</ol>
```

### Unordered List

```html
<ul>

 <li>Angular</li>

</ul>
```

---

## div vs span

Massive interview topic.

### div

```text
Block element
```

Example:

```html
<div>Hello</div>
```

---

### span

```text
Inline element
```

Example:

```html
<span>Hello</span>
```

---

## Inline vs Block Elements

### Block

```text
div
p
section
article
```

Takes:

```text
Full width
```

---

### Inline

```text
span
a
strong
```

Takes:

```text
Required width
```

---

# Semantic HTML

Very important.

Bad:

```html
<div class="header">

</div>
```

Good:

```html
<header>

</header>
```

---

## Semantic Elements

```html
<header>
<nav>
<main>
<section>
<article>
<aside>
<footer>
```

---

## Benefits

```text
SEO
Accessibility
Cleaner code
Maintainability
```

---

## Example Layout

```html
<header>

 Header

</header>

<nav>

 Navigation

</nav>

<main>

 <section>

  Content

 </section>

</main>

<footer>

 Footer

</footer>
```

---

## section vs article

### section

Generic section.

### article

Independent content.

Example:

```text
Blog Post
News Article
```

---

# Forms Deep Dive

Highly asked topic.

---

## Basic Form

```html
<form>

 <input
  type="text"
 />

 <button>

  Submit

 </button>

</form>
```

---

## Form Attributes

```html
<form

 action="/save"

 method="POST"

>
```

---

## Input Types

---

### Text

```html
<input
 type="text"
/>
```

---

### Email

```html
<input
 type="email"
/>
```

Validation included.

---

### Password

```html
<input
 type="password"
/>
```

---

### Number

```html
<input
 type="number"
/>
```

---

### Date

```html
<input
 type="date"
/>
```

---

### Checkbox

```html
<input
 type="checkbox"
/>
```

---

### Radio

```html
<input
 type="radio"
/>
```

---

### File Upload

```html
<input
 type="file"
/>
```

---

## Required Validation

```html
<input

 required

 type="email"
/>
```

---

## Placeholder

```html
<input

 placeholder=
 "Enter Name"

/>
```

---

## Label Tag

Accessibility favorite.

GOOD:

```html
<label for="email">

 Email

</label>

<input
 id="email"
/>
```

---

# Tables

---

## Table Example

```html
<table>

 <thead>

  <tr>
   <th>Name</th>
  </tr>

 </thead>

 <tbody>

  <tr>

   <td>Rahul</td>

  </tr>

 </tbody>

</table>
```

---

## Responsive Table

Use:

```text
overflow-x:auto
```

---

# Media Elements

---

## Video

```html
<video controls>

 <source
  src="video.mp4"
 />

</video>
```

---

## Audio

```html
<audio controls>

 <source
  src="song.mp3"
 />

</audio>
```

---

## iframe

Embed content.

```html
<iframe

 src="youtube"

></iframe>
```

---

## SVG

Scalable graphics.

Benefits:

```text
Performance
Scalable
Sharp image
```

---

# SEO in HTML

Frontend lead favorite.

---

## Meta Description

```html
<meta

 name="description"

 content="Angular App"

/>
```

---

## Keywords

```html
<meta

 name="keywords"

 content="Angular,React"

/>
```

---

## Open Graph

Social sharing.

```html
<meta

 property="og:title"

 content="Website"

/>
```

---

## Canonical Tag

Avoid duplicate SEO.

```html
<link

 rel="canonical"

 href="url"

/>
```

---

# Accessibility (WCAG)

Very important.

---

## Why Accessibility?

Support:

```text
Screen Readers
Keyboard users
Disabled users
```

---

## aria-label

```html
<button

 aria-label=
 "Close"

>
 X
</button>
```

---

## role Attribute

```html
<div

 role="button"

>

 Save

</div>
```

---

## tabindex

Keyboard navigation.

```html
tabindex="0"
```

---

## Semantic HTML for Accessibility

GOOD:

```html
<nav>
<header>
```

BAD:

```html
<div>
```

---

## Contrast Ratio

Important for:

```text
Readability
WCAG
```

---

# HTML Performance Optimization

---

## Lazy Loading Images

```html
<img

 loading="lazy"

/>
```

---

## Async Script

```html
<script

 async

 src="app.js"

></script>
```

---

## Defer Script

Preferred:

```html
<script

 defer

 src="app.js"

></script>
```

---

## Minimize DOM

Avoid:

```text
Deep nesting
```

---

## Optimize Images

Prefer:

```text
WebP
SVG
```

---

# Senior HTML Interview Questions

---

## Q1.
div vs span?

```text
div → block

span → inline
```

---

## Q2.
Semantic HTML?

Meaningful tags.

---

## Q3.
Why semantic HTML?

```text
SEO
Accessibility
Cleaner code
```

---

## Q4.
section vs article?

section:

grouping.

article:

independent content.

---

## Q5.
Why alt attribute?

Accessibility.

---

## Q6.
Why label important?

Screen readers.

---

## Q7.
async vs defer?

async:

independent loading.

defer:

runs after HTML parsing.

---

## Q8.
localStorage vs sessionStorage?

localStorage:

persistent.

sessionStorage:

tab only.

---

## Q9.
Why iframe risky?

Security issue.

---

## Q10.
Meta viewport?

Responsive support.

---

## Q11.
What is ARIA?

Accessibility attributes.

---

## Q12.
Why tabindex?

Keyboard navigation.

---

## Q13.
Why h1 important?

SEO hierarchy.

---

## Q14.
Canvas vs SVG?

Canvas:

pixel based.

SVG:

vector based.

---

## Q15.
How optimize HTML?

```text
Lazy loading
Optimize DOM
Image compression
Semantic HTML
```

---

# Interview Traps

---

## Trap 1

### Multiple h1 tags

Bad SEO.

---

## Trap 2

### Missing alt tag

Accessibility issue.

---

## Trap 3

### Using div everywhere

Avoid.

Use semantic tags.

---

## Trap 4

### No label in forms

Bad accessibility.

---

# Quick Revision

```text
Semantic HTML
Forms
ARIA
Accessibility
SEO
Meta Tags
SVG
Video
Audio
div vs span
async vs defer
```

---

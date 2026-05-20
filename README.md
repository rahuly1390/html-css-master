# 🌐 HTML CSS Master 
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
# 🎨 HTML CSS Master — Part 2
### CSS3 + Flexbox + Grid + Responsive + SCSS + Tailwind + Animations + 100 Questions

> Complete CSS3 deep dive for **Frontend Developers / Senior Developers / Leads / Architects**

![CSS3](https://img.shields.io/badge/CSS3-blue?style=for-the-badge&logo=css3)
![Tailwind](https://img.shields.io/badge/Tailwind-blue?style=for-the-badge&logo=tailwindcss)
![SCSS](https://img.shields.io/badge/SCSS-pink?style=for-the-badge&logo=sass)
![Responsive](https://img.shields.io/badge/Responsive-UI-green?style=for-the-badge)

---

# 📌 Table of Contents

- [CSS Overview](#css-overview)
- [CSS Selectors](#css-selectors)
- [CSS Specificity](#css-specificity)
- [Box Model](#box-model)
- [Positioning](#positioning)
- [Display Properties](#display-properties)
- [Flexbox Deep Dive](#flexbox-deep-dive)
- [CSS Grid Deep Dive](#css-grid-deep-dive)
- [Responsive Design](#responsive-design)
- [Media Queries](#media-queries)
- [SCSS Deep Dive](#scss-deep-dive)
- [Tailwind CSS](#tailwind-css)
- [Animations](#animations)
- [Performance Optimization](#performance-optimization)
- [100 Advanced Interview Questions](#advanced-css-interview-questions)

---

# CSS Overview

CSS:

```text
Cascading Style Sheets
```

Purpose:

```text
Styling UI
Layout
Responsive design
Animation
```

---

## CSS Types

### Inline CSS

```html
<h1 style="color:red">
 Hello
</h1>
```

---

### Internal CSS

```html
<style>

 h1{
  color:red;
 }

</style>
```

---

### External CSS

Preferred.

```html
<link

 rel="stylesheet"

 href="style.css"
/>
```

---

# CSS Selectors

Massive interview topic.

---

## Element Selector

```css
h1{
 color:red;
}
```

---

## Class Selector

```css
.card{
 padding:20px;
}
```

---

## ID Selector

```css
#header{
 background:black;
}
```

---

## Universal Selector

```css
*{
 margin:0;
}
```

---

## Attribute Selector

```css
input[type="text"]{
 border:1px solid;
}
```

---

## Pseudo Class

```css
button:hover{
 background:red;
}
```

---

## Pseudo Element

```css
p::before{
 content:"★";
}
```

---

# CSS Specificity

Senior interview favorite.

Priority:

```text
Inline > ID > Class > Element
```

Example:

```css
#title{
 color:red;
}

.title{
 color:blue;
}
```

Winner:

```text
ID Selector
```

---

## !important

Avoid overuse.

```css
color:red !important;
```

---

# Box Model

Very important.

Structure:

```text
Content
Padding
Border
Margin
```

---

## Example

```css
.card{

 padding:20px;

 border:1px solid;

 margin:10px;

}
```

---

## box-sizing

Recommended:

```css
*{

 box-sizing:
 border-box;

}
```

Why?

```text
Predictable width
```

---

# Positioning

---

## Static

Default.

```css
position:static;
```

---

## Relative

Moves relative.

```css
position:relative;
top:10px;
```

---

## Absolute

Relative to parent.

```css
position:absolute;
top:0;
```

---

## Fixed

Sticky viewport.

```css
position:fixed;
```

---

## Sticky

Scroll sticky.

```css
position:sticky;
top:0;
```

---

# Display Properties

---

## Block

Takes full width.

```css
display:block;
```

---

## Inline

Only content width.

```css
display:inline;
```

---

## Inline-block

Mixed behavior.

```css
display:inline-block;
```

---

## Flex

Modern layout.

```css
display:flex;
```

---

## Grid

Advanced layout.

```css
display:grid;
```

---

# Flexbox Deep Dive

Most asked topic.

---

## Parent Container

```css
.container{

 display:flex;

}
```

---

## Main Axis

```text
justify-content
```

---

## Cross Axis

```text
align-items
```

---

## justify-content

### Center

```css
justify-content:
center;
```

### Space Between

```css
justify-content:
space-between;
```

---

## align-items

```css
align-items:center;
```

---

## flex-direction

```css
row
column
```

Example:

```css
flex-direction:
column;
```

---

## flex-wrap

```css
flex-wrap:
wrap;
```

---

## flex-grow

Take available space.

```css
flex-grow:1;
```

---

## Common Layout

Navbar:

```css
display:flex;

justify-content:
space-between;

align-items:center;
```

---

# CSS Grid Deep Dive

Advanced layout system.

---

## Basic Grid

```css
.container{

 display:grid;

 grid-template-columns:
 repeat(3,1fr);

}
```

---

## Grid Gap

```css
gap:20px;
```

---

## Grid Areas

```css
grid-template-areas:
"header header"
"sidebar main";
```

---

## Responsive Grid

```css
grid-template-columns:

repeat(

 auto-fit,

 minmax(
 250px,
 1fr
 )

);
```

---

## Flexbox vs Grid

Flexbox:

```text
1D layout
```

Grid:

```text
2D layout
```

---

# Responsive Design

Lead interview favorite.

---

## Mobile First

Recommended.

```css
.container{

 width:100%;
}
```

---

## Breakpoints

```text
Mobile:
0-768px

Tablet:
768-1024px

Desktop:
1024+
```

---

# Media Queries

---

## Example

```css
@media(
 max-width:
768px
){

 .menu{

  display:none;

 }

}
```

---

## Mobile First Query

Preferred:

```css
@media(
 min-width:
768px
){}
```

---

# SCSS Deep Dive

Enterprise favorite.

---

## Variables

```scss
$primary:red;

button{

 color:
 $primary;

}
```

---

## Nesting

```scss
.card{

 h1{

  color:red;

 }

}
```

---

## Mixins

Reusable styles.

```scss
@mixin flex-center{

 display:flex;

 justify-content:
 center;

 align-items:
 center;

}
```

Usage:

```scss
.container{

 @include
 flex-center;

}
```

---

## Inheritance

```scss
%button{
 padding:10px;
}

.primary{

 @extend
 %button;

}
```

---

# Tailwind CSS

Huge trend.

Utility-first CSS.

---

## Installation

```bash
npm install tailwindcss
```

---

## Example

```html
<div class="

 flex
 justify-center
 items-center
 p-4
 rounded
">

</div>
```

---

## Benefits

```text
Fast UI
Reusable utilities
Responsive classes
```

---

## Responsive Tailwind

```html
<div class="

 sm:block
 md:flex
 lg:grid

">
</div>
```

---

# Animations

---

## Transition

Smooth effect.

```css
button{

 transition:
 all .3s ease;

}
```

---

## Hover Effect

```css
button:hover{

 transform:
 scale(1.1);

}
```

---

## Transform

```css
transform:
 rotate(45deg);
```

---

## Keyframes

```css
@keyframes slide{

 from{

  opacity:0;

 }

 to{

  opacity:1;

 }

}
```

---

## Animation Example

```css
.card{

 animation:
 slide 1s ease;

}
```

---

# Performance Optimization

Lead-level topic.

---

## Avoid Heavy Selectors

BAD:

```css
div div div p{}
```

---

## Prefer Class Selector

GOOD:

```css
.card{}
```

---

## Reduce Repaint

Avoid frequent:

```text
width
height
top
left
```

Prefer:

```text
transform
opacity
```

---

## Critical CSS

Load important styles first.

---

## Minify CSS

Use:

```text
cssnano
```

---

## Avoid Large CSS File

Split:

```text
Feature based CSS
```

---

# Advanced CSS Interview Questions

## Q1.
Flexbox vs Grid?

Flexbox:

1D.

Grid:

2D.

---

## Q2.
Specificity order?

```text
Inline
ID
Class
Element
```

---

## Q3.
box-sizing:border-box?

Includes:

```text
padding + border
```

inside width.

---

## Q4.
display:none vs visibility:hidden?

display:none:

removed.

visibility:hidden:

hidden but space exists.

---

## Q5.
absolute vs relative?

relative:

parent positioning.

absolute:

position relative to nearest parent.

---

## Q6.
fixed vs sticky?

fixed:

viewport fixed.

sticky:

scroll dependent.

---

## Q7.
Why transform better?

GPU optimized.

---

## Q8.
Flex-grow?

Available space sharing.

---

## Q9.
Grid auto-fit?

Responsive columns.

---

## Q10.
Mobile first?

Better responsive approach.

---

## Q11.
SCSS advantages?

```text
Variables
Mixins
Nesting
Reusable styles
```

---

## Q12.
Tailwind advantages?

Fast styling.

---

## Q13.
Transition vs animation?

Transition:

state change.

Animation:

continuous motion.

---

## Q14.
Reflow vs Repaint?

Reflow:

layout recalculation.

Repaint:

visual update.

---

## Q15.
How optimize CSS?

```text
Critical CSS
Minify
Transform
Avoid nesting
```

---

# Interview Traps

---

## Trap 1

### Overusing !important

Bad practice.

---

## Trap 2

### Using height:auto animation

Not performant.

---

## Trap 3

### Flex vs Grid confusion

---

## Trap 4

### Position absolute without parent relative

Bug issue.

---

# Quick Revision

```text
Flexbox
Grid
Media Query
SCSS
Tailwind
Animation
Specificity
Box Model
Responsive UI
Transform
Transition
```

---


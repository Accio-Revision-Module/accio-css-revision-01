# CSS Revision Notes

## Table of Contents

1. [CSS syntax and selectors](#css-syntax-and-selectors)
2. [CSS rules and declarations](#css-rules-and-declarations)
3. [Applying CSS styles to HTML elements](#applying-css-styles-to-html-elements)
4. [Using inline, internal, and external stylesheets](#using-inline-internal-and-external-stylesheets)
5. [CSS comments](#css-comments)
6. [Understanding the box model](#understanding-the-box-model)
7. [Controlling element dimensions](#controlling-element-dimensions)
8. [Box sizing](#box-sizing)
9. [Margin collapsing](#margin-collapsing)
10. [Adding borders and padding](#adding-borders-and-padding)
11. [Positioning elements](#positioning-elements)
12. [Floating elements](#floating-elements)
13. [Display property](#display-property)
14. [CSS units of measurement](#css-units-of-measurement)
15. [CSS layout techniques](#css-layout-techniques)
16. [Setting font family, size, and weight](#setting-font-family-size-and-weight)
17. [Text alignment and indentation](#text-alignment-and-indentation)
18. [Text decoration](#text-decoration)
19. [Line height and spacing](#line-height-and-spacing)
20. [Transparency and opacity](#transparency-and-opacity)
21. [Pseudo-classes and pseudo-elements](#pseudo-classes-and-pseudo-elements)
22. [Overriding styles and using !important](#overriding-styles-and-using-important)
23. [Timing functions](#timing-functions)
24. [CSS animation keyframes and properties](#css-animation-keyframes-and-properties)
25. [Delaying and repeating animations](#delaying-and-repeating-animations)
26. [Media queries and responsive breakpoints](#media-queries-and-responsive-breakpoints)

---

## CSS syntax and selectors

CSS uses a selector to target HTML elements and apply styles.

```css
selector {
  property: value;
}
```

## CSS rules and declarations

Rules consist of selectors and declarations.

```css
h1 {
  color: blue;
}
```

## Applying CSS styles to HTML elements

Styles can be applied inline, internally, or externally.

```html
<!-- Inline -->
<p style="color: red;">Red Text</p>

<!-- Internal -->
<style>
  p {
    color: green;
  }
</style>

<!-- External -->
<link rel="stylesheet" href="styles.css" />
```

## CSS comments

```css
/* This is a CSS comment */
```

## Understanding the box model

The box model consists of content, padding, border, and margin.

```css
.element {
  width: 200px;
  padding: 20px;
  border: 2px solid black;
  margin: 10px;
}
```

## Controlling element dimensions

```css
.element {
  width: 300px;
  height: 150px;
}
```

## Box sizing

```css
.element {
  box-sizing: border-box;
}
```

## Margin collapsing

```css
.container {
  margin-top: 20px;
}

.element {
  margin-top: 10px;
}
```

## Adding borders and padding

```css
.element {
  border: 1px solid black;
  padding: 10px;
}
```

## Positioning elements

```css
.relative {
  position: relative;
  top: 20px;
}

.absolute {
  position: absolute;
  top: 0;
  right: 0;
}
```

## Floating elements

```css
.left {
  float: left;
}

.right {
  float: right;
}
```

## Display property

```css
.block {
  display: block;
}

.inline {
  display: inline;
}

.inline-block {
  display: inline-block;
}
```

## CSS units of measurement

Use pixels, percentages, ems, and rems.

```css
.element {
  width: 200px;
  font-size: 16px;
  margin: 10%;
}
```

## CSS layout techniques

Use floats, flexbox, and grid for layout.

```css
/* Floats */
.float-left {
  float: left;
}

/* Flexbox */
.flex-container {
  display: flex;
  justify-content: center;
  align-items: center;
}

/* Grid */
.grid-container {
  display: grid;
  grid-template-columns: 1fr 1fr;
}
```

## Setting font family, size, and weight

```css
body {
  font-family: Arial, sans-serif;
  font-size: 16px;
  font-weight: bold;
}
```

## Text alignment and indentation

```css
.center {
  text-align: center;
}

.indented {
  text-indent: 20px;
}
```

## Text decoration

```css
.underline {
  text-decoration: underline;
}

.overline {
  text-decoration: overline;
}

.line-through {
  text-decoration: line-through;
}
```

## Line height and spacing

```css
.text {
  line-height: 1.5;
  letter-spacing: 1px;
}
```

## Transparency and opacity

```css
.transparent {
  background-color: rgba(0, 0, 0, 0.5);
}

.opaque {
  opacity: 0.8;
}
```

## Pseudo-classes and pseudo-elements

```css
/* Pseudo-class */
a:hover {
  color: red;
}

/* Pseudo-element */
p::first-line {
  font-weight: bold;
}
```

## Overriding styles and using !important

```css
.element {
  color: blue !important;
}
```

## Timing functions

Use timing functions in animations.

```css
@keyframes move {
  from {
    transform: translateX(0);
  }
  to {
    transform: translateX(100px);
  }
}

.element {
  animation: move 2s ease-in-out infinite;
}
```

## CSS animation keyframes and properties

```css
@keyframes fade {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}

.element {
  animation: fade 3s alternate infinite;
}
```

## Delaying and repeating animations

```css
.element {
  animation: fade 3s 1s alternate infinite;
}
```

## Media queries and responsive breakpoints

```css
@media screen and (max-width: 768px) {
  .element {
    font-size: 14px;
  }
}
```

---

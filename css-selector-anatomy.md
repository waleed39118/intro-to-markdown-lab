# The Anatomy of a CSS Selector

CSS selectors are patterns used to select and style HTML elements. Understanding how they work is key to writing effective and efficient stylesheets.

---

## Basic Structure

A CSS rule typically looks like this:

```css
selector {
  property: value;
}
```

- **Selector** — identifies the HTML element(s) to style
- **Property** — the aspect of the element to style (like color, font, or margin)
- **Value** — the desired setting for that property

---

## Types of Selectors

### 1. **Element Selector**

Targets all elements of a given type:

```css
p {
  color: blue;
}
```

> All `<p>` elements will have blue text.

---

### 2. **Class Selector**

Targets elements with a specific class attribute:

```css
.button {
  background-color: green;
}
```

> Any element with `class="button"` gets the green background.

---

### 3. **ID Selector**

Targets a specific element with a unique ID:

```css
#header {
  font-size: 2em;
}
```

> The element with `id="header"` will have larger text.

---

### 4. **Attribute Selector**

Targets elements with a specific attribute:

```css
input[type="text"] {
  border: 1px solid gray;
}
```

> All `<input>` fields of type text will have a gray border.

---

### 5. **Combinators & Pseudo-Classes**

You can combine selectors for more precise targeting:

```css
ul li:hover {
  background-color: lightgray;
}
```

> Highlights list items inside a `<ul>` when hovered over.

---

## Summary Table

| Selector Type | Example        | Description                          |
|---------------|----------------|--------------------------------------|
| Element       | `p`            | Selects all `<p>` elements           |
| Class         | `.card`        | Selects elements with class "card"   |
| ID            | `#main`        | Selects element with ID "main"       |
| Attribute     | `[type="text"]`| Selects based on attribute value     |
| Pseudo-class  | `:hover`       | Selects on a specific user state     |

---

Mastering CSS selectors gives you powerful control over your page’s design. Happy styling! 
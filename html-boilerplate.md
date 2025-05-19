# How to Write an HTML Boilerplate

An HTML boilerplate is a basic template used to start any HTML document. It sets up the structure and necessary metadata for your web page.

---

## The Basic Boilerplate

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Web Page</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>

  <h1>Hello, world!</h1>

  <script src="script.js"></script>
</body>
</html>
```

---

## What Each Part Does

| Tag | Purpose |
|-----|---------|
| `<!DOCTYPE html>` | Tells the browser to use HTML5 |
| `<html lang="en">` | Root element with language attribute |
| `<head>` | Contains metadata and links to stylesheets/scripts |
| `<meta charset="UTF-8">` | Sets character encoding |
| `<meta name="viewport">` | Makes page responsive on mobile devices |
| `<title>` | Title displayed on browser tab |
| `<link>` | Links external CSS |
| `<body>` | Contains visible content |
| `<script>` | Loads JavaScript |

---

## Pro Tips

- Add a favicon using `<link rel="icon" href="favicon.ico">`.
- Use semantic tags like `<header>`, `<nav>`, `<main>`, and `<footer>` to organize content.
- Always test in multiple browsers for compatibility.

This boilerplate is a solid foundation for any modern HTML project. 
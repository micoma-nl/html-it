# ✍️ HTML IT – Lightweight Bootstrap 5 WYSIWYG Editor

**HTML IT** is a fast, simple, and reusable WYSIWYG editor that you can easily integrate into any HTML project. It only requires Bootstrap 5 and a single class on your `<textarea>` — and you're good to go!

---

## 🚀 Installation

Add the following lines inside your `<head>`:

```html
<!-- Bootstrap 5 (required) -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- HTML IT CSS + JS -->
<link href="https://cdn.jsdelivr.net/gh/micoma-nl/html-it@latest/dist/html-it.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/gh/micoma-nl/html-it@latest/dist/html-it.min.js" defer></script>
```

Add the following line just above '</body>`:

```html
<!-- Bootstrap 5 (required) -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
```

---

## 🧠 Usage

Place a `<textarea>` with the class `html-it` in your HTML:

```html
<textarea class="html-it" placeholder="Type your content here..."></textarea>
```

HTML IT will automatically transform it into a visual WYSIWYG editor with a toolbar.

---

## 🧰 Features

✅ Clean HTML output  
✅ Compatible with Bootstrap 5  
✅ Undo / redo  
✅ Bold, italic, underline  
✅ Bullet & numbered lists  
✅ Insert links  
✅ Headings: H1 to H6 + paragraph via dropdown  
✅ Code view toggle  
✅ Lightweight and fast

---

## ⚡ Output

The editor keeps the generated HTML inside the original `<textarea>`. This can be used in forms, previews, or CMS systems.

Example output:

```html
<h1>Title</h1>
<p>Paragraph with <strong>bold</strong> text</p>
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
```

---

## 📦 File Structure

```text
/dist
├── html-it.min.css   → Editor styles
└── html-it.min.js    → Editor functionality
```

---

## 🛠️ Self-hosting

Place these files on your own server:

```html
<link href="/editor/html-it.min.css" rel="stylesheet">
<script src="/editor/html-it.min.js" defer></script>
```

---

## 🌐 CDN via JSDelivr

Use the JSDelivr CDN:

```html
<link href="https://cdn.jsdelivr.net/gh/micoma-nl/html-it/dist/html-it.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/gh/micoma-nl/html-it/dist/html-it.min.js" defer></script>
```

Or with a specific version:

```html
<link href="https://cdn.jsdelivr.net/gh/micoma-nl/html-it@v1.0.0/dist/html-it.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/gh/micoma-nl/html-it@v1.0.0/dist/html-it.min.js" defer></script>
```

---

## 💡 Planned Features (optional)

- [ ] Image upload  
- [ ] Insert tables  
- [ ] Text color selection  
- [ ] Dark mode  
- [ ] Markdown export  

---

## 📄 License

MIT © 2025 — by [MiCoMa](https://micoma.nl)

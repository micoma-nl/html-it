# ✍️ NiceEditor – Lightweight WYSIWYG Editor

NiceEditor is een snelle, simpele en herbruikbare WYSIWYG-editor die je eenvoudig kunt toevoegen aan elk HTML-project. Het vereist alleen Bootstrap 5 en één class op je `<textarea>`, en klaar ben je!

---

## 🚀 Installatie

Voeg de volgende regels toe in je `<head>`:

```html
<!-- Bootstrap 5 (verplicht) -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- NiceEditor CSS + JS -->
<link href="https://cdn.jsdelivr.net/gh/jouwdomein/nice-editor@latest/dist/nice-editor.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/gh/jouwdomein/nice-editor@latest/dist/nice-editor.min.js" defer></script>
```

---

## 🧠 Gebruik

Plaats in je HTML een `<textarea>` met de class `nice-editor`:

```html
<textarea class="nice-editor" placeholder="Typ hier je content..."></textarea>
```

NiceEditor transformeert dit automatisch naar een visuele editor met toolbar.

---

## 🧰 Features

✅ Clean HTML-output  
✅ Werkt met Bootstrap 5  
✅ Undo / redo  
✅ Bold, italic, underline  
✅ Opsommingen (bullet & genummerd)  
✅ Links invoegen  
✅ Kopstijlen: H1 t/m H6 + paragraaf via dropdown  
✅ Code view (toggle raw HTML)  
✅ Minimalistisch en snel

---

## ⚡ Output

De editor bewaart de gegenereerde HTML in het originele `<textarea>`-element. Je kunt dit eenvoudig gebruiken in formulieren, previews of CMS’en.

Voorbeeldoutput:

```html
<h1>Titel</h1>
<p>Paragraaf met <strong>vette</strong> tekst</p>
<ul>
  <li>Punt 1</li>
  <li>Punt 2</li>
</ul>
```

---

## 📦 Bestandenstructuur

```text
/dist
├── nice-editor.min.css   → opmaak van de editor
└── nice-editor.min.js    → JavaScript voor functionaliteit
```

---

## 🛠️ Zelf hosten?

Plaats deze bestanden op je eigen server:

```html
<link href="/editor/nice-editor.min.css" rel="stylesheet">
<script src="/editor/nice-editor.min.js" defer></script>
```

---

## 🌐 CDN via JSDelivr

Gebruik de JSDelivr CDN:

```html
<link href="https://cdn.jsdelivr.net/gh/jouwdomein/nice-editor/dist/nice-editor.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/gh/jouwdomein/nice-editor/dist/nice-editor.min.js" defer></script>
```

Of met specifieke versie:

```html
<link href="https://cdn.jsdelivr.net/gh/jouwdomein/nice-editor@v1.0.0/dist/nice-editor.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/gh/jouwdomein/nice-editor@v1.0.0/dist/nice-editor.min.js" defer></script>
```

---

## 💡 Toekomstige uitbreidingen (optioneel)

- [ ] Afbeeldingen uploaden
- [ ] Tabellen invoegen
- [ ] Kleurselectie voor tekst
- [ ] Dark mode
- [ ] Markdown-export

---

## 📄 Licentie

MIT © 2025 — door [JouwNaam](https://jouwdomein.nl)

# Exercise 3 – Links & Images ⭐

## 🎯 What You Will Learn
- How to create clickable links
- How to open links in a new tab
- How to display images
- What `alt` text is and why it matters

---

## 📖 Explanation

### Links – `<a>` tag

```html
<a href="URL">Clickable Text</a>
```

| Attribute | What it does |
|-----------|-------------|
| `href` | The URL to go to |
| `target="_blank"` | Opens in a **new tab** |

**Types of links:**
```html
<!-- Website -->
<a href="https://google.com">Google</a>

<!-- Another HTML file -->
<a href="about.html">About Page</a>

<!-- Email -->
<a href="mailto:you@email.com">Email Me</a>
```

### Images – `<img>` tag

```html
<img src="image.jpg" alt="Description of image" width="300">
```

| Attribute | What it does |
|-----------|-------------|
| `src` | Path or URL of the image |
| `alt` | Text shown if image doesn't load (also helps blind users) |
| `width` / `height` | Size in pixels |
| `title` | Tooltip on hover |

> ⚠️ `<img>` is self-closing – no `</img>` needed!

---

## ✅ Your Task

1. Add a link to your favourite website
2. Make that link open in a new tab
3. Add an image from the internet (right-click any image → Copy Image Address)
4. Write a meaningful `alt` text for your image

---

## 💡 Remember
- Always write `alt` text – it's important for accessibility
- `href` = "hypertext reference" – it's the destination

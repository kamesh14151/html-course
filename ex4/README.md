# Exercise 4 – Lists ⭐

## 🎯 What You Will Learn
- Unordered lists (bullet points)
- Ordered lists (numbered)
- Nested lists (list inside a list)
- Description lists (term + definition)

---

## 📖 Explanation

### Unordered List – `<ul>`
Shows items with bullet points (•)
```html
<ul>
  <li>Item one</li>
  <li>Item two</li>
</ul>
```

### Ordered List – `<ol>`
Shows items with numbers (1, 2, 3...)
```html
<ol>
  <li>First</li>
  <li>Second</li>
</ol>
```

**Tip:** Use `start="5"` to start numbering from 5.

### Nested List
Put a `<ul>` or `<ol>` **inside** a `<li>` to create sub-items:
```html
<ul>
  <li>Fruits
    <ul>
      <li>Mango</li>
      <li>Apple</li>
    </ul>
  </li>
</ul>
```

### Description List – `<dl>`
For terms and their meanings:
```html
<dl>
  <dt>Term</dt>
  <dd>Definition of the term</dd>
</dl>
```

| Tag | Meaning |
|-----|---------|
| `<ul>` | Unordered (bullet) list |
| `<ol>` | Ordered (numbered) list |
| `<li>` | List item |
| `<dl>` | Description list |
| `<dt>` | Term (the word) |
| `<dd>` | Description (the meaning) |

---

## ✅ Your Task

1. Create an unordered list of your 5 favourite foods
2. Create an ordered list of steps to make tea
3. Create a nested list: "My Skills → HTML, CSS, JS"
4. Create a description list for 3 programming languages

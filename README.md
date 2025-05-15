# 🛒 Shopping List Webpage Lab

A simple HTML exercise to build a shopping list webpage with nested lists, internal hyperlinks, and a navigational menu. This demonstrates fundamental HTML skills: lists, anchors, and semantic structure.

---

## 📖 Lab Overview

You've forgotten items on your shopping trip one too many times—time to build a shopping list page! In this lab you will:

1. Create nested lists of shopping items (food & electronics).  
2. Add internal hyperlinks from item names to their descriptions.  
3. Build a top navigation menu to jump between "Food Items" and "Electronics Items."  
4. Include a "Back to top" link.

### Lab Status
- **Tasks completed:** 7 of 8  
- **File under test:** `shoppinglist.html`

---

## 📂 Project Structure

```
project-root/
├── LICENSE
└── shoppinglist.html # Main HTML file implementing lab requirements
```

---

## 🚀 Features

- **Top Navigation**  
  `<nav>` bar linking to `#food` and `#electronics`.

- **Nested Lists**  
  - Food Items  
    - Fruits  
      - Apples (linked to description)  
      - Mangoes  
      - Bananas  
    - Vegetables  
    - Bread  
    - Dairy  
  - Electronics Items  
    - Smartphone  
    - Headphones  
    - Television (linked to description)

- **Item Descriptions**  
  - `<h3 id="apples">About Apples</h3>` with a descriptive `<p>`.  
  - `<h3 id="tv">About Television</h3>` with a descriptive `<p>`.

- **Internal Links**  
  - Item names link down to their `<h3>` descriptions.  
  - "Back to top" link returns to the top of the page.

---

## 🛠️ How to Run

1. **Open in VS Code**  
   ```bash
   code shoppinglist.html
   ```

2. **Preview in Browser**
   - Install the Live Server extension (optional).
   - Right-click shoppinglist.html → Open with Live Server
   - Or simply double-click the file to open in your default browser.

3. **Test Navigation**
   - Click "Food Items" / "Electronics Items" in the nav bar.
   - Click "Apples" / "Television" list items to scroll to their descriptions.
   - Click "Back to top" at the bottom to return to the top.

## 🎯 Lab Steps Completed

| Step | Description | Status |
|------|-------------|--------|
| 1 | Open shoppinglist.html in VS Code | ✅ |
| 2 | Add `<h2 id="food">Food Items</h2>` | ✅ |
| 3 | Create `<ul>` of food categories (Fruits, Vegetables, Bread, Dairy) | ✅ |
| 4 | Add `<h2 id="electronics">Electronics Items</h2>` | ✅ |
| 5 | Create `<ul>` of electronics categories (Smartphone, Headphones, Television) | ✅ |
| 6 | Nest `<ul>` under "Fruits" with Apples, Mangoes, Bananas | ✅ |
| 7 | Add `<h2>Item Descriptions</h2>` | ✅ |
| 8 | Add `<h3 id="apples">About Apples</h3>` + `<p>` description | ✅ |
| 9 | Add `<h3 id="tv">About Television</h3>` + `<p>` description | ✅ |
| 10 | Link "Apples" → #apples and "Television" → #tv | ✅ |
| 11 | Add "Back to top" link `<a href="#top">Back to top</a>` | ✅ |
| 12 | Insert `<nav>` at top with links to #food & #electronics | ✅ |

**Note:** You may want to add `id="top"` on the `<body>` or an `<h1>` to make the "Back to top" link functional.

## 👀 Preview

Open the HTML file in your browser to see:
- A navigation bar at the top.
- Nested lists for food & electronics.
- Clickable items ("Apples" & "Television") that scroll to their descriptions.
- A "Back to top" link at the bottom.

## 💡 Next Steps

- Style with CSS (e.g., add colors, spacing, responsive breakpoints).
- Enhance accessibility (ARIA landmarks, skip-links).
- Expand to more categories & items.
- Integrate JavaScript for dynamic list management.

## ✍️ Author

Masingita Ottis Maluleke
- LinkedIn: thefreelancer201
- GitHub: Tinyu01

## 📜 License

This repository is for educational purposes only. No formal license applied.

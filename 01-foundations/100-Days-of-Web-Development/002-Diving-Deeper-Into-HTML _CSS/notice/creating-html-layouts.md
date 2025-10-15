# 📘 Day 11 — Creating HTML Layouts

A **layout** is the structure and arrangement of content on a webpage.  
Learning how to create HTML layouts is essential for organizing information clearly and making pages visually appealing.

---

## 🏗 1. HTML Layout Basics

HTML layouts are created by combining **structural elements** (containers) and **grouping content** logically.

### Common Structural Elements:

- `<header>` → Top section, usually contains logo, navigation  
- `<nav>` → Navigation menu  
- `<main>` → Main content of the page  
- `<section>` → Group related content  
- `<article>` → Independent content like blog posts or news  
- `<aside>` → Sidebar content, tips, or ads  
- `<footer>` → Bottom section, usually contains copyright, links

---

## 📦 2. Example: Basic Page Layout

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Webpage Layout</title>
</head>
<body>

  <header>
    <h1>My Website</h1>
    <nav>
      <a href="#">Home</a> |
      <a href="#">About</a> |
      <a href="#">Contact</a>
    </nav>
  </header>

  <main>
    <section>
      <h2>About Me</h2>
      <p>Welcome to my personal webpage!</p>
    </section>

    <section>
      <h2>Projects</h2>
      <p>Check out my recent projects below.</p>
    </section>
  </main>

  <aside>
    <h3>Tips & News</h3>
    <p>Stay updated with the latest tutorials.</p>
  </aside>

  <footer>
    <p>&copy; 2025 Mohammed EL-IDRISSI</p>
  </footer>

</body>
</html>

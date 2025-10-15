# 📘 CSS Selectors & Combinators

CSS selectors allow you to **target HTML elements** and apply styles.  
Combinators define **relationships between elements** and help you target elements more precisely.

---

## 🎯 1. What Are Selectors?

A **selector** tells the browser **which HTML element(s) to style**.  

### Common Types of Selectors:

1. **Element selector** – targets HTML tags  
   ```css
   p {
     color: blue;
   }
→ Targets all ```<p>``` elements.

2. **Class selector** – targets elements with a specific class
```css
.highlight {
  background-color: yellow;
}
```


→ Targets all elements with ```class="highlight"```.

3. **ID selector** – targets an element with a unique ID

```css
#main-title {
  font-size: 36px;
}
```

→ Targets the element with ```id="main-title"```.

## 🔗 2. Combinators

Combinators describe relationships between elements.

**a) Descendant Selector (space)**

Targets all elements that are **descendants of another element**.
```css
div p {
  color: green;
}
```

 - Targets all ```<p>``` inside ```<div>``` (any depth).

**b) Child Selector (```>```)**

Targets **direct children** only.

```css
div > p {
  color: red;
}
```

 - Only targets ```<p>``` elements that are directly inside a ```<div>```.

**c) Adjacent Sibling Selector (```+```)**

Targets the **next sibling element** immediately after another.
```css
h2 + p {
  font-style: italic;
}
```

 - Targets the ```<p>``` right after an ```<h2>```.

**d) General Sibling Selector (```~```)**

Targets **all sibling elements** that follow a specific element.
```css
h2 ~ p {
  color: gray;
}
```

 - All ```<p>``` elements after an ```<h2>``` inside the same parent.

## 🖋 3. Combining Selectors

You can combine selectors to target elements more specifically:
```css
div.highlight > p.special {
  color: purple;
}
```

 - Targets ```<p>``` elements with class special that are direct children of ```<div>``` elements with class highlight.

## 💡 4. Quick Tips

 - Use **class selectors** for reusable styles.

 - Use **ID selectors** for unique elements.

 - Learn **combinators** to target elements without extra classes.

 - Avoid overusing **inline styles**; they have the highest specificity and are harder to maintain.

## ✅ 5. Summary Table

| Selector / Combinator   | Description          | Example                          |
|-------------------------|-------------------|----------------------------------|
| `p`                     | Element selector    | All `<p>` tags                   |
| `.class`                | Class selector      | All elements with `class="class"`|
| `#id`                   | ID selector         | Element with `id="id"`           |
| `ancestor descendant`    | Descendant combinator | All descendants inside ancestor |
| `parent > child`        | Child combinator    | Direct children only             |
| `prev + next`           | Adjacent sibling    | Next element only                |
| `prev ~ siblings`       | General sibling     | All following siblings           |

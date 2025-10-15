# 📘 Understanding Cascading, Inheritance & Specificity in CSS

CSS can sometimes feel confusing when multiple rules apply to the same element.  
To understand how the browser decides which styles to use, we need to learn about **Cascading**, **Inheritance**, and **Specificity**.

---

## 🌊 1. Cascading

The **Cascading** principle determines which CSS rules apply when multiple rules target the same element.  
CSS rules "cascade" from top to bottom, and the **last rule wins** if the specificity is the same.

### Example:

```html
<p class="text">Hello World!</p>

<style>
  p {
    color: blue;
  }

  .text {
    color: red;
  }
</style>

# 🧩 The Development Server & The Local Website Address 

In the previous lecture, we started a **local development web server** via the **Live Server** extension for **Visual Studio Code**.

---

## ⚙️ What Is a “Development Web Server”?

A **local development web server** is a software that serves your website **locally on your own machine**.  
It does **not** expose your machine or your website to the internet — it can only be visited from your own computer.

This “web server software” (for example, the **Live Server** extension) listens for incoming **HTTP requests** and sends back **responses** (containing HTML, CSS, images, etc.).

> 💡 Remember the request + response model from the first course section!

Later in the course, you’ll also set up your own web server capable of doing more advanced tasks using **Node.js** (starting in section 16).

---

## 🌍 What’s This Address: `127.0.0.1`?

As mentioned above, the development server **hosts the website from your local machine** to your local machine.

You already know that when users enter a web address (like `academind.com`), it’s translated to an **IP address** that uniquely identifies a machine on the internet.

`127.0.0.1` is one such IP address — but it’s **special**!

- `127.0.0.1` is **reserved** for your local computer.  
- It always points back to **your own machine** — never to another computer on the web.

So:
- If **you** enter `127.0.0.1` in your browser, it connects to **your** computer.
- If **I** enter `127.0.0.1`, it connects to **mine**.

That’s why it’s perfect for **local development**: You can test websites locally without making them public.

---

## 🏠 The Alias: `localhost`

`localhost` is simply a **nickname (alias)** for `127.0.0.1`.  
You can type either of the following in your browser and they’ll mean the same thing:


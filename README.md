# 📰 Article Preview Component

This is a solution to the **Article Preview Component Challenge** on Frontend Mentor.
The goal of this project is to practice building responsive UI components using **HTML, CSS, and JavaScript**.

---


## 🚀 Demo

* 🔗 Live Site: add-your-live-link-here
* 🔗 Frontend Mentor Solution: add-your-solution-link-here

---

## 📌 Overview

This project shows an article card that contains:

* Article image
* Title and description
* Author information
* Share button with social media icons

When the user clicks the **share button**, a share box appears showing social media links.

---

## 🛠️ Built With

* HTML5
* CSS3
* Flexbox
* JavaScript (DOM Manipulation)

---

## ⚙️ How It Works

JavaScript is used to toggle the share box when the button is clicked.

```javascript
let btn = document.querySelector("button");
let boxShare = document.querySelector(".share-box");

btn.addEventListener("click", () => {
  boxShare.classList.toggle("none");
});
```

---

---

## 💡 What I Learned

From this project I practiced:

* DOM manipulation
* Event listeners
* Responsive layout
* Using Flexbox for layout

---

## 👨‍💻 Author

* GitHub: https://github.com/sohib-ezaldeen
* Frontend Mentor: https://www.frontendmentor.io/profile/sohib-ezaldeen

---

⭐ If you like this project, feel free to give it a star!

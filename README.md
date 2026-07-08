# Job Portal Website

## 📖 About
This is a Job Portal Website developed using HTML, CSS, and JavaScript. It helps users explore job opportunities and apply through a simple and responsive interface.

## ✨ Features
- Responsive design
- Home page
- Job listings
- Apply page
- Contact page
- Modern user interface

## 🛠️ Technologies Used
- HTML5
- CSS3
- JavaScript

## 📁 Project Structure
```
Job-Portal/
│── index.html
│── jobs.html
│── apply.html
│── contact.html
│── css/
│── js/
│── images/
│── README.md
```

## 🚀 How to Run
1. Download or clone the repository.
2. Open the project folder.
3. Double-click `index.html` or open it in a web browser.

## 🌐 Live Demo
Add your Netlify or GitHub Pages link here after deployment.

## 👨‍💻 Author
Your Name
// ------------------------
// HOME PAGE
// ------------------------

function searchJobs() {
    let title = document.getElementById("jobTitle").value || "";
    let location = document.getElementById("location").value || "";

    localStorage.setItem("title", title);
    localStorage.setItem("location", location);

    window.location.href = "jobs.html";
}



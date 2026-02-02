# Ex01 Portfolio
## Date: 02/02/2026

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM

HTML 
```
<!DOCTYPE html>
<html>
<head>
  <title>Bharathi's Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<h1>BHARATHI M K</h1>

<div class="tabs">
  <button onclick="openTab('tab1')">Profile</button>
  <button onclick="openTab('tab2')">Education</button>
  <button onclick="openTab('tab3')">Work</button>
</div>

<!-- TAB 1 -->
<div id="tab1" class="tab-content">

  <h2>Welcome to My Portfolio</h2>
  <p>I am a student passionate about technology and development.</p>

  <h2>About Me</h2>
  <p>
    Hi! BHARATHI M K, an undergraduate student at Saveetha Engineering College,
    pursuing Information Technology. Passionate about technology, I enjoy
    exploring programming languages like Python, C, C++, and web development
    with HTML, CSS, and MySQL.
  </p>

</div>

<!-- TAB 2 -->
<div id="tab2" class="tab-content">

  <h2>Education</h2>
  <p><strong>Saveetha Engineering College</strong><br>BE, CSE</p>

  <h2>Skills</h2>
  <ul class="skills">
    <li>Python</li>
    <li>C</li>
    <li>C++</li>
    <li>HTML</li>
    <li>CSS</li>
    <li>MySQL</li>
  </ul>

</div>

<!-- TAB 3 -->
<div id="tab3" class="tab-content">

  <h2>Projects</h2>
  <div class="project-card">
    <h3>Portfolio Website</h3>
    <p>A simple personal portfolio website showcasing my details, skills, and projects.</p>
    <a href="https://github.com/BHARATHI20MK" target="_blank">View on GitHub</a>
  </div>

  <h2>Contact Me</h2>
  <p>Email: <a href="mailto:bharathimohann2004@gmail.com">bharathimohann2004@gmail.com</a></p>
  <p>GitHub: <a href="https://github.com/BHARATHI20MK" target="_blank">github.com/BHARATHI20MK</a></p>

</div>



<script>
function openTab(tabName) {
  let i;
  let content = document.getElementsByClassName("tab-content");

  for (i = 0; i < content.length; i++) {
    content[i].style.display = "none";
  }

  document.getElementById(tabName).style.display = "block";
}

openTab("tab1");
</script>

</body>
</html>


```

CSS

```

body {
  font-family: Arial;
  text-align: center;
  margin: 0;
  background: #f4f4f9;
}

h1 {
  background: #333;
  color: white;
  padding: 15px;
  margin: 0;
}

.tabs {
  margin: 20px;
}

.tabs button {
  padding: 10px 20px;
  margin: 5px;
  border: none;
  cursor: pointer;
  background: #333;
  color: white;
  font-weight: bold;
  border-radius: 5px;
}

.tabs button:hover {
  background: #555;
}

.tab-content {
  display: none;
  padding: 20px;
  width: 70%;
  margin: auto;
  background: white;
  border-radius: 10px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

.skills {
  list-style: none;
  padding: 0;
}

.skills li {
  background: #333;
  color: white;
  margin: 5px;
  padding: 8px;
  border-radius: 20px;
  display: inline-block;
}

.project-card {
  background: #f9f9f9;
  padding: 15px;
  margin: 10px;
  border-radius: 8px;
}

footer {
  margin-top: 20px;
  padding: 10px;
  background: #333;
  color: white;
}


```



## OUTPUT

<img width="1919" height="1076" alt="Screenshot 2026-02-02 152544" src="https://github.com/user-attachments/assets/3d89b45d-6d44-4ffa-a33b-8e0b3c2c9f9e" />

<img width="1919" height="1078" alt="Screenshot 2026-02-02 152556" src="https://github.com/user-attachments/assets/f2134553-8b13-4b7a-b012-ed6d0dfe293f" />

<img width="1919" height="1078" alt="Screenshot 2026-02-02 152607" src="https://github.com/user-attachments/assets/45825287-3e50-4670-a82a-de3de4755fbf" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.

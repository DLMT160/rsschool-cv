
<!DOCTYPE html>
<html lang="en">
<head>
<title>Page Title</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
    box-sizing: border-box;
}

body {
    font-family: Arial;
    margin: 0;
}

.header {
    padding: 80px;
    text-align: center;
    background: #4169E1;
    color: white;
}

.header h1 {
    font-size: 40px;
}

.navbar {
    overflow: hidden;
    background-color: #333;
}

.navbar a {
    float: left;
    display: block;
    color: white;
    text-align: center;
    padding: 14px 20px;
    text-decoration: none;
}


.navbar a.right {
    float: inline-end;
}

.navbar a:hover {
    background-color: #ddd;
    color: black;
}

.row {  
    display: -ms-flexbox; /* IE10 */
    display: flex;
    -ms-flex-wrap: wrap; /* IE10 */
    flex-wrap: wrap;
}

.side {
    -ms-flex: 30%; /* IE10 */
    flex: 30%;
    background-color: #f1f1f1;
    padding: 20px;
}

.main {   
    -ms-flex: 70%; /* IE10 */
    flex: 70%;
    background-color: white;
    padding: 20px;
}


.footer {
    padding: 20px;
    text-align: center;
    background: #4169E1;
}

.footerCourse {
  text-decoration: none;
}

.footerCourse img {
  display: block;
  width: 75px;
  height: 28px;
}

.footerGit img {
  display: block;
  width: 28px;
  height: 28px;
}

html {
  scroll-behavior: smooth;
}

.CodeExample {
  padding-block-start: 16px;
  padding-inline-end: 34px;
  padding-block-end: 16px;
  padding-left: 34px;
  margin-top: 0;
  margin-bottom: 0;
  font-family: monospace;
  font-size: 16px;
  line-height: 28px;
  background-color: #f5f5f5;
}


</style>
</head>
<body>

<div class="header">
  <h1>Berg Artem</h1>
</div>

<div class="navbar">
  <a href="#Contacts">Contacts</a>
  <a href="#About">About</a>
  <a href="#Skills">Skills</a>
  <a href="#Education">Education</a>
  <a href="#CodeExample">Code Example</a>
  <a href="#Languages">Languages</a>
</div>

<div class="row">
  <div class="side">
      <h2 id="About">About Me</h2>
      <img src="https://avatars.githubusercontent.com/u/93256627" width="150" height="150" alt="Berg Artem" />
      <p>First of all, I never tryed coding before in my life. This is my first step on a journey to become Frontend developer.</p>
  </div>
  <div class="main">
      <h2 id="Contacts">Contacts</h2>
      <h4 id="phone"><strong>Phone</strong>: +79215648286</h4>
      <h4 id="email"><strong>Email</strong>: LABerg010@yandex.ru</h4>  

<h2 id="Skills">Skills</h2>
<ul>
  <li>HTML5, CSS3</li>
  <li>JavaScript Basics</li>
  <li>Git and GitHub</li>
  <li>Adobe photoshop</li>
  <li>Adobe Premiere </li>
</ul>
      <h2 id="Education">Education</h2>
<ul>
  <li>2010-2014 St. Petersburg College of Telecommunications</li>
  <li>2014-2016 Saint Petersburg University of Telecommunications</li>
</ul>
      <h2 id="CodeExample"><strong>Code example:</strong></h2>
<div class="CodeExample"><div class="highlight"><pre class="highlight"><code>function multiply (a, b) {
  return a * b
} 
</code></pre></div></div>
      <h2 id="Languages">Languages</h2>
      <ul>
  <li>Russian - Native</li>
  <li>English - Pre-Intermediate</li>
</ul>

</div>
</div>

<div class="footer">
  <h2>03.01.2022</h2>
  <a class="footerCourse" href="https://rs.school/js-stage0" title="Link to RS School course" aria-label="Link to RS School course">
            <img src="https://rs.school/images/rs_school_js.svg" width="75" height="28" alt="RS School" />
          </a>
<a class="footerGit" href="https://github.com/DLMT160" title="Link to GitHub Account" aria-label="Link to GitHub Account">
            <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="28" height="28" alt="RS School" />
          </a>

</div>

</body>
</html>




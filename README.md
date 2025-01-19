<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chandupa's Portfolio</title>
    
    <style>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    color: #333;
    background-color: #b267b1;
    line-height: 1.6;
}

.profile-image img {
    width: 200px; 
    height: 250px; 
    border-radius: 50%; 
    display: block;
    margin: 0 auto;
    border: 3px solid #555;
}

header {
    background-color: #555;
    color: white;
    padding: 10px 0;
}

nav ul {
    list-style: none;
    text-align: center;
    margin: 0;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

nav ul li a:hover {
    text-decoration: underline;
}

.section {
    padding: 20px;
    margin: 20px auto;
    max-width: 900px;
    background: white;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

.section h2 {
    text-align: center;
    color: #645e5e;
}

.columns {
    display: flex;
    justify-content: space-between;
    margin-top: 20px;
}

.columns div {
    width: 45%;
}

.skills {
    display: flex;
    justify-content: space-between;
    margin-top: 20px;
}

.skills div {
    width: 45%;
}

.skills ul {
    list-style: none;
    padding: 0;
}

.skills ul li {
    margin-bottom: 5px;
}

.contact a {
   color: #007BFF;
   text-decoration: none;
}
.contact a:hover {
    text-decoration: underline;
    color: #b267b1;
}

footer {
  height:50%;
    text-align: center;
    padding: 10px 0;
    background-color: #d6d6d6;
    color: white;
    margin-top: 20px;
}

    </style>

</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#skills">Skills & Hobbies</a></li>
                <li><a href="#cv">My CV</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="about" class="section">
            <div class="content">
                <div class="profile-image">
                    <img src="profile.jpg" alt="My Photo">
                </div>
                <div class="text">
                    <h2>About Me</h2>
                    <p>  Methanatath daapan ubata ona ekak </p>
                </div>
            </div>
        </section>

        <section id="education" class="section">
            <h2>Educational Qualifications</h2>
            <div class="columns">
                <div>
                    <h3>Secondary Education</h3>
                    <p>Rahula College</p>
                    <p>G.C.E. Advanced Level: </p>
                    <p>G.C.E. Ordinary Level: </p>
                </div>
                <div>
                    <h3>Higher Education</h3>
                    <p>An Undergraduate Student of SLIIT</p>
                </div>
                <div>
                    <h3>Other</h3>
                    <p>A member of the school rugby team</p>
                    <p>A member of Nilwala Leo Club</p>
                </div>
            </div>
        </section>

        <section id="skills" class="section">
            <h2>Skills</h2>
            <p>  Methanatath daapan ubata ona ekak </p>
        </section>


        <section id="cv" class="section">
          <h2>My Curriculum Vitae</h2>
          <p> Methanatath daapan ubata ona ekak </p>
      </section>


      <section id="conclusion" class="section">
          <div class="columns">
              <div>
                  <h3>Conclusion</h3>
                  <p> Methanatath uba kamathi magulak daapan hode</p>
              </div>

              <div>
                <section class="contact">
                  <h3>Contact Details</h3>
                  <p>Email: <a href="mailto:vidurawannihayage@outlook.com">Ube-eka-daapan@outlook.com</a></p>
                  <p> LinkedIn: <a href="https://linkedin.com/in/your-profile" target="_blank">linkedin.com/in/your-profile</a> </p>
                </section>
              </div>
          </div>

      </section>
    </main>

    <footer>
        <p>© 2025 Chandupa's Portfolio</p>
    </footer>
</body>
</html>

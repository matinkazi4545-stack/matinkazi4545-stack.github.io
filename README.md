<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Matin Kazi - Web Developer / Data Analyst</title>
    <link rel="stylesheet" href="css/style.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">

    <style>
    /* General Styles */
body {
    margin: 0;
    padding: 0;
    font-family: 'Poppins', sans-serif;
    background-color: #000;
    color: #fff;
}

/* Header Section */
.header {
    background-color: #0d0d0d;
    padding: 80px 20px;
}

.header-container {
    display: flex;
    justify-content: space-around;
    align-items: center;
}

.header-text {
    max-width: 50%;
}

.header h1 {
    font-size: 48px;
    margin: 0;
}

.header h1 span {
    color: #f5a623;
}

.header p {
    font-size: 24px;
    margin-top: 10px;
}

.buttons-container {
    margin-top: 30px;
}

.buttons-container .btn {
    padding: 10px 30px;
    color: #fff;
    background-color: #f5a623;
    border: none;
    border-radius: 5px;
    text-decoration: none;
    margin: 0 10px;
}

.btn.hire-me {
    background-color: #f5a623;
}

.btn.my-works {
    background-color: #000;
    border: 1px solid #f5a623;
}

/* Header Image */
.header-image img {
    width: 300px;
}

/* Navigation Bar */
.navbar {
    background-color: #151515;
    padding: 20px;
    text-align: center;
}

.navbar ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
}

.navbar ul li {
    display: inline;
    margin: 0 15px;
}

.navbar ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 18px;
}

/* About Section */
.about {
    padding: 60px 20px;
    background-color: #0d0d0d;
    text-align: center;
}

.about h2 {
    font-size: 36px;
    margin-bottom: 30px;
}

.about-content {
    display: flex;
    justify-content: center;
    align-items: center;
}

.profile-image img {
    width: 250px;
    height: 250px;
}

.about-details {
    margin-left: 30px;
}

.about-details p {
    font-size: 18px;
    margin: 5px 0;
}

.about-details .btn {
    margin-top: 20px;
    padding: 10px 20px;
    background-color: #f5a623;
    border: none;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
}

/* Skills Section */
.skills {
    background-color: #0d0d0d;
    padding: 60px 20px;
    text-align: center;
}

.skills h2 {
    font-size: 36px;
    margin-bottom: 30px;
}

.skills-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 20px;
}

.skill {
    font-size: 18px;
}

.progress {
    background-color: #333;
    border-radius: 25px;
    height: 15px;
    margin-top: 5px;
    overflow: hidden;
}

.progress-bar {
    height: 100%;
    background-color: #f5a623;
    border-radius: 25px;
}

/* General styling */
p {
    margin: 0 0 1rem;
    line-height: 1.6;
}

.header p,
.about-details p {
    margin-top: 0;
}

.navbar ul,
.skills-grid {
    margin: 0;
    padding: 0;
}

.navbar ul {
    list-style-type: none;
    display: flex;
    justify-content: space-around;
    background-color: #333;
    padding: 10px 20px;
}

.navbar ul li a {
    color: white;
    text-decoration: none;
    padding: 10px 20px;
    display: block;
    margin: 0;
}

.navbar ul li a:hover {
    background-color: #444;
}

.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 50px;
}

.header-container {
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    align-items: center;
}

.header-image img {
    max-width: 400px;
}

.btn {
    background-color: #f0a500;
    padding: 10px 20px;
    color: #fff;
    text-decoration: none;
    margin-right: 20px;
}

.btn:hover {
    background-color: #e59400;
}

/* Contact Page */
.contact-page {
    max-width: 1100px;
    margin: 0 auto;
    padding: 60px 20px 80px;
    text-align: center;
}

.contact-page h1 {
    margin: 0 0 10px;
    font-size: 40px;
    color: #f5a623;
}

.contact-intro {
    margin-bottom: 40px;
    color: #ddd;
    font-size: 18px;
}

.contact-content {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 40px;
    text-align: left;
}

.contact-details,
.contact-form-section {
    padding: 30px;
    background-color: #1b1b1b;
    border: 1px solid #333;
    border-radius: 5px;
}

.contact-content h2 {
    margin: 0 0 25px;
    color: #f5a623;
    font-size: 28px;
}

.contact-item {
    margin-bottom: 22px;
}

.contact-item h3 {
    margin: 0 0 5px;
    color: #f5a623;
    font-size: 17px;
}

.contact-item p {
    color: #eee;
}

.contact-item a {
    color: #fff;
    text-decoration: none;
}

.contact-item a:hover {
    color: #f5a623;
}

.contact-form {
    display: flex;
    flex-direction: column;
}

.contact-form label {
    margin-bottom: 7px;
    color: #eee;
    font-size: 16px;
}

.contact-form input,
.contact-form textarea {
    width: 100%;
    margin-bottom: 18px;
    padding: 12px;
    border: 1px solid #555;
    border-radius: 4px;
    background-color: #111;
    color: #fff;
    font: inherit;
}

.contact-form input:focus,
.contact-form textarea:focus {
    outline: 2px solid #f5a623;
    border-color: #f5a623;
}

.contact-form textarea {
    resize: vertical;
}

.contact-submit {
    padding: 12px 20px;
    border: none;
    border-radius: 5px;
    background-color: #f5a623;
    color: #fff;
    cursor: pointer;
    font: inherit;
}

.contact-submit:hover {
    background-color: #e59400;
}

@media (max-width: 700px) {
    .contact-content {
        grid-template-columns: 1fr;
        gap: 25px;
    }

    .navbar ul {
        flex-wrap: wrap;
        gap: 5px;
    }

    .navbar ul li a {
        padding: 8px 10px;
        font-size: 16px;
    }
}


    </style>
</head>
<body>
    <nav class="navbar">
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="resume.html">Resume</a></li>
            <li><a href="skills.html">Skills</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>

    <header class="header">
        <div class="container header-container">
            <div class="header-text">
                <h1>Hello!<br>I'm <span>Matin Kazi</span></h1>
                <p>Web Developer / Data Analyst</p>
                <div class="buttons-container">
                    <a href="contact.html" class="btn hire-me">Hire Me</a>
                    <a href="skills.html" class="btn my-works">My Works</a>
                </div>
            </div>
            <div class="header-image">
                <img src="asset/profile2.png" alt="Matin Kazi">
            </div>
        </div>
    </header>

    <section class="about" id="about">
        <div class="container">
            <h2>About Me</h2>
            <div class="about-content">
                <div class="profile-image">
                    <img src="asset/profile.png" alt="Matin Kazi">
                </div>
                <div class="about-details">
                    <p><strong>Name:</strong> Matin Kazi</p>
                    <p><strong>Date of Birth:</strong> June 28, 2007</p>
                    <p><strong>Address:</strong> Camp, Pune</p>
                    <p><strong>Zip Code:</strong> 411001</p>
                    <p><strong>Email:</strong> matinkazi4545@gmail.com</p>
                    <p><strong>Phone:</strong> 9403121645</p>
                    <p><strong>Projects Complete:</strong> 7</p>
                    <br/>
                    <a href="resume.html" class="btn download-cv">Download CV</a>
                </div>
            </div>
        </div>
    </section>

    <section class="skills" id="skills">
        <div class="container">
            <h2>My Skills</h2>
            <div class="skills-grid">
                <div class="skill"><span>Python</span><div class="progress"><div class="progress-bar" style="width: 70%;"></div></div></div>
                <div class="skill"><span>SQL</span><div class="progress"><div class="progress-bar" style="width: 85%;"></div></div></div>
                <div class="skill"><span>Power BI</span><div class="progress"><div class="progress-bar" style="width: 80%;"></div></div></div>
                <div class="skill"><span>Excel</span><div class="progress"><div class="progress-bar" style="width: 80%;"></div></div></div>
                <div class="skill"><span>HTML5</span><div class="progress"><div class="progress-bar" style="width: 95%;"></div></div></div>
                <div class="skill"><span>CSS3</span><div class="progress"><div class="progress-bar" style="width: 90%;"></div></div></div>
                <div class="skill"><span>JavaScript</span><div class="progress"><div class="progress-bar" style="width: 80%;"></div></div></div>
                <div class="skill"><span>PHP</span><div class="progress"><div class="progress-bar" style="width: 90%;"></div></div></div>
            </div>
        </div>
    </section>
<section>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Matin Kazi - About</title>
    <link rel="stylesheet" href="css/style.css">
    <header>
        <nav class="navbar">
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="resume.html">Resume</a></li>
                <li><a href="skills.html">Skills</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="about">
        <div class="container">
            <h2>About Me</h2>
            <div class="about-content">
                <div class="profile-image">
                    <img src="asset/profile.png" alt="Matin Kazi">
                </div>
                <div class="about-details">
                    <p><strong>Name:</strong> Matin Kazi</p>
                    <p><strong>Date of Birth:</strong> June 28, 2007</p>
                    <p><strong>Address:</strong> Camp, Pune, Maharashtra, India</p>
                    <p><strong>Zip Code:</strong> 411001</p>
                    <p><strong>Email:</strong> matinkazi4545@gmail.com</p>
                    <p><strong>Phone:</strong> 9403121645</p>
                    <p><strong>Project Complete:</strong> 7</p>
                    <br>
                    <a href="resume.html" class="btn download-cv">Download CV</a>
                </div>
            </div>
        </div>
    </section>
</section>

<section>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Matin Kazi - Resume</title>
    <link rel="stylesheet" href="css/style.css">
    <style>
        * { box-sizing: border-box; }
        body { margin: 0; background: #000; font-family: "Times New Roman", Times, serif; color: #f2f2f2; }
        .resume { width: 90%; max-width: 1100px; margin: 35px auto; }
        .resume-header { text-align: center; }
        .name { margin: 0; color: #4f8ac9; font-size: 32px; font-weight: bold; letter-spacing: 0.5px; }
        .resume-contact { margin-top: 7px; font-size: 17px; color: #ccc; }
        .resume-contact a { color: #5b9bd5; text-decoration: underline; }
        .section { margin-top: 25px; }
        .section-title { margin: 0 0 10px; padding-bottom: 5px; border-bottom: 3px solid #4f6680; color: #5b83aa; font-size: 21px; font-weight: bold; letter-spacing: 0.3px; }
        .objective, .experience { font-size: 17px; line-height: 1.45; margin: 0; color: #e6e6e6; }
        .education-item { margin: 0 12px 19px; }
        .education-top { display: flex; justify-content: space-between; align-items: baseline; }
        .degree { font-size: 18px; font-weight: bold; color: #eee; }
        .date { font-size: 17px; font-style: italic; color: #bbb; }
        .college { margin-top: 2px; font-size: 17px; font-style: italic; color: #aaa; }
        .details { margin-top: 4px; font-size: 17px; color: #ddd; }
        .resume ul { margin-top: 5px; padding-left: 37px; }
        .resume li { font-size: 17px; margin-bottom: 7px; padding-left: 3px; color: #ddd; }
        @media print {
            body { background: #000; color: white; }
            .resume { width: 100%; max-width: none; margin: 0; }
            @page { size: A4; margin: 18mm 15mm; }
        }
    </style>
    <header>
        <nav class="navbar">
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="resume.html">Resume</a></li>
                <li><a href="skills.html">Skills</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <div class="resume">
        <header class="resume-header">
            <h1 class="name">MATIN SALIM KAZI</h1>
            <div class="resume-contact">matinkazi4545@gmail.com &nbsp;|&nbsp; +91 9403121645 &nbsp;|&nbsp; <a href="#">LinkedIn</a> &nbsp;|&nbsp; <a href="#">GitHub</a></div>
        </header>

        <section class="section">
            <h2 class="section-title">CAREER OBJECTIVE</h2>
            <p class="objective">Motivated Computer Applications student seeking an entry-level opportunity to apply my programming and data analysis skills, contribute to organizational growth, and continue building my technical expertise.</p>
        </section>

        <section class="section">
            <h2 class="section-title">ACADEMIC QUALIFICATION</h2>
            <div class="education-item">
                <div class="education-top"><div class="degree">Bachelor of Computer Applications (BCA)</div><div class="date">2024 - 2027 <b>(Pursuing)</b></div></div>
                <div class="college">Socmacs / Dr. PA Inamdar University, Pune</div>
                <div class="details">Currently in 3rd Year | CGPA: 8.0 (through 4th Semester)</div>
            </div>
            <div class="education-item">
                <div class="education-top"><div class="degree">12th Standard</div><div class="date">Percentage: 67.17%</div></div>
                <div class="college">Shri Krishna Vidyalaya, Gunjoti</div>
            </div>
            <div class="education-item">
                <div class="education-top"><div class="degree">10th Standard</div><div class="date">Percentage: 84.80%</div></div>
                <div class="college">Urdu Primary School, Gunjoti</div>
            </div>
        </section>

        <section class="section">
            <h2 class="section-title">CERTIFICATIONS</h2>
            <ul>
                <li>Data Analyst Course - Code With Harry (Online), 2026</li>
                <li>Database Management Systems (DBMS) - Great Learning (Online)</li>
            </ul>
        </section>

        <section class="section">
            <h2 class="section-title">TECHNICAL SKILLS</h2>
            <ul>
                <li>Programming Languages: C, C++, Python, HTML, CSS</li>
                <li>Database: SQL</li>
                <li>Tools: MS Excel, Power BI</li>
                <li>Core Competency: Data Analysis &amp; Visualization</li>
            </ul>
        </section>

        <section class="section">
            <h2 class="section-title">WORK EXPERIENCE</h2>
            <p class="experience">Fresher - No prior professional work experience. Eager to apply academic knowledge and technical skills in a real-world role.</p>
        </section>
    </div>
</section>

<section>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Matin Kazi - Skills</title>
    <link rel="stylesheet" href="css/style.css">
    <header>
        <nav class="navbar">
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="resume.html">Resume</a></li>
                <li><a href="skills.html">Skills</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="skills">
        <div class="container">
            <h2>My Skills</h2>
            <div class="skills-grid">
                <div class="skill"><span>Python</span><div class="progress"><div class="progress-bar" style="width: 70%;"></div></div></div>
                <div class="skill"><span>SQL</span><div class="progress"><div class="progress-bar" style="width: 85%;"></div></div></div>
                <div class="skill"><span>Power BI</span><div class="progress"><div class="progress-bar" style="width: 80%;"></div></div></div>
                <div class="skill"><span>Excel</span><div class="progress"><div class="progress-bar" style="width: 80%;"></div></div></div>
                <div class="skill"><span>HTML5</span><div class="progress"><div class="progress-bar" style="width: 95%;"></div></div></div>
                <div class="skill"><span>CSS3</span><div class="progress"><div class="progress-bar" style="width: 90%;"></div></div></div>
                <div class="skill"><span>JavaScript</span><div class="progress"><div class="progress-bar" style="width: 80%;"></div></div></div>
                <div class="skill"><span>PHP</span><div class="progress"><div class="progress-bar" style="width: 90%;"></div></div></div>
            </div>
        </div>
    </section>
</section>


<section>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Matin Kazi - Contact</title>
    <link rel="stylesheet" href="css/style.css">
    <nav class="navbar">
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="resume.html">Resume</a></li>
            <li><a href="skills.html">Skills</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>

    <main class="contact-page">
        <h1>Contact Me</h1>
        <p class="contact-intro">Have a project or opportunity in mind? Get in touch with me.</p>

        <div class="contact-content">
            <section class="contact-details">
                <h2>My Details</h2>
                <div class="contact-item"><h3>Name</h3><p>Matin Salim Kazi</p></div>
                <div class="contact-item"><h3>Email</h3><p><a href="mailto:matinkazi4545@gmail.com">matinkazi4545@gmail.com</a></p></div>
                <div class="contact-item"><h3>Phone</h3><p><a href="tel:+919403121645">+91 9403121645</a></p></div>
                <div class="contact-item"><h3>Address</h3><p>Camp, Pune, Maharashtra<br>411001, India</p></div>
            </section>

            <section class="contact-form-section">
                <h2>Send a Message</h2>
                <form class="contact-form" action="mailto:matinkazi4545@gmail.com" method="post" enctype="text/plain">
                    <label for="name">Your Name</label>
                    <input type="text" id="name" name="name" placeholder="Enter your name" required>
                    <label for="email">Your Email</label>
                    <input type="email" id="email" name="email" placeholder="Enter your email" required>
                    <label for="message">Your Message</label>
                    <textarea id="message" name="message" rows="6" placeholder="Write your message" required></textarea>
                    <button type="submit" class="contact-submit">Send Message</button>
                </form>
            </section>
        </div>
    </main>
</section>

</body>
</html>

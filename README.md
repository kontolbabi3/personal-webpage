<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Muhajirin's Personal Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #77aaff 3px solid;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            display: inline;
            padding: 0 20px 0 20px;
        }
        header #branding {
            float: left;
        }
        header #branding h1 {
            margin: 0;
        }
        header nav {
            float: right;
            margin-top: 10px;
        }
        section#showcase {
            min-height: 400px;
            background: url('showcase.jpg') no-repeat 0 -400px;
            text-align: center;
            color: #fff;
        }
        section#showcase h1 {
            margin-top: 100px;
            font-size: 55px;
            margin-bottom: 10px;
        }
        section#showcase p {
            font-size: 20px;
        }
        .section-a {
            padding: 20px 0;
            background: #e4e4e4;
        }
        .section-b {
            padding: 20px 0;
            background: #fff;
        }
        .box {
            float: left;
            width: 30%;
            padding: 10px;
            text-align: center;
        }
        .box img {
            width: 90%;
        }
        footer {
            padding: 20px;
            margin-top: 20px;
            color: #fff;
            background-color: #333;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1>Muhajirin</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#about">About Me</a></li>
                    <li><a href="#experience">Experience</a></li>
                    <li><a href="#education">Education</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="showcase">
        <div class="container">
            <h1>Welcome to My Personal Webpage</h1>
            <p>Your one-stop destination to know more about me and my work.</p>
        </div>
    </section>

    <section id="about" class="section-a">
        <div class="container">
            <h2>About Me</h2>
            <p>I am currently pursuing an MSc in Data Science at the University of Birmingham, with anticipated completion in mid-September 2024. My academic journey is complemented by a comprehensive MSc Data Science Project focused on the "Development of Auto Trading Bots," scheduled for deployment in late August and submission by 2nd September 2024. Post-graduation, I plan to return to Indonesia in October 2024 to leverage my skills and knowledge in the dynamic field of data science.</p>
        </div>
    </section>

    <section id="experience" class="section-b">
        <div class="container">
            <h2>Work Experience</h2>
            <h3>Bimbel Khalifah, Banda Aceh</h3>
            <p>Mathematics, Physics, and GRE Teacher (Feb 2018 - Aug 2023)</p>
            <ul>
                <li>Teach high school students</li>
                <li>Consult students needing extra help</li>
                <li>Organize weekly mathematics teacher meetings</li>
                <li>Type mathematics question booklets</li>
                <li>Substitute absent teachers</li>
            </ul>
            <h3>Bimbel Madaz, Banda Aceh</h3>
            <p>Mathematics and Physics Teacher (Aug 2016 - Jan 2018)</p>
            <ul>
                <li>Teach high school students</li>
                <li>Consult students needing extra help</li>
                <li>Type mathematics question booklets</li>
                <li>Substitute absent teachers</li>
            </ul>
        </div>
    </section>

    <section id="education" class="section-a">
        <div class="container">
            <h2>Education</h2>
            <p><strong>University of Birmingham</strong><br>
            Master of Data Science (Sep 2023 - Sep 2024)</p>
            <p><strong>Universitas Syiah Kuala</strong><br>
            Bachelor of Physics (Sep 2016 - May 2020)</p>
        </div>
    </section>

    <section id="contact" class="section-b">
        <div class="container">
            <h2>Contact</h2>
            <p>Email: <a href="mailto:muhajirin.msc@gmail.com">muhajirin.msc@gmail.com</a></p>
            <p>Phone: +62 85261722944</p>
            <p>Address: 10 Dale Road, Selly Oak, B29 6AG, Birmingham, United Kingdom</p>
        </div>
    </section>

    <footer>
        <p>Muhajirin &copy; 2024</p>
    </footer>
</body>
</html>

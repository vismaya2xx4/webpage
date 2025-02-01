<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vismaya's Portfolio</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to right, #0f2027, #203a43, #2c5364);
            text-align: center;
            color: #fff;
        }
        header {
            background: rgba(0, 0, 0, 0.9);
            padding: 20px;
            font-size: 28px;
            text-transform: uppercase;
            font-weight: bold;
        }
        section {
            padding: 30px;
        }
        .content-box {
            background: rgba(255, 255, 255, 0.9);
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
            margin: 30px auto;
            width: 80%;
            text-align: left;
            line-height: 1.8;
            color: #333;
        }
        .about-container {
            display: flex;
            align-items: center;
            justify-content: center;
            flex-wrap: wrap;
        }
        .about-text {
            max-width: 500px;
            margin-left: 20px;
        }
        img {
            width: 100%;
            max-width: 400px;
            border-radius: 15px;
            margin-top: 15px;
        }
        a {
            color: #ffcc00;
            text-decoration: none;
            font-weight: bold;
        }
        a:hover {
            text-decoration: underline;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        table, th, td {
            border: 1px solid #555;
        }
        th, td {
            padding: 12px;
            text-align: center;
            background: rgba(255, 255, 255, 0.8);
        }
        ul, ol {
            margin: 20px;
            text-align: left;
        }
        form {
            margin-top: 20px;
        }
        input, textarea, button {
            width: 100%;
            padding: 12px;
            margin-top: 12px;
            border: none;
            border-radius: 5px;
        }
        button {
            background: #ffcc00;
            color: black;
            font-size: 16px;
            cursor: pointer;
        }
        button:hover {
            background: #ff9900;
        }
        canvas {
            border: 2px solid black;
            margin-top: 20px;
        }
        video, audio {
            margin-top: 20px;
        }
        footer {
            background: rgba(0, 0, 0, 0.9);
            padding: 15px;
            font-size: 14px;
            width: 100%;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        Vismaya Vinod | Cybersecurity & Development Enthusiast
    </header>
    <section>
        <div class="content-box">
            <h2>Welcome to My Portfolio</h2>
            <p>Passionate about cybersecurity, programming, and innovation.</p>
            <div class="about-container">
                <img src="image/vismaya.jpg" alt="Vismaya's Image">
                <div class="about-text">
                    <h3>About Me</h3>
                    <p>
                        I am a dedicated BTech student at VIT University, Bhopal, specializing in Cyber Security and Digital Forensics.
                        With a passion for computer programming and cyber security, I excel in communication and teamwork, thriving in collaborative environments. 
                        My goal is to leverage my technical skills and academic knowledge to contribute to the field of Cybersecurity and digital forensics.
                        Currently, I am broadening my skill set by learning new courses and am eager to connect with professionals and peers to further explore the engineering community's possibilities.
                    </p>
                    <a href="https://www.linkedin.com/in/vismaya-vinod-nair-20a01a252/" target="_blank">Visit my LinkedIn</a>
                </div>
            </div>
            <h3>Skills</h3>
            <table>
                <tr>
                    <th>Technology</th>
                    <th>Proficiency</th>
                </tr>
                <tr>
                    <td>Python & Java</td>
                    <td>Advanced</td>
                </tr>
                <tr>
                    <td>Web Development</td>
                    <td>Intermediate</td>
                </tr>
                <tr>
                    <td>Cybersecurity</td>
                    <td>Expert</td>
                </tr>
            </table>
            <h3>Projects</h3>
            <ul>
                <li>App Development [CYPICS]</li>
                <li> Coverless Steganography</li>
            </ul>
            <h3>Certifications</h3>
            <ul>
                <li>AI Essentials (Google)</li>
                <li>Cybersecurity Specialization (Google)</li>
                <li>Introduction to Cybersecurity (Cisco)</li>
                <li>Ethical Hacking Essentials (EC-Council)</li>
                <li>OOPs Concepts in C++ (Great Learning)</li>
            </ul>
            <h3>Work Experience</h3>
            <div class="content-box">
                <h4>Cybersecurity Intern</h4>
                <p><strong>Company:</strong> Arada Developments, Dubai<br>
                <strong>Role:</strong> Cybersecurity Intern<br>
                <strong>Responsibilities:</strong> Conducting vulnerability assessments, implementing security measures, and assisting in developing cybersecurity policies.</p>
          <h4>Creative Team Core Member</h4>
                <p><strong>Organization:</strong> Mozilla Firefox Club, VIT Bhopal<br>
                <strong>Role:</strong> Creative Team Core Member<br>
                <strong>Responsibilities:</strong> Contributing to creative aspects of club events, including design and content creation for promotional materials.</p>
                <h4>Media & Marketing Team Co-Lead</h4>
                <p><strong>Organization:</strong> Cyber Warriors, VIT Bhopal<br>
                <strong>Role:</strong> Media & Marketing Team Co-Lead<br>
                <strong>Responsibilities:</strong> Leading the media and marketing efforts for club events, managing social media presence, and creating promotional content.</p>
            </div>
            <h3>Contact Me</h3>
            <form>
                <input type="text" placeholder="Your Name" required>
                <textarea placeholder="Your Message" required></textarea>
                <button type="submit">Submit</button>
            </form>
            <h3>Media</h3>
            <video controls width="300">
                <source src="media/dubai.mp4" type="video/mp4">
                Your browser does not support video.
            </video>
        </div>
    </section>
    <footer>
        &copy; 2024 Vismaya Vinod | All Rights Reserved
    </footer>
</body>
</html>

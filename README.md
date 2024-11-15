<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <style>
        body {
            font-family: 'Montserrat', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            max-width: 1200px;
            margin: 30px auto;
            padding: 20px;
            background: #fff;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
        }
        .header {
            text-align: center;
        }
        .header h1 {
            font-size: 48px;
            margin: 10px 0;
            color: #333;
        }
        .header h2 {
            font-size: 24px;
            color: #777;
        }
        section {
            margin: 40px 0;
        }
        section h2 {
            font-size: 32px;
            margin-bottom: 15px;
            color: #555;
        }
        p {
            line-height: 1.6;
            font-size: 18px;
        }
        .contact-info, .skills, .languages {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .contact-item, .skill-item, .language-item {
            width: calc(33.33% - 20px);
            font-size: 16px;
            background: #f8f8f8;
            padding: 10px;
            border-radius: 5px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .projects {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
        }
        .project-card {
            padding: 20px;
            background: #f8f8f8;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            margin-top: 40px;
            font-size: 14px;
            color: #999;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header -->
        <div class="header">
            <h1>Clarissa</h1>
            <h2>Welcome to My Portfolio</h2>
        </div>

        <!-- About Me -->
        <section>
            <h2>About Me</h2>
            <p>
                Hello! I’m Clarissa, a designer who loves mixing style and creativity. 
                My work is inspired by what I see and hear around me. 
                I believe art can be found in everything, and I enjoy combining different types of art to make something new and exciting. 
                Every project I work on is a chance to try something creative and fresh. Let’s work together to make something special!
            </p>
        </section>

        <!-- Contact Me -->
        <section>
            <h2>Contact Me</h2>
            <div class="contact-info">
                <div class="contact-item">📍 Indonesian</div>
                <div class="contact-item">📅 October 5th, 2005</div>
                <div class="contact-item">📞 +62 811-6530-515</div>
                <div class="contact-item">📧 clarissa0510@gmail.com</div>
                <div class="contact-item">📸 clarissa_lrz.s</div>
            </div>
        </section>

        <!-- Experience -->
        <section>
            <h2>Experience</h2>
            <p><strong>2024-Present:</strong> Freelance</p>
            <p><strong>June 24 - August 24:</strong> Brighton Card (Graphic Designer)</p>
        </section>

        <!-- Education -->
        <section>
            <h2>Education</h2>
            <p><strong>2023-Present:</strong> Universitas Prima Indonesia - Visual Communication Design</p>
            <p><strong>2021-2023:</strong> SMA Sutomo 1 - Science</p>
        </section>

        <!-- Skills -->
        <section>
            <h2>Skills</h2>
            <div class="skills">
                <div class="skill-item">Adobe Illustrator (Ai)</div>
                <div class="skill-item">Adobe Photoshop (Ps)</div>
            </div>
        </section>

        <!-- Languages -->
        <section>
            <h2>Languages</h2>
            <div class="languages">
                <div class="language-item">Indonesian (Fluent)</div>
                <div class="language-item">English (Intermediate)</div>
                <div class="language-item">Mandarin (Basic)</div>
            </div>
        </section>

        <!-- Projects -->
        <section>
            <h2>Projects</h2>
            <div>
                <!-- Chate -->
                <h3>Chate</h3>
                <img src="Asset 4.png"
                 height="400" width="500">
                <div class="project-card">
                    
                    <p>
                        Chate is a brand dedicated to offering a premium experience of authentic matcha. 
                        With a focus on tradition and quality, we present a wide range of classic and unique matcha flavor combinations, 
                        blending tradition with innovation. Whether you're a matcha lover or a newcomer, Chate delivers a refined experience rooted in heritage and taste.
                    </p>
                </div>
                <!-- Neibo -->
                <h3>Neibo</h3>
                 <img src="Asset 5.png"
                 height="400" width="500">
                <div class="project-card">
                    
                    <p>
                        Neibo is a café-restaurant brand inspired by my passion for playing guitar and the iconic sounds of my favorite indie rock bands, 
                        The Neighbourhood and Arctic Monkeys. With a dark, rock 'n' roll theme, Neibo captures the electric guitar vibe that defines 
                        these bands and creates a unique, immersive experience.
                    </p>
                </div>
            </div>
        </section>
    </div>

    <footer>
        &copy; 2024 Clarissa. All rights reserved.
    </footer>
</body>
</html>

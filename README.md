<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Piano Tutoring</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
        }
        header {
            position: relative;
            height: 400px;
            background: url('https://images.unsplash.com/photo-1511376777868-611b54f68947?fit=crop&w=1500&q=80') no-repeat center center/cover;
            color: #fff;
            text-align: center;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }
        header h1 {
            font-size: 3em;
            margin: 0;
            text-shadow: 2px 2px 5px #000;
        }
        header p {
            font-size: 1.5em;
            text-shadow: 1px 1px 3px #000;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #6A0DAD;
        }
        nav a {
            color: white;
            padding: 15px 20px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            background-color: #4B0082;
        }
        section {
            padding: 40px 20px;
            max-width: 1000px;
            margin: auto;
        }
        h1, h2 {
            text-align: center;
        }
        .services {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .service {
            background: #f4f4f4;
            margin: 10px;
            padding: 20px;
            flex: 1 1 250px;
            border-radius: 10px;
        }
        .testimonials {
            display: flex;
            flex-direction: column;
            gap: 20px;
            text-align: center;
        }
        .testimonial {
            background: #f4f4f4;
            padding: 20px;
            border-radius: 10px;
            font-style: italic;
        }
        form {
            display: flex;
            flex-direction: column;
            max-width: 500px;
            margin: auto;
        }
        form input, form textarea {
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
            font-size: 16px;
        }
        form button {
            background-color: #4B0082;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }
        form button:hover {
            background-color: #6A0DAD;
        }
        footer {
            background: #4B0082;
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
        }
        iframe {
            width: 100%;
            height: 300px;
            border: none;
            border-radius: 10px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to Your Piano Tutoring</h1>
        <p>Learn Piano with Fun and Professional Guidance</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#lessons">Lessons</a>
        <a href="#testimonials">Testimonials</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="home">
        <h2>Start Your Musical Journey Today!</h2>
        <p>Whether you're a beginner or advanced, I offer personalized piano lessons to help you reach your goals.</p>
    </section>

    <section id="about">
        <h2>About Me</h2>
        <p>Hi! I'm vivaan, a ten year old kid. My teaching style is friendly, patient, and tailored to each student.</p>
    </section>

    <section id="lessons">
        <h2>Lessons & Services</h2>
        <div class="services">
            <div class="service">
                <h3>Beginner Lessons</h3>
                <p>Learn the basics of piano, reading music, and simple songs.</p>
            </div>
            <div class="service">
                <h3>Advanced Lessons</h3>
                <p>For experienced players looking to improve technique and repertoire.</p>
            </div>
            <div class="service">
                <h3>Online Lessons</h3>
                <p>Learn from anywhere via Zoom or Skype with interactive guidance.</p>
            </div>
        </div>
    </section>

    <section id="testimonials">
        <h2>What My Students Say</h2>
        <div class="testimonials">
            <div class="testimonial">"I improved so much thanks to vivaan! Lessons are fun and engaging." – Student A</div>
            <div class="testimonial">"My child loves every lesson and has grown in confidence and skill." – Parent B</div>
            <div class="testimonial">"Highly recommend for anyone wanting to learn piano seriously or just for fun!" – Student C</div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea rows="5" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
        <h3 style="text-align:center; margin-top:40px;">Visit Me</h3>
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3153.0869032358426!2d-122.41941548468142!3d37.77492977975954!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8085809c1d1d7b2b%3A0x0!2zMzfCsDQ2JzI5LjgiTiAxMjLCsDI1JzA2LjkiVw!5e0!3m2!1sen!2sus!4v1600000000000!5m2!1sen!2sus" allowfullscreen="" loading="lazy"></iframe>
    </section>

    <footer>
        <p>&copy; 2025 Your Piano Tutoring | All Rights Reserved</p>
    </footer>

</body>
</html>

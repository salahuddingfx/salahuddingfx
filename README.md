<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        section {
            padding: 20px;
            margin: 20px 0;
            background: #fff;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: relative;
        }
        .social-icons a {
            margin: 0 10px;
            color: #fff;
            text-decoration: none;
        }
        .skills-chart {
            display: flex;
            flex-direction: column;
        }
        .chart {
            display: flex;
            justify-content: space-between;
            margin: 5px 0;
        }
        .chart span {
            width: 100px;
        }
        .contact input, .contact textarea {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        .contact button {
            padding: 10px;
            background: #28a745;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .contact button:hover {
            background: #218838;
        }
    </style>
</head>
<body>

<header>
    <h1>My Portfolio</h1>
    <p>I'm a freelancer, a passionate digital marketeer, a designer, a creator, acreative lover</p>
</header>

<section class="about">
    <h2>About Me</h2>
    <p>Your personal description goes here. Share your journey, experiences, and what you love to do.</p>
</section>

<section class="skills">
    <h2>My Skills</h2>
    <div class="skills-chart">
        <div class="chart"><span>Digital Marketing</span><span>90%</span></div>
        <div class="chart"><span>Web Design</span><span>85%</span></div>
        <div class="chart"><span>Graphic Design</span><span>80%</span></div>
        <!-- Add more skills as needed -->
    </div>
</section>

<section class="projects">
    <h2>My Projects</h2>
    <p>List of projects or showcase your work here.</p>
</section>

<section class="packages">
    <h2>Packages</h2>
    <p>Detail your service packages with prices and descriptions.</p>
</section>

<section class="stats">
    <h2>Statistics</h2>
    <p>Details about your submitted work, happy clients, etc.</p>
</section>

<section class="contact">
    <h2>Contact Me</h2>
    <form id="contact-form">
        <label for="client-name">Name:</label>
        <input type="text" id="client-name" name="client-name" required>

        <label for="client-email">Email:</label>
        <input type="email" id="client-email" name="client-email" required>

        <label for="client-phone">Phone Number:</label>
        <input type="tel" id="client-phone" name="client-phone" required>

        <label for="client-message">Message:</label>
        <textarea id="client-message" name="client-message" required></textarea>

        <button type="submit">Send Message</button>
    </form>
</section>

<footer>
    <p>&copy; 2024 Your Name. All rights reserved.</p>
    <div class="social-icons">
        <a href="https://facebook.com" class="fa fa-facebook-official" aria-hidden="true"></a>
        <a href="https://twitter.com" class="fa fa-twitter" aria-hidden="true"></a>
        <a href="https://linkedin.com" class="fa fa-linkedin" aria-hidden="true"></a>
        <!-- Add more social icons as needed -->
    </div>
    <section class="contact">
    <h2>Contact Me</h2>
    <form id="contact-form">
        <label for="client-name">Name:</label>
        <input type="text" id="client-name" name="client-name" required>

</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css" />
    <title>Your Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #f4f4f4;
        }
        header {
            background: url('your-3d-background.png') no-repeat center center/cover;
            padding: 60px 20px;
            text-align: center;
            color: #fff;
            position: relative;
        }
        h1 {
            font-size: 3em;
            margin: 0;
        }
        .intro {
            animation: fadeIn 2s ease-in-out;
        }
        section {
            padding: 20px;
            background: #fff;
            margin: 20px auto;
            max-width: 800px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #333;
            color: #fff;
        }
        .social-icons i {
            margin: 0 10px;
            color: #fff;
            font-size: 1.5em;
        }
    </style>
</head>
<body>

<header>
    <div class="intro">
        <h1>Your Name</h1>
        <h2 class="animate__animated animate__fadeInUp">I'm a freelancer, a passionate digital marketeer, designer, creator, and creative lover.</h2>
    </div>
</header>

<section class="about">
    <h2>About Me</h2>
    <p>Your short biography here...</p>
</section>

<section class="skills">
    <h2>Skills</h2>
    <ul>
        <li>Digital Marketing: 90%</li>
        <li>Design: 85%</li>
        <li>Content Creation: 80%</li>
        <!-- আরও স্কিল যুক্ত করুন -->
    </ul>
</section>

<section class="packages">
    <h2>Packages</h2>
    <div>
        <h3>Package 1</h3>
        <p>Details about Package 1...</p>
    </div>
    <div>
        <h3>Package 2</h3>
        <p>Details about Package 2...</p>
    </div>
    <!-- আরও প্যাকেজ যুক্ত করুন -->
</section>

<section class="blog-posts">
    <h2>Recent Blog Posts</h2>
    <div class="blog-post">
        <h3><a href="link_to_your_blogger_post_1" target="_blank">Blog Post Title 1</a></h3>
        <p>Summary of your blog post 1...</p>
    </div>
    <!-- আরও ব্লগ পোস্ট যুক্ত করুন -->
</section>

<section class="stats">
    <h2>Statistics</h2>
    <p>Number of Projects Submitted: XX</p>
    <p>Happy Clients: XX</p>
    <p>Tips/Rewards Received: XX</p>
</section>

<footer>
    <div class="social-icons">
        <a href="https://facebook.com" target="_blank"><i class="fab fa-facebook-official"></i></a>
        <a href="https://twitter.com" target="_blank"><i class="fab fa-twitter"></i></a>
        <a href="https://linkedin.com" target="_blank"><i class="fab fa-linkedin"></i></a>
        <!-- আরও সোশ্যাল লিংক যুক্ত করুন -->
    </div>
    <p>Contact: your.email@example.com | Phone: +1234567890 | Address: Your Address</p>
</footer>

</body>
</html>

<!---
Salahuddin835/Salahuddin835 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

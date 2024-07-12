<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Miniar Dhaoui - Pharmacist</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        nav {
            background-color: #333;
            color: white;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        section {
            padding: 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        table, th, td {
            border: 1px solid black;
        }
        th, td {
            padding: 15px;
            text-align: left;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#work">Work</a>
            <a href="#resume">Resume</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <main>
        <section id="home">
            <h1>Welcome to Miniar Dhaoui's Professional Page</h1>
            <p>Discover my journey and expertise in the pharmaceutical industry.</p>
        </section>

        <section id="about">
            <h2>About Me</h2>
            <p>I am Miniar Dhaoui, a dedicated pharmacist with over a decade of experience in the pharmaceutical industry. My career began in 2012 as a regulatory affairs pharmacist in a local company for one year. Since then, I have been working as a medical representative in a multinational company.</p>
        </section>

        <section id="work">
            <h2>Work Experience</h2>
            <h3>Regulatory Affairs Pharmacist</h3>
            <p>Local Pharmaceutical Company (2012 - 2013)</p>
            <ul>
                <li>Ensured compliance with regulatory requirements.</li>
                <li>Prepared and submitted documentation to health authorities.</li>
                <li>Maintained up-to-date knowledge of industry regulations.</li>
            </ul>

            <h3>Medical Representative</h3>
            <p>Multinational Pharmaceutical Company (2013 - Present)</p>
            <ul>
                <li>Promoted pharmaceutical products to healthcare professionals.</li>
                <li>Provided product information and training.</li>
                <li>Built and maintained strong relationships with clients.</li>
            </ul>
        </section>

        <section id="resume">
            <h2>Resume</h2>
            <table>
                <tr>
                    <th>Position</th>
                    <th>Company</th>
                    <th>Duration</th>
                    <th>Responsibilities</th>
                </tr>
                <tr>
                    <td>Regulatory Affairs Pharmacist</td>
                    <td>Local Pharmaceutical Company</td>
                    <td>2012 - 2013</td>
                    <td>
                        <ul>
                            <li>Compliance with regulatory requirements</li>
                            <li>Documentation preparation and submission</li>
                            <li>Industry regulations knowledge</li>
                        </ul>
                    </td>
                </tr>
                <tr>
                    <td>Medical Representative</td>
                    <td>Multinational Pharmaceutical Company</td>
                    <td>2013 - Present</td>
                    <td>
                        <ul>
                            <li>Product promotion to healthcare professionals</li>
                            <li>Providing product information and training</li>
                            <li>Client relationship management</li>
                        </ul>
                    </td>
                </tr>
            </table>
        </section>

        <section id="contact">
            <h2>Contact Me</h2>
            <p>Email: <a href="mailto:miniar.dhaoui@example.com">miniar.dhaoui@example.com</a></p>
            <p>Phone: +1-234-567-8900</p>
            <form>
                <label for="name">Name:</label><br>
                <input type="text" id="name" name="name" required><br><br>
                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email" required><br><br>
                <label for="message">Message:</label><br>
                <textarea id="message" name="message" rows="4" required></textarea><br><br>
                <input type="submit" value="Submit">
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Miniar Dhaoui</p>
    </footer>
</body>
</html>

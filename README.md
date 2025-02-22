<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohamed Metwally - Resume</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;700&display=swap');
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #000;
            color: #fff;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }
        .header h1 {
            font-size: 3rem;
            font-weight: 700;
            letter-spacing: 3px;
            text-transform: uppercase;
            animation: fadeIn 1.5s ease-in-out;
        }
        .header p {
            font-size: 1.2rem;
            font-weight: 300;
            animation: fadeIn 2s ease-in-out;
        }
        .contact-buttons {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin: 20px 0;
        }
        .contact-buttons a {
            text-decoration: none;
            background: #fff;
            color: #000;
            padding: 10px 20px;
            border-radius: 5px;
            font-weight: 600;
            transition: all 0.3s ease;
        }
        .contact-buttons a:hover {
            background: gray;
        }
        .content-section {
            margin-top: 30px;
            text-align: left;
        }
        h2 {
            font-size: 1.8rem;
            font-weight: 700;
            letter-spacing: 2px;
            border-bottom: 2px solid #fff;
            display: inline-block;
            padding-bottom: 5px;
            animation: slideIn 1s ease-in-out;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        ul li {
            font-size: 1.1rem;
            padding: 5px 0;
            animation: fadeInUp 1s ease-in-out;
        }
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 10px;
            padding: 10px;
        }
        .skills-grid div {
            background: #333;
            padding: 10px;
            border-radius: 5px;
            font-weight: 500;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        @keyframes slideIn {
            from { opacity: 0; transform: translateX(-20px); }
            to { opacity: 1; transform: translateX(0); }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Mohamed Metwally</h1>
            <p>Accounting & Banking Professional | Data Analyst</p>
        </div>

        <div class="contact-buttons">
            <a href="mailto:MohamedMetwally.Mohamed@outlook.com">Email Me</a>
            <a href="https://www.linkedin.com/in/mohamed-metwally-0182bb2b5" target="_blank">LinkedIn</a>
            <a href="https://drive.google.com/file/d/1Y4qxrVXAtwa3cMK6DzV_OQDm8rBhGJpl/view" target="_blank">Download CV</a>
            <a href="tel:+201002347613">Call Me</a>
        </div>

        <div class="content-section" id="summary">
            <h2>A B O U T &nbsp; M E</h2>
            <p>A highly motivated and detail-oriented accounting graduate with strong expertise in financial analysis, banking, and data analysis...</p>
        </div>

        <div class="content-section" id="education">
            <h2>E D U C A T I O N</h2>
            <p>Bachelor's Degree in Accounting - Faculty of Commerce, Benha University (Expected 2025) - GPA: Very Good</p>
        </div>

        <div class="content-section" id="courses">
            <h2>C O U R S E S &nbsp; & &nbsp; C E R T I F I C A T I O N S</h2>
            <ul>
                <li>AI Career Essentials - ALX</li>
                <li>AWS Cloud Economics for Startups - AWS</li>
                <li>Financial Services - AWS</li>
                <li>Liquidity Management - Open University</li>
            </ul>
        </div>

        <div class="content-section" id="achievements">
            <h2>A C H I E V E M E N T S</h2>
            <ul>
                <li>Ideal Student Award: Faculty of Commerce, Benha University (2024-2025)</li>
                <li>First Place in Scientific Research (2025)</li>
                <li>CMA Scholarship Recipient</li>
                <li>President of the University Dormitory Student Union</li>
            </ul>
        </div>

        <div class="content-section" id="skills">
            <h2>S K I L L S</h2>
            <div class="skills-grid">
                <div>✔ Financial Analysis & Accounting</div>
                <div>✔ Data Analysis & SQL</div>
                <div>✔ Excel & QuickBooks</div>
                <div>✔ Banking & Liquidity Management</div>
                <div>✔ Leadership & Team Management</div>
                <div>✔ Multilingual: Arabic, English, French</div>
            </div>
        </div>

        <footer>
            <p>&copy; 2025 Mohamed Metwally. All Rights Reserved.</p>
        </footer>
    </div>
</body>
</html>

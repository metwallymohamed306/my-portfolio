<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohamed Metwally - Resume</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background-color: #ffffff;
            color: #000000;
            line-height: 1.6;
            text-align: center;
        }

        body[lang="ar"] {
            direction: rtl;
        }

        header {
            background-color: #ffffff;
            padding: 20px 0;
            text-align: center;
            position: relative;
            border-bottom: 2px solid #000000;
        }

        header h1 {
            font-size: 3rem;
            font-weight: bold;
            color: #000000;
            letter-spacing: 2px;
            margin-bottom: 5px;
            text-transform: uppercase;
            animation: fadeIn 1.5s ease-in-out;
        }

        header h2 {
            font-size: 1.5rem;
            color: #000000;
            margin-bottom: 15px;
            font-weight: normal;
            animation: fadeIn 1.5s ease-in-out;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        .social-media {
            position: absolute;
            top: 20px;
            right: 20px;
            display: flex;
            gap: 15px;
            font-size: 1.3rem;
            color: #000000;
            text-transform: uppercase;
        }

        .social-media a {
            color: #000000;
            text-decoration: none;
            transition: color 0.3s ease;
        }

        .social-media a:hover {
            color: #FF6347;
        }

        .container {
            max-width: 900px;
            margin: 40px auto;
            padding: 20px;
        }

        .btn-primary {
            background-color: #000000;
            color: #ffffff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            text-decoration: none;
            font-size: 1.1rem;
            transition: background-color 0.3s ease;
        }

        .btn-primary:hover {
            background-color: #FF6347;
        }

        footer {
            background-color: #ffffff;
            color: #000000;
            padding: 15px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
            border-top: 2px solid #000000;
        }

        footer p {
            font-size: 1rem;
        }

        .content-section {
            padding: 40px 0;
            background-color: #ffffff;
            color: #000000;
            margin-top: 30px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            animation: fadeIn 1.5s ease-in-out;
        }

        .content-section h2 {
            font-size: 2rem;
            color: #000000;
            margin-bottom: 20px;
            text-align: left;
            font-weight: bold;
        }

        .content-section p, .content-section ul {
            font-size: 1rem;
            margin-bottom: 15px;
            text-align: left;
        }

        .content-section ul {
            list-style-type: none;
        }

        .content-section ul li {
            margin-bottom: 10px;
        }

        .nav-links {
            margin-top: 20px;
            text-align: center;
        }

        .nav-links a {
            font-size: 1.2rem;
            color: #000000;
            margin: 0 20px;
            text-decoration: none;
        }

        .nav-links a:hover {
            text-decoration: underline;
        }

    </style>
</head>
<body lang="en">

    <!-- Header Section -->
    <header>
        <h1>Mohamed Metwally</h1>
        <h2>Accountant | Financial Analyst | Data Analyst</h2>

        <!-- Social Media Links -->
        <div class="social-media">
            <a href="https://www.linkedin.com/in/mohamed-metwally-0182bb2b5" target="_blank" title="LinkedIn">LinkedIn</a>
            <a href="mailto:MohamedMetwally.Mohamed@outlook.com" title="Email">Email</a>
            <a href="tel:+01002347613" title="Phone">Phone</a>
        </div>
    </header>

    <!-- Navigation Links -->
    <div class="nav-links">
        <a href="#about">About Me</a>
        <a href="#education">Education</a>
        <a href="#certifications">Certifications</a>
        <a href="#skills">Skills</a>
        <a href="#experience">Work Experience</a>
        <a href="#achievements">Achievements</a>
    </div>

    <!-- About Me Section -->
    <div id="about" class="content-section">
        <h2>About Me</h2>
        <p>Hello! I am Mohamed Metwally, an aspiring accountant, financial analyst, and data analyst with a passion for technology, financial management, and data analysis. I have a diverse background, with experience in both the private and public sectors, and have honed my skills in various industries.</p>
        <p>Currently, I am pursuing my Bachelor’s degree in Accounting at Benha University, and I am actively involved in projects and certifications in financial management, accounting, and data analysis.</p>
        <p>I aim to apply my skills to the banking and financial sectors to improve processes, enhance customer experiences, and contribute to organizational success. I believe in continuous learning and strive to stay at the forefront of industry trends and technology advancements.</p>
    </div>

    <!-- Education Section -->
    <div id="education" class="content-section">
        <h2>Education</h2>
        <p><strong>Bachelor’s Degree in Accounting</strong> – Faculty of Commerce, Benha University (Expected Graduation: 2025) – GPA: Very Good</p>
    </div>

    <!-- Certifications Section -->
    <div id="certifications" class="content-section">
        <h2>Certifications</h2>
        <ul>
            <li><strong>Diploma in Accounting and Finance</strong> – Oxford Home Study College (January 2025 – March 2025)</li>
            <li><strong>Diploma in Effective Bookkeeping and Payroll</strong> – Alison (January 2025 – March 2025)</li>
            <li><strong>AI Career Essentials</strong> – ALX (December 2024 – February 2025)</li>
            <li><strong>AWS Cloud Economics for Startups</strong> – Amazon Web Services (AWS) (November 2024 – January 2025)</li>
            <li><strong>Financial Services</strong> – Amazon Web Services (AWS) (October 2024 – December 2024)</li>
            <li><strong>Services Analyst</strong> – Amazon Web Services (AWS) (September 2024 – November 2024)</li>
            <li><strong>Getting Started with Amazon</strong> – Amazon Web Services (AWS) (August 2024 – October 2024)</li>
            <li><strong>Skills for Communication</strong> – IBM (July 2024 – September 2024)</li>
            <li><strong>Liquidity Management</strong> – The Open University (June 2024 – August 2024)</li>
            <li><strong>Data Literacy Certificate</strong> – SAS (May 2024 – July 2024)</li>
            <li><strong>Financial Accounting Management and Reporting</strong> – UNICEF (April 2024 – June 2024)</li>
            <li><strong>Diploma in Financial Management</strong> – American Board of Professional Studies (March 2024 – May 2024)</li>
        </ul>
    </div>

    <!-- Skills Section -->
    <div id="skills" class="content-section">
        <h2>Skills</h2>
        <ul>
            <li><strong>Data Analysis</strong> – Proficient in SQL, Python, Excel, QuickBooks, SAP</li>
            <li><strong>Financial Analysis</strong> – Budgeting, Forecasting, Cash Flow Management</li>
            <li><strong>Accounting</strong> – Financial Reporting, Auditing, Taxation, Payroll</li>
            <li><strong>Communication</strong> – Strong interpersonal and communication skills</li>
            <li><strong>Language Skills</strong> – Arabic (Native), English (Fluent), French (Intermediate)</li>
        </ul>
    </div>

    <!-- Work Experience Section -->
    <div id="experience" class="content-section">
        <h2>Work Experience</h2>
        <p><strong>Accountant</strong> – Business Comeback Company (July 2022 – August 2023)</p>
        <p><strong>Financial Analyst Intern</strong> – Bank of CIB, Zagazig Branch (August 2024 – September 2024)</p>
    </div>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2025 Mohamed Metwally | All Rights Reserved</p>
    </footer>

</body>
</html>




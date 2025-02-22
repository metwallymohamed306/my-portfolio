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
            line-height: 1.6;
            background-color: #000000;
            color: #ffffff;
            text-align: center;
            background-image: url('https://upload.wikimedia.org/wikipedia/commons/5/52/Benha_University_logo.png');
            background-repeat: no-repeat;
            background-position: center;
            background-attachment: fixed;
            background-size: 15%;
            opacity: 0.1;
        }

        body[lang="ar"] {
            direction: rtl;
        }

        header {
            background-color: #000000;
            color: #ffffff;
            padding: 40px 0;
            text-align: center;
            position: relative;
        }

        header h1, header h2 {
            font-size: 3rem;
            margin-bottom: 10px;
            letter-spacing: 2px;
        }

        header h2 {
            color: #ffffff;
        }

        .typing-effect {
            font-size: 2.5rem;
            font-weight: bold;
            color: #ffffff;
            display: inline-block;
            border-right: 3px solid;
            padding-right: 5px;
            animation: typing 3s steps(40) 1s forwards, blink 0.75s step-end infinite;
        }

        @keyframes typing {
            from { width: 0; }
            to { width: 100%; }
        }

        @keyframes blink {
            50% { border-color: transparent; }
        }

        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-top: 20px;
            border: 5px solid #ffffff;
            object-fit: cover;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }

        .btn-primary {
            background-color: #ffffff;
            color: #000000;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            text-decoration: none;
        }

        .btn-primary:hover {
            background-color: #000000;
            color: #ffffff;
        }

        footer {
            background-color: #000000;
            color: #ffffff;
            padding: 15px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        footer p {
            font-size: 1rem;
        }

        .nav-links {
            margin: 30px 0;
        }

        .nav-links a {
            font-size: 1.2rem;
            color: #ffffff;
            margin: 0 15px;
            text-decoration: none;
        }

        .nav-links a:hover {
            text-decoration: underline;
        }

        .content-section {
            padding: 50px 0;
            background-color: #ffffff;
            color: #000000;
            margin-top: 30px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }

        .content-section h2 {
            font-size: 2rem;
            color: #000000;
            margin-bottom: 20px;
        }

        .content-section p {
            font-size: 1.1rem;
            margin-bottom: 15px;
        }

        .content-section ul {
            list-style-type: none;
            font-size: 1rem;
            text-align: left;
            margin-top: 15px;
        }

        .content-section ul li {
            margin-bottom: 10px;
        }

        .nav-links a:active {
            color: #FF6347;
        }

        /* Social Media Links */
        .social-media {
            position: absolute;
            top: 20px;
            right: 20px;
            display: flex;
            gap: 15px;
        }

        .social-media a {
            color: #ffffff;
            font-size: 1.5rem;
            text-decoration: none;
        }

        .social-media a:hover {
            color: #FF6347;
        }

    </style>
</head>
<body lang="en">

    <!-- Social Media Links -->
    <div class="social-media">
        <a href="https://www.linkedin.com/in/mohamed-metwally-0182bb2b5" target="_blank" title="LinkedIn">
            <i class="fab fa-linkedin"></i> LinkedIn
        </a>
        <a href="mailto:MohamedMetwally.Mohamed@outlook.com" title="Email">
            <i class="fas fa-envelope"></i> Email
        </a>
        <a href="tel:+01002347613" title="Phone">
            <i class="fas fa-phone"></i> Phone
        </a>
    </div>

    <!-- Header Section -->
    <header>
        <h1 id="name" class="typing-effect">Mohamed Metwally</h1>
        <h2 class="typing-effect">Accountant, Financial Analyst, Data Analyst</h2>
        <div class="typing-effect" id="typing-effect">Mohamed Metwally</div>
        <img src="https://drive.google.com/uc?export=view&id=1ZuIowj4L4Vi-AaAyXE2_HjY_rFhC5VV-" alt="Mohamed Metwally" class="profile-img">
        
        <div class="nav-links">
            <a href="#about" class="typing-effect">About Me</a>
            <a href="#education" class="typing-effect">Education</a>
            <a href="#certifications" class="typing-effect">Certifications</a>
            <a href="#skills" class="typing-effect">Skills</a>
            <a href="#experience" class="typing-effect">Work Experience</a>
            <a href="#achievements" class="typing-effect">Achievements</a>
        </div>
    </header>

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
        <p><strong>Banking Intern</strong> – Bank Faisal Islami (October 2023 – December 2023)</p>
    </div>

    <!-- Achievements Section -->
    <div id="achievements" class="content-section">
        <h2>Achievements</h2>
        <ul>
            <li>Top Research Award 2025</li>
            <li>Received the CMA Scholarship</li>
            <li>Published Research in the International Journal of Economic Studies – Berlin</li>
            <li>First Prize in Academic Research at Benha University (2024)</li>
        </ul>
    </div>

    <!-- Footer Section -->
    <footer>
        <p>Contact: <a href="mailto:MohamedMetwally.Mohamed@outlook.com">MohamedMetwally.Mohamed@outlook.com



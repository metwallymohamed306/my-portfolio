<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohamed Metwally - CV</title>
    <style>
        /* General Styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f7f7f7;
            color: #333;
        }
        .container {
            width: 80%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 40px;
        }

        /* Header Section */
        #header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
        }
        .header-content {
            flex: 1;
        }
        .header-content h1 {
            font-size: 28px;
            font-weight: bold;
            color: #333;
        }
        .header-content p {
            font-size: 18px;
            color: #555;
        }
        .contact-info {
            display: flex;
            gap: 20px;
        }
        .contact-item {
            text-decoration: none;
            color: #0077b5;
            font-size: 16px;
        }
        .contact-item:hover {
            text-decoration: underline;
        }

        /* About Section */
        #about {
            background-color: #fff;
            padding: 40px;
            border-radius: 8px;
            margin-top: 40px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
        }
        #about h2 {
            font-size: 24px;
            font-weight: bold;
            color: #0077b5;
        }
        #about p {
            font-size: 16px;
            color: #555;
        }

        /* Sections Styles */
        section {
            margin-top: 40px;
        }
        h2 {
            font-size: 24px;
            font-weight: bold;
            margin-bottom: 15px;
            color: #0077b5;
        }
        ul {
            list-style-type: none;
            padding: 0;
            line-height: 1.6;
        }
        li {
            margin-bottom: 10px;
        }
        .job-title {
            font-weight: bold;
        }

        /* Skills Section */
        .skills, .languages, .computer-skills {
            display: flex;
            flex-wrap: wrap;
        }
        .skills div, .languages div, .computer-skills div {
            width: 30%;
            margin-bottom: 15px;
        }

        /* Achievements Section */
        .achievements {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .achievement {
            width: 45%;
            margin-bottom: 15px;
            background-color: #fff;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.05);
        }
        .achievement strong {
            color: #0077b5;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Header Section -->
        <div id="header">
            <div class="header-content">
                <h1>Mohamed Metwally</h1>
                <p>Accountant | Banking Operations | Financial Analyst |DATE Analyst </p>
            </div>
            <div class="contact-info">
                <a href="tel:"01002347613" class="contact-item">Phone: 01002347613</a>
                <a href="https://www.linkedin.com/in/your-linkedin" class="contact-item">LinkedIn</a>
                <a href="mailto:your-email@example.com" class="contact-item">Email</a>
            </div>
        </div>

        <!-- About Section -->
        <section id="about">
            <h2>About Me</h2>
            <p>
                I am a motivated and results-oriented accounting student with a passion for financial analysis and banking operations. 
                I have gained practical experience through internships in leading banks, such as CIB and Faisal Islamic Bank. 
                With expertise in accounting software, financial reporting, and banking operations, I am focused on combining my academic background with professional skills to drive operational efficiency and financial growth.
            </p>
        </section>

        <!-- Education Section -->
        <section id="education">
            <h2>Education</h2>
            <ul>
                <li><strong>Bachelor’s Degree in Accounting</strong><br> Faculty of Commerce, Benha University (Expected Graduation: 2025) – GPA: Very Good</li>
            </ul>
        </section>

        <!-- Certifications & Courses Section -->
        <section id="certifications">
            <h2>Certifications & Courses</h2>
            <ul>
                <li><strong>Diploma in Accounting and Finance</strong> – Oxford Home Study College (Jan 2025 – Mar 2025)</li>
                <li><strong>Diploma in Effective Bookkeeping and Payroll</strong> – Alison (Jan 2025 – Mar 2025)</li>
                <li><strong>AI Career Essentials</strong> – ALX (Dec 2024 – Feb 2025)</li>
                <li><strong>AWS Cloud Economics for Startups</strong> – Amazon Web Services (Nov 2024 – Jan 2025)</li>
                <li><strong>Financial Services</strong> – Amazon Web Services (Oct 2024 – Dec 2024)</li>
                <li><strong>Services Analyst</strong> – Amazon Web Services (Sep 2024 – Nov 2024)</li>
                <li><strong>Getting Started with Amazon</strong> – Amazon Web Services (Aug 2024 – Oct 2024)</li>
                <li><strong>Skills for Communication</strong> – IBM (Jul 2024 – Sep 2024)</li>
                <li><strong>Liquidity Management</strong> – The Open University (Jun 2024 – Aug 2024)</li>
                <li><strong>Data Literacy Certificate</strong> – SAS (May 2024 – Jul 2024)</li>
                <li><strong>Financial Accounting Management and Reporting</strong> – UNICEF (Apr 2024 – Jun 2024)</li>
                <li><strong>Diploma in Financial Management</strong> – American Board of Professional Studies (Mar 2024 – May 2024)</li>
                <li><strong>BuildSkills</strong> – Eyoot (Feb 2024 – Apr 2024)</li>
                <li><strong>Master's in Business Administration (Mini MBA)</strong> – American Board of Professional Studies (Jul 2023 – Apr 2024)</li>
                <li><strong>Small Project Implementation Phases, Business Models, Financial Planning Programs, Entrepreneurship</strong> – Banking Institute (Jun 2023 – Aug 2023)</li>
                <li><strong>Entrepreneurship</strong> – Undergraduate Researchers Initiative (Jan 2023 – Mar 2023)</li>
                <li><strong>Introduction to Banking, Accounting Fundamentals</strong> – CFI Institute (Dec 2022 – Feb 2023)</li>
                <li><strong>Certified International Trainer Diploma</strong> – Cambridge International Academy, UK (Nov 2022 – Jan 2023)</li>
                <li><strong>ICDL Preparation Course</strong> – UNIX Academy (Oct 2022 – Dec 2022)</li>
            </ul>
        </section>

        <!-- Skills Section -->
        <section id="skills">
            <h2>Skills</h2>
            <div class="skills">
                <div><strong>Personal Skills:</strong><br> Communication, Negotiation, Analytical, Attention to Detail, Time Management</div>
                <div><strong>Language Skills:</strong><br> Arabic (Native), English (Proficient), French (Good)</div>
                <div><strong>Computer Skills:</strong><br> Microsoft Office (Advanced Excel), Python, Oracle, QuickBooks, SAP</div>
            </div>
        </section>

        <!-- Work Experience Section -->
        <section id="work-experience">
            <h2>Work Experience</h2>
            <ul>
                <li><strong>Intern at CIB Bank</strong><br> June 2024 – Aug 2024: Gained experience in banking operations and financial services.</li>
                <li><strong>Intern at Faisal Islamic Bank</strong><br> June 2023 – Aug 2023: Assisted with daily banking functions and learned Islamic banking practices.</li>
                <li><strong>Accountant at Business Compaq Office for Accounting</strong><br> Mar 2021 – Apr 2023: Managed financial records, transactions, and assisted with audits.</li>
            </ul>
        </section>

        <!-- Achievements & Activities Section -->
        <section id="achievements">
            <h2>Achievements & Activities</h2>
            <div class="achievements">
                <div class="achievement"><strong>Ideal Student Award</strong> – Named Ideal Student of the Faculty of Commerce, Benha University (2024-2025)</div>
                <div class="achievement"><strong>University Research Recognition</strong> – Recipient of the University’s Encouragement Award for Scientific Research (2024)</div>
                <div class="achievement"><strong>First Place in Scientific Research</strong> – Awarded first place for Scientific Research in 2025</div>
                <div class="achievement"><strong>CMA Scholarship</strong> – Awarded a CMA scholarship in recognition of academic excellence</div>
                <div class="achievement"><strong>President, University Cities Students Union</strong> – Led initiatives and advocated for student welfare at Benha University</div>
                <div class="achievement"><strong>Member, European Organization for Human Rights and Sustainable Development</strong></div>

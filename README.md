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
            background-color: #f4f4f4;
            color: #333;
            direction: ltr;
        }

        /* Adding right to left for Arabic support */
        body[lang="ar"] {
            direction: rtl;
        }

        header {
            background-color: #4CAF50;
            color: #fff;
            padding: 30px;
            text-align: center;
            border-bottom: 3px solid #fff;
        }

        header h1 {
            margin-bottom: 10px;
            font-size: 2.5rem;
        }

        header p {
            font-size: 1.1rem;
            margin-bottom: 10px;
        }

        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-top: 10px;
            border: 5px solid #fff;
            object-fit: cover;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }

        section {
            margin-bottom: 20px;
            background-color: #fff;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            padding: 20px;
            border-radius: 8px;
        }

        section h2 {
            font-size: 1.8rem;
            margin-bottom: 15px;
            color: #4CAF50;
        }

        section h3 {
            font-size: 1.4rem;
            margin-top: 10px;
        }

        ul {
            list-style-type: none;
            padding-left: 20px;
        }

        ul li {
            margin-bottom: 8px;
            font-size: 1.1rem;
        }

        .language-toggle {
            text-align: center;
            margin-bottom: 20px;
        }

        .language-toggle button {
            padding: 10px 20px;
            font-size: 1rem;
            margin: 5px;
            cursor: pointer;
            border: 1px solid #4CAF50;
            border-radius: 5px;
            background-color: #fff;
            color: #4CAF50;
        }

        .language-toggle button:hover {
            background-color: #4CAF50;
            color: #fff;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 15px;
            margin-top: 30px;
        }

        footer p {
            font-size: 1.1rem;
        }
    </style>
</head>
<body lang="en">
    <header>
        <div class="container">
            <h1>Mohamed Metwally Mohamed</h1>
            <p>Awlad Saqr, Sharqiyah, Egypt | Phone: +01002347613 | Email: <a href="mailto:MohamedMetwally.Mohamed@outlook.com">MohamedMetwally.Mohamed@outlook.com</a></p>
            <p>LinkedIn: <a href="https://www.linkedin.com/in/mohamed-metwally-0182bb2b5">www.linkedin.com/in/mohamed-metwally-0182bb2b5</a></p>
            <img src="your-photo.jpg" alt="Mohamed Metwally" class="profile-img">
        </div>
    </header>

    <div class="language-toggle">
        <button onclick="setLanguage('en')">English</button>
        <button onclick="setLanguage('ar')">العربية</button>
    </div>

    <div class="container">
        <section class="objective">
            <h2>Objective</h2>
            <p>Seeking a Banker position to apply my skills in financial management, customer service, and banking operations. Passionate about enhancing client experience and optimizing financial processes through data analysis and digital banking solutions.</p>
        </section>

        <section class="education">
            <h2>Education</h2>
            <p><strong>Bachelor’s Degree in Accounting</strong><br> Faculty of Commerce, Benha University (Expected Graduation: 2025) – GPA: Very Good</p>
        </section>

        <section class="certifications">
            <h2>Certifications & Courses</h2>
            <ul>
                <li><strong>Diploma in Accounting and Finance</strong> – Oxford Home Study College (Jan 2025 – Mar 2025)</li>
                <li><strong>Diploma in Effective Bookkeeping and Payroll</strong> – Alison (Jan 2025 – Mar 2025)</li>
                <li><strong>AI Career Essentials</strong> – ALX (Dec 2024 – Feb 2025)</li>
                <li><strong>AWS Cloud Economics for Startups</strong> – Amazon Web Services (AWS) (Nov 2024 – Jan 2025)</li>
                <li><strong>Financial Services</strong> – Amazon Web Services (AWS) (Oct 2024 – Dec 2024)</li>
                <li><strong>Services Analyst</strong> – Amazon Web Services (AWS) (Sep 2024 – Nov 2024)</li>
                <li><strong>Getting Started with Amazon</strong> – Amazon Web Services (AWS) (Aug 2024 – Oct 2024)</li>
                <li><strong>Skills for Communication</strong> – IBM (Jul 2024 – Sep 2024)</li>
                <li><strong>Liquidity Management</strong> – The Open University (Jun 2024 – Aug 2024)</li>
                <li><strong>Data Literacy Certificate</strong> – SAS (May 2024 – Jul 2024)</li>
                <li><strong>Financial Accounting Management and Reporting</strong> – UNICEF (Apr 2024 – Jun 2024)</li>
                <li><strong>Diploma in Financial Management</strong> – American Board of Professional Studies (Mar 2024 – May 2024)</li>
                <li><strong>BuildSkills</strong> – Eyoot (Feb 2024 – Apr 2024)</li>
                <li><strong>Master's in Business Administration (Mini MBA)</strong> – American Board of Professional Studies (Jul 2023 – Apr 2024)</li>
                <li><strong>Small Project Implementation Phases, Business Models, Financial Planning Programs, Entrepreneurship, Bank and Small Projects Relationship</strong> – Banking Institute (Jun 2023 – Aug 2023)</li>
                <li><strong>Entrepreneurship</strong> – Undergraduate Researchers Initiative (Jan 2023 – Mar 2023)</li>
                <li><strong>Introduction to Banking, Accounting Fundamentals, Reading Financial Statements, Introduction to Capital Markets</strong> – CFI Institute (Dec 2022 – Feb 2023)</li>
                <li><strong>Certified International Trainer Diploma</strong> – Cambridge International Academy, UK (Nov 2022 – Jan 2023)</li>
                <li><strong>ICDL Preparation Course</strong> – UNIX Academy (Oct 2022 – Dec 2022)</li>
            </ul>
        </section>

        <section class="skills">
            <h2>Skills</h2>
            <h3>Personal Skills</h3>
            <ul>
                <li>Communication skills</li>
                <li>Negotiation skills</li>
                <li>Analytical skills</li>
                <li>Attention to detail</li>
                <li>Time management skills</li>
            </ul>

            <h3>Language Skills</h3>
            <ul>
                <li>Arabic: Native</li>
                <li>English: Proficient (writing and speaking)</li>
                <li>French: Good</li>
            </ul>

            <h3>Computer Skills</h3>
            <ul>
                <li>Microsoft Office (Excel, Word, Access, PowerPoint)</li>
                <li>Oracle Database</li>
                <li>Python (data analysis and automation)</li>
                <li>QuickBooks, SAP (accounting software)</li>
            </ul>

            <h3>Banking and Financial Skills</h3>
            <ul>
                <li>Financial statement analysis and reporting</li>
                <li>Banking regulations and financial compliance</li>
                <li>Loan processing and risk assessment</li>
                <li>Cash flow management and financial forecasting</li>
                <li>Budgeting and financial planning</li>
                <li>Accounting principles (GAAP, IFRS)</li>
            </ul>
        </section>

        <section class="work-experience">
            <h2>Work Experience</h2>
            <p><strong>Intern at CIB Bank</strong> (June 2024 – August 2024)</p>
            <p>Gained experience in banking operations and financial services, focusing on customer service.</p>

            <p><strong>Intern at Faisal Islamic Bank</strong> (June 2023 – August 2023)</p>
            <p>Gained knowledge of Islamic banking practices and assisted with daily banking functions.</p>

            <p><strong>Accountant at Business Compaq Office for Accounting</strong> (March 2021 – April 2023)</p>
            <p>Responsible for maintaining financial records, processing transactions, and assisting with audits using accounting software.</p>
        </section>

        <section class="achievements">
            <h2>Achievements & Activities</h2>
            <ul>
                <li><strong>Ideal Student Award</strong>: Named Ideal Student of the Faculty of Commerce, Benha University for the academic year 2024-2025.</li>
                <li><strong>University Research Recognition</strong>: Recipient of the University’s Encouragement Award for Scientific Research in 2024.</li>
                <li><strong>First Place in Scientific Research</strong>: Awarded first place for Scientific Research in 2025.</li>
                <li><strong>CMA Scholarship</strong>: Awarded a CMA scholarship in recognition of academic excellence and professional potential.</li>
                <li><strong>President, University Cities Students Union, Benha University</strong>: Led student initiatives and advocated for student welfare across university cities.</li>
                <li><strong>Member, European Organization for Human Rights and Sustainable Development</strong>: Contributed to efforts in human rights advocacy and sustainability.</li>
                <li><strong>International Certified Trainer</strong>: Certified by Cambridge Academy and the Human Development Trainers Syndicate, focusing on personal and professional development.</li>
                <li><strong>Volunteer, Life Makers Organization</strong>: Actively participated in community service initiatives in Sharkia Governorate.</li>
                <li><strong>Director, Egyptian Organization for Human Rights and Development</strong>: Oversaw and supported institutional initiatives aimed at enhancing human rights in Egypt.</li>
                <li><strong>Published Research Paper</strong>: Published a paper on “Activating the Partnership between the Faculty of Commerce, University Faculties, and Community Institutions” to improve educational and practical outcomes for students.</li>
                <li><strong>Technology Awareness Ambassador</strong>: Participated in the Ministry of Social Solidarity’s Technology Awareness Ambassadors Program to promote digital literacy.</li>
                <li><strong>Symposia Participation</strong>: Attended key symposia on etiquette, economic challenges, and international cooperation organized by Alexandria University.</li>
            </ul>
        </section>
    </div>

    <footer>
        <p>Contact: <a href="mailto:MohamedMetwally.Mohamed@outlook.com">MohamedMetwally.Mohamed@outlook.com</a></p>
    </footer>

    <script>
        function setLanguage(lang) {
            document.documentElement.lang = lang;
            if (lang === 'ar') {
                document.body.classList.add('rtl');
            } else {
                document.body.classList.remove('rtl');
            }
        }
    </script>
</body>
</html>


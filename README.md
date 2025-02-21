<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>محفظتي الشخصية</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
    <style>
        /* تنسيق عام */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background-color: #121212;
            color: white;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
            background-color: #1e1e1e;
        }

        nav .logo {
            font-size: 24px;
            font-weight: 600;
        }

        nav ul {
            list-style: none;
            display: flex;
        }

        nav ul li {
            margin-left: 20px;
        }

        nav ul li a {
            text-decoration: none;
            color: white;
            font-size: 18px;
            transition: color 0.3s ease;
        }

        nav ul li a:hover {
            color: #f39c12;
        }

        /* قسم الترحيب */
        .hero {
            text-align: center;
            padding: 100px 20px;
            background-color: #333;
        }

        .hero h1 {
            font-size: 48px;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 24px;
        }

        /* قسم عنّي */
        #about {
            padding: 50px 20px;
            background-color: #222;
            text-align: center;
        }

        #about h2 {
            font-size: 36px;
            margin-bottom: 20px;
        }

        /* قسم المشاريع */
        #projects {
            padding: 50px 20px;
            background-color: #333;
            text-align: center;
        }

        #projects h2 {
            font-size: 36px;
            margin-bottom: 30px;
        }

        .projects-container {
            display: flex;
            justify-content: center;
            gap: 20px;
        }

        .project {
            background-color: #444;
            padding: 20px;
            border-radius: 8px;
            width: 250px;
        }

        .project h3 {
            font-size: 24px;
            margin-bottom: 10px;
        }

        .project p {
            font-size: 16px;
        }

        /* قسم الاتصال */
        #contact {
            padding: 50px 20px;
            background-color: #222;
            text-align: center;
        }

        #contact h2 {
            font-size: 36px;
            margin-bottom: 20px;
        }

        /* التذييل */
        footer {
            text-align: center;
            padding: 20px;
            background-color: #1e1e1e;
        }

        footer p {
            font-size: 16px;
        }
    </style>
</head>
<body>
    <!-- شريط التنقل -->
    <nav>
        <div class="logo">محمد متولي</div>
        <ul>
            <li><a href="#home">الرئيسية</a></li>
            <li><a href="#about">عنّي</a></li>
            <li><a href="#projects">المشاريع</a></li>
            <li><a href="#contact">اتصال</a></li>
        </ul>
    </nav>

    <!-- قسم الترحيب -->
    <section id="home" class="hero">
        <h1>مرحبًا! أنا محمد متولي</h1>
        <p>مطور ومحاسب مالي. شغوف بالتكنولوجيا وتحليل البيانات.</p>
    </section>

    <!-- قسم عنّي -->
    <section id="about">
        <h2>عنّي</h2>
        <p>أنا طالب في جامعة بنها، وأعمل في مجال المحاسبة والتكنولوجيا. أحب تعلم كل ما هو جديد.</p>
    </section>

    <!-- قسم المشاريع -->
    <section id="projects">
        <h2>المشاريع</h2>
        <div class="projects-container">
            <div class="project">
                <h3>مشروع 1</h3>
                <p>وصف مختصر للمشروع.</p>
            </div>
            <div class="project">
                <h3>مشروع 2</h3>
                <p>وصف مختصر للمشروع.</p>
            </div>
        </div>
    </section>

    <!-- قسم الاتصال -->
    <section id="contact">
        <h2>اتصال</h2>
        <p>يمكنك التواصل معي عبر البريد الإلكتروني: example@example.com</p>
    </section>

    <footer>
        <p>حقوق الطبع والنشر &copy; 2025 محمد متولي</p>
    </footer>
</body>
</html>


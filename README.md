<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>کانال یوتیوب مرتضی صمدی</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: #fff;
            text-align: center;
        }
        header {
            background: #1f1f1f;
            padding: 15px;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: #ffcc00;
            text-decoration: none;
            font-weight: bold;
        }
        section {
            padding: 50px;
        }
        iframe {
            border-radius: 10px;
        }
        form {
            background: #222;
            padding: 20px;
            border-radius: 10px;
            width: 50%;
            margin: auto;
        }
        input, textarea, button {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: none;
            border-radius: 5px;
        }
        button {
            background: #ffcc00;
            color: #000;
            font-weight: bold;
            cursor: pointer;
        }
        footer {
            background: #1f1f1f;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>کانال یوتیوب مرتضی صمدی</h1>
        <nav>
            <ul>
                <li><a href="#home">صفحه اصلی</a></li>
                <li><a href="#videos">ویدیوها</a></li>
                <li><a href="#about">درباره من</a></li>
                <li><a href="#blog">بلاگ</a></li>
                <li><a href="#contact">تماس با من</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="home">
        <h2>به کانال من خوش آمدید!</h2>
        <p>در اینجا می‌توانید ویدیوهای جذاب و پخش‌های زنده من را دنبال کنید.</p>
        <iframe width="560" height="315" src="https://www.youtube.com/embed?listType=user_uploads&list=@mortezasamadi" frameborder="0" allowfullscreen></iframe>
    </section>
    
    <section id="videos">
        <h2>آخرین ویدیوها</h2>
        <div id="video-list"></div>
    </section>
    
    <section id="about">
        <h2>درباره من</h2>
        <p>من مرتضی صمدی هستم، یوتیوبر و سازنده محتوا در یوتیوب. محتوای سرگرم‌کننده، چالش‌ها و لایوهای جذاب را با شما به اشتراک می‌گذارم.</p>
    </section>
    
    <section id="blog">
        <h2>بلاگ</h2>
        <p>جدیدترین اخبار و مقالات درباره محتوای یوتیوبی من را اینجا بخوانید.</p>
    </section>
    
    <section id="contact">
        <h2>تماس با من</h2>
        <form>
            <label for="name">نام:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">ایمیل:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">پیام:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">ارسال</button>
        </form>
    </section>
    
    <footer>
        <p>تمامی حقوق محفوظ است - کانال یوتیوب مرتضی صمدی</p>
    </footer>
</body>
</html>

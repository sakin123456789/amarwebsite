<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <title>আমার পাঠশালা</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>আমার পাঠশালা</h1>
        <nav>
            <ul>
                <li><a href="#">হোম</a></li>
                <li><a href="#">নোটস</a></li>
                <li><a href="#">মডেল টেস্ট</a></li>
                <li><a href="#">যোগাযোগ</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="intro">
            <h2>স্বাগতম!</h2>
            <p>এই ওয়েবসাইটে তুমি HSC সকল বিষয়ের সাজেশন, নোট এবং মডেল টেস্ট পাবে।</p>
        </section>

        <section class="notes">
            <h2>নতুন নোটস</h2>
            <ul>
                <li><a href="#">পদার্থবিজ্ঞান ১ম পত্র - চ্যাপ্টার ১</a></li>
                <li><a href="#">রসায়ন ২য় পত্র - এসিড বেস</a></li>
                <li><a href="#">জীববিজ্ঞান - কোষ বিভাজন</a></li>
            </ul>
        </section>
    </main>

    <footer>
        <p>&copy; ২০২৫ আমার পাঠশালা | সকল অধিকার সংরক্ষিত</p>
    </footer>
</body>
</html>
body {
    font-family: 'Siyam Rupali', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f8ff;
}

header {
    background-color: #005f73;
    color: white;
    padding: 20px;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline-block;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

main {
    padding: 20px;
}

.intro, .notes {
    background-color: #ffffff;
    margin-bottom: 20px;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

footer {
    background-color: #005f73;
    color: white;
    text-align: center;
    padding: 10px;
}

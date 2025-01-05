<!DOCTYPE html>
<html lang="he">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>שרי הנדסה - בדק בית ופיקוח בנייה</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>שרי הנדסה</h1>
            <nav>
                <ul>
                    <li><a href="#about">אודות</a></li>
                    <li><a href="#services">שירותים</a></li>
                    <li><a href="#testimonials">המלצות</a></li>
                    <li><a href="#contact">יצירת קשר</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <button id="accessibility-button" aria-label="הפעלת תפריט נגישות">🔍 נגישות</button>

    <section id="hero">
        <div class="hero-content">
            <h2>בדק בית וליקויי בנייה</h2>
            <p>שירותי הנדסה מתקדמים עם דגש על אמינות, מקצועיות ותשומת לב לפרטים הקטנים.</p>
            <a href="#contact" class="cta">צור קשר עכשיו</a>
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2>אודות שרי הנדסה</h2>
            <p>שרי הנדסה מספקת שירותי בדק בית, פיקוח הנדסי ואבחון ליקויי בנייה למגוון רחב של פרויקטים. אנו מתמחים במתן פתרונות מותאמים אישית לצורכי הלקוח.</p>
        </div>
    </section>

    <section id="services">
        <div class="container">
            <h2>השירותים שלנו</h2>
            <ul class="services-list">
                <li>
                    <h3>בדק בית</h3>
                    <p>בדיקת נכסים לזיהוי ליקויים ומניעת בעיות עתידיות.</p>
                </li>
                <li>
                    <h3>פיקוח בנייה</h3>
                    <p>ניהול ופיקוח מקצועי על פרויקטים לבנייה.</p>
                </li>
                <li>
                    <h3>אבחון ליקויי בנייה</h3>
                    <p>איתור ותיעוד ליקויים על פי תקנים מחמירים.</p>
                </li>
            </ul>
        </div>
    </section>

    <section id="testimonials">
        <div class="container">
            <h2>המלצות</h2>
            <blockquote>
                <p>"שירות מקצועי ברמה הגבוהה ביותר. בזכות שרי הנדסה חסכנו זמן וכסף רב."</p>
                <cite>משה לוי</cite>
            </blockquote>
            <blockquote>
                <p>"צוות אמין ומקצועי, ממליץ בחום!"</p>
                <cite>דנה כהן</cite>
            </blockquote>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>צור קשר</h2>
            <form action="submit_form.php" method="POST">
                <label for="name">שם מלא:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">דוא"ל:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">הודעה:</label>
                <textarea id="message" name="message" required></textarea>

                <button type="submit">שלח</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2025 שרי הנדסה. כל הזכויות שמורות.</p>
        </div>
    </footer>
</body>
</html>


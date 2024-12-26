<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Portfolio of Kamal Al Dannawi, a professional programmer.">
  <title>Khaled Al Khaldi</title>
  <meta name="google" content="notranslate">
<script type="text/javascript">
  function googleTranslateElementInit() {
    new google.translate.TranslateElement(
      {pageLanguage: 'en'}, // استبدل 'en' بلغة صفحتك الأصلية
      'google_translate_element'
    );
  }
</script>
<script src="https://translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>
  <style>
    /* إعدادات عامة */
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      background: linear-gradient(120deg, #1f1c2c, #928dab);
      color: #fff;
      overflow-x: hidden;
    }

    /* تأثير رأس الصفحة */
    header {
      background: rgba(0, 0, 0, 0.7);
      color: #fff;
      padding: 50px 0;
      text-align: center;
      position: relative;
      overflow: hidden;
    }

    header::after {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: url('https://source.unsplash.com/random/1600x900?nature') center/cover no-repeat;
      z-index: -1;
      filter: brightness(0.4);
    }

    header h1 {
      font-size: 3rem;
    }

    header p {
      font-size: 1.2rem;
      margin-top: 10px;
    }

    /* التنقل */
    nav ul {
      list-style: none;
      padding: 0;
      display: flex;
      justify-content: center;
      background: rgba(0, 0, 0, 0.8);
    }

    nav ul li {
      margin: 0 15px;
    }

    nav ul li a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s ease;
    }

    nav ul li a:hover {
      color: #ff5733;
    }

    /* الأقسام */
    section {
      padding: 40px 20px;
      text-align: center;
    }

    section h2 {
      font-size: 2.5rem;
      margin-bottom: 20px;
      color: #ff5733;
    }

    footer {
      text-align: center;
      padding: 15px 0;
      background: rgba(0, 0, 0, 0.8);
      color: #fff;
      font-size: 0.9rem;
    }
    table {
            width: 80%;
            border-collapse: collapse; /* إزالة الفراغات بين الحدود */
            margin: 20px auto; /* توسيط الجدول */
            border: 1px solid #acd80c;
            border-radius: 15px; /* إضافة الزوايا المستديرة */
            overflow: hidden; /* منع تجاوز الزوايا المستديرة */
        }

        th, td ,tr{
            padding: 10px;
            text-align: center;
            border: 1px solid #acd80c;
        }

        th {
            background-color: #a12a2a;
        }

        tr:nth-child(even) {
            background-color: #a12a2a; /* لون مختلف للصفوف الزوجية */
        }

        tr {
            background-color: #a12a2a; /* لون مميز عند التمرير */
        }
  </style>
</head>
<body>
  <header>
    <u><h1>Khaled Al Khaldi</h1></u>
   <marquee behavior="10s" direction="left"><u><p>Phone & internet services</p></u></marquee> 
  </header>
  <nav>
    <ul>
      <li><a href="#about">About Me</a></li>
      <li><a href="#Services">Services</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>
  <main>
    <section id="about">
      <h2>About Me</h2>
      <p>Hello! My name is Khaled, and I am here to provide you with the best services. Our store is distinguished by its credibility and good treatment of customers.</p>
    </section>
    <section id="Services">
      <h2>Services</h2>
      <table>
        <tr>
            <td>Alfa</td>
            <th>U_share</th>
            <th>Gift</th>
            
        </tr>
        <tr>
            <td>Internet</td>
            <td>5G <br>10G <br>20G <br>30G</td>
            <td>5G <br>10G <br>20G <br>30G</td>
        </tr>
        <tr>
            <td>Price</td>
            <td>...L.L <br>...L.L <br>...L.L <br>...L.L</td>
            <td>...L.L <br>...L.L <br>...L.L <br>...L.L</td>
        </tr>
      </table>
    </section>
    <section id="contact">
      <h2>Contact Me</h2>
      <p>Email: <a href="mailto:khaled@gmail.com" style="color: #ff5733;">khaled@gmail.com</a></p>
      <p>facebook: <a href="#" target="_blank" style="color: #ff5733;">khaled-al-khalidi</a></p>
      <p>Phone :<a href="tel:+96170304667" style="color: #ff5733;">+96170304667</a> </p>
    </section>
  </main>
  <div id="google_translate_element"></div>
  <footer>
    <p>&copy; 2024 By Kamal Al Dannawi. All rights reserved.</p>
  </footer>
</body>


</html>

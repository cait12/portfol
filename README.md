
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Портфолио</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
<nav>
  <h1>Я начинающий Веб-разработчик</h1>
  <ul class="navigation">
    <li><a href="#about" class="nav-link">О мне</a></li>
    <li><a href="#skills" class="nav-link">Навыки</a></li>
    <li><a href="#projects" class="nav-link">Проект</a></li>
  </ul>
  <button class="burger-menu" id="burger-menu">
    <ion-icon class="bars" name="menu-outline"></ion-icon>
  </button>
</nav>
  <section class="hero" id="about">
    <div class="bio animate__animated animate__shakeX">
      <h2 class="bio-title">О мне</h2>
      <p class="bio-text">
 Я начинающий веб-разработчик. Люблю играть в ПК игры. Мечтаю стать професиональным Java-разработчиком.
      </p>
    </div>
  </section>

  <section class="skills" id="skills">
<h2>Я имею опыт в разработке Веб-сайтов (HTML с применением CSS и JavaScript)</h2>
<img src="https://avatars.mds.yandex.net/i?id=db0607fc2e5f4c53dce85879e2e5b56b13bd7d0b-10649741-images-thumbs&n=13" alt="Значек JavaScript">
  </section>


  <section class="projects" id="projects">
    <h2 class="projects-title">Я представляю 1 из проектов - Календарь</h2>
    <p>Этот проект я создал как пример моих навыков.</p>
    <p>В нем содержиться календарь на декабрь 2022 года,</p>
    <p>прайс на календарь, о компании и контакты.</p>

    <div class="projects-container">
      <div class="project-container project-card">
        <img src="https://img.freepik.com/free-photo/calendar-with-pencil-and-monstera-leaf_23-2148693336.jpg?size=626&ext=jpg" alt="календарь" class="project-pic">

        <h3 class="project-title">Пример сайта компании, которая производит календари</h3>
        <p class="project-details">

        </p>
        <a href="calendar.html" target="_blank" class="project-link">Посмотреть веб-сайт</a>
      </div>
    </div>
  </section>
<script src="tol.js"></script>
</body>







</html>

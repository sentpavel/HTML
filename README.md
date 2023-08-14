# HTML

Examples of layout HTML / HSS pages.


---


HW1 contains an example of an animated page using HTML5 and CSS. It uses the style.css file, three separate zones and a feedback form.
```HTML
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>Page Title</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header class="header">
    <h1 class="header__title">Привет<br>мир!</h1>
  </header>
  <article class="article article_whitebg article_first">
    <h2 class="black">Это моя первая<br>страница!</h2>
    <p class="black">Я научился писать <strong>HTML</strong>, а теперь я подключил свой первый стилевой файл и всё стало красивым :) Очень скоро я научусь делать такие же красивые страницы, а вы будете мне завидовать!</p>
  </article>
  <article class="article article_bluebg article_second">
    <h2 class="white">Свяжись со мной!</h2>
    <p class="white">Ты по-любому захочешь, чтобы я сделал такую же красоту и тебе. Поэтому я создал форму обратной связи! Пиши, не стесняйся :)</p>
    <form class="form">
      <input type="email" class="form_input" placeholder="E-mail">
      <input type="text" class="form_input" placeholder="Имя">
      <textarea class="form_textarea" placeholder="Ваше сообщение"></textarea>
      <button class="form_button" type="button">Отправить</button>
    </form>
  </article>
</body>
</html>
```


---


HW2 shows the use of the bootstrap framework to create a responsive abstract service page: a scientific dashboard. Created three breakpoint screens:
1. Large
2. Medium
3. Small.
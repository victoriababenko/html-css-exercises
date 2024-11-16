# html-css-exercises

## Exercises for lecture #2

1. В середині exercises створіть піддирексторію lecture-02. В середині lecture-02 створіть файли index.html та README.md

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lesson 3 challenges</title>

    <link rel="shortcut icon" href="./favicon.ico" type="image/x-icon">

</head>
<body>

</body>
</html>
```

2. Відредагуйте файл index.html
```html 

<!doctype html>
  <head>
	<!-- 
		Додайте тут елеиент style 
		В сепедині style визначте селектор p з властивістю color: red;
	-->
  </head>
  <body>
	<!-- 
		Додайте тут елеиент p з текстом This is my paragraph.
		визначте атрибут style для тега p зі значенням color: blue;
	-->

	<!-- 
		який колір буде мати текст This is my paragraph і чому.
	-->

  </body>
</html>
```

3. У наступному фпагменті випрвити помилки 
```html 
    <p>Звичайний, нудний абзац. Намагайтеся не заснути.</p>

    <p id="exciting">The most exciting paragraph on the page. One of a kind!</p>

    <div id="exciting">The most exciting paragraph on the page. One of a kind!</div>

	<style>
		#exciting {
			background: #f69d3c;
			border: 1px solid #696969;
			padding: 10px;
		}
	</style>
```


4. Чи буде змінна --bgColor видимою для елемента body. Яким буде фон елемента body і чому.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lesson 3 challenges</title>
    <link rel="shortcut icon" href="./favicon.ico" type="image/x-icon">

    <!-- Додайте тут елеиент style: -->
    <style type="text/css">
    	
    	body {
			background: var(--bgColor);
		}

		div {
			--bgColor: limegreen;
		}

		/*
		 визначте для елементів p властивість фону таким чином:
			background: var(--bgColor);
		*/
    </style>

</head>
<body>

    <!-- ... -->

	<!-- Додайте тут 2 елеиенти div: -->
	<div>
		<h3>Div 1</h3>
	    <p>Paragraph 1</p>
	</div>

	<div>
		<h3>Div 2</h3>
	    <p>Paragraph 2</p>
	</div>

</body>
</html>
```

5. Створити файл css/main.css
	- Перейти до кореня персонального сайта
	- Створити файли css/main.css та css/base.css
	- Відредагувати файл index.html
		1. Підключити css/main.css за допомогою тега link
		2. Підключити css/base.css за допомогою правила @import


6. Виправити помилку у фпагменті
```css
	* {
		margin: 0;
		padding: 0;
	}

	/* more styles */
	@import url("my-imported-styles.css");

```


7. Відредагувати файл css/base.css
	- Визначити у глобальній області видимості змінну:
    	--accentColorMuted: hsl(300, 40%, 40%);
	- Встановити, за допомогою цієї змінної властивість color для елемента a


8. Відредагувати розділ footer
```html

<footer>
  <!-- створити тут секцію -->
  	<!-- створити тут div -->
      <h2>About</h2>
	  <!-- 
	  створити тут невпорядкований список з такмсм елементами 
	  	<a href="#">Services</a>
        <a href="#">Portfolio</a>
        <a href="#">Pricing</a>
        <a href="#">Customers</a>
        <a href="#">Careers</a>
	  -->
	
	<!-- створити тут div -->
      <h2>Resources</h2>
	  <!-- 
	  створити тут невпорядкований список з такмсм елементами 
	  	<a href="#">Docs</a>
        <a href="#">Blog</a>
        <a href="#">eBooks</a>
        <a href="#">Webinars</a>
	  -->

	<!-- створити тут div -->
      <h2>Contact</h2>
	  <!-- 
	  створити тут невпорядкований список з такмсм елементами 
	  	<a href="#">Help</a>
        <a href="#">Sales</a>
        <a href="#">Advertise</a>
	  -->

  
  <!-- Footer legal -->
  <!-- створити тут section -->
  <!-- 
	  створити тут невпорядкований список з такмсм елементами 
	  	<a href="#">Terms &amp; Conditions</a>
        <a href="#">Privacy Policy</a>
        &copy; 2024 Copyright Shopaholic Inc.
	  -->
</footer>
```

Відредагуйте файл index.html:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lesson 4 challenges</title>

    <link rel="shortcut icon" href="/favicon.ico" type="image/x-icon">

	<link href="css/main.css" rel="stylesheet">

</head>
<body>
	
  	<section>
        <h1>This is a heading 1</h1>
		<h2>This is a heading 2</h2>
		<h3>This is a heading 3</h3>
    </section>

	<main id='main'>
		<h2 id="heading">This is a heading.</h2>
		<p class="heading">This is a heading.</p>
		Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium saepe placeat quisquam, eveniet aliquam ipsum amet cupiditate repudiandae obcaecati, impedit aperiam. 
	
	</main>
	
	<footer>
		<h2 class="h2">This is a h2.</h2>
		<p class="heading">This is a heading.</p>
	</footer>

	<p class="heading">This is a heading.</p>

</body>
</html>
```

9. Відредагуйте файл css/main.css
	- визначити для усіх елементів h1, h2, h3 на веб-сторінці властивість колір тексту - сірий. 
	- визначити для елемента з ідентифікатором main властивість color: #e60202;.
	- визначити для елемента з класом h2 властивість color: червоний.
	- встановити для елемента з класом heading колір тексту у зелений.

10. Відвідайте веб-сайт Google Fonts https://fonts.google.com/.
знайдіть шрифт Roboto, додайте шрифт «Roboto» за допомогою посилання на сторінку index.html.


11. базовий розмір шрифта для кореневого елемента = 100%
	- визначити розмір шрифта для body, що успадковує розмір шрифта кореневого елемента, збільшений на 40 відсотків

	- визначити розмір шрифта для h1, що успадковує розмір шрифта кореневого елемента, збільшений на 140 відсотків

12. Додайте до сторінки index.html наступну розмітку
```html
	<div>
	<span>Outer <span>inner</span> outer</span>
	</div>
```
	- Припустімо, що розмір шрифту для body встановлено на 16 пікселів. 
	- Слова «Outer» відображається з розміром 25,6 пікселів, а слово «inner» — 40,96 пікселів.
	- Всередині файла css/main.css 
		- визначте властивсть font-size для div, вказавши значення в одиницях виміру em.
		- визначте властивсть font-size для span, вказавши значення в одиницях виміру em.


13. Додайте до сторінки index.html наступну розмітку
```html
 	<div>
        <strong>Outer <strong>inner</strong> outer</strong>
    </div>
```
	- Припустімо, що розмір шрифту для body встановлено на 16 пікселів. 
	- Всередині файла css/main.css визначте властивсть font-size для strong так, щоб всі слова мали однаковий відносний розмір, еквівалентний 25,6 пікселів.

14. Відредагувати файл css/main.css
	- Встановити властивості елемента body:
		- font-family: Roboto
		- font-size: 1rem
	- Встановити властивість font-weight: 700 для елементів h1, h2, h3
	- Встановити властивість font-size: 1.45rem для елемента h1
	- Встановити властивість font-size: 1.3rem для елемента h2
	- Визначити клас .list-unstyled з властивістю list-style: none
	- Визначити клас .footer-social


15. Відредагуйте файл css/main.css 
	- Виконайте імпорт шрифтів font-awesomeза допомогою правила @import. 

9. Відредагуйте файл index.html
	- В розділі footer створіть section з атрибутом class="footer-social"
	- В середині цієї секції розмістіть елемент ul з атрибутом class="list-unstyled"
	- В середині ul розмістіть елементи li, кожний з яких має містити посилання на одну з соціальних мереж - facebook, twitter, github, linkedin, youtube, instagram.
	- Перегляньте документацію для font-awesome, знайдіть іконки відповідних соц-мереж та вставте їх як текст посилань

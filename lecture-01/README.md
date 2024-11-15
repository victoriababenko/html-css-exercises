# html-css-exercises

## Exercises for lecture #1

- Виконайте інсталяцію Visual Code
- Виконайте інсталяцію git
- Виконайте початкове налаштування Git
- Зареєструйтесь на github
- Створіть новий репозиторій з ім’ям свого облікового запису.

- В корені проєкту виконайте команду:

git remote add origin https://github.com/<ім’я вашого облікового запису>/<ім’я вашого облікового запису>.github.io

### Виконайте наступні кроки
1. В корені проєкту:
	- створіть файл README.md 
	- створіть файл index.html

```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>

</body>
</html>

```
На сайті https://favicon.io/ згенеруйте файл favicon.ico та розмістить його до кореня проєкту.
Відредагуйте файл index.html

```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- Додайте тут іконку для вашого сайту -->
	<link rel="shortcut icon" href="/favicon.ico" type="image/x-icon">
</head>
<body>

</body>
</html>

```

2. Створіть директорію exercises

	- В середині exercises створіть файл README.md
	- В середині exercises створіть піддиректорію lecture-01
	- В середині lecture-01 створіть файли index.html та README.md

**Результатом повинна стати така структура:**
```
├── exercises
│   ├── lecture-01
│   │   ├── index.html
│   │   └── README.md
│   └── README.md
├── index.html
├── LICENSE
└── README.md

```

3. Відредагуйте файл exercises/README.md

```
## Мої домашні вправи
```

4. Відредагуйте файл exercises/lecture-01/README.md

```
## Домашні вправи до лекції 1
```

5. Відкрийте термінал та перейдіть у корінь проєкту. Виконайте наступні команди з терміналу
	- git add .
	- git commit -m "added exercise 1"
	- git push origin main

6. В браузері викличте https://<ім’я вашого облікового запису>/<ім’я вашого облікового запису>.github.io 

7. Відредагуйте файл index.html

```html 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- змініть title на: Домашні вправи до лекції 2 -->
    <title>Document</title>
</head>
<body>
    
    <!-- Введіть свій код під цим рядком-->

    <!-- Додайте заголовок першого рівня: Ласкаво просимо до мого сайту! -->
	
    <!-- Додайте підзаголовок другого рівня: Про програмування -->

	<!-- Додайте підзаголовок третього рівня: Про HTML -->

    <!-- Додайте підзаголовок третього рівня: Про CSS -->
   
</body>
</html>

```

8. Весь текст у браузері відображатиметься в одному рядку, доки він не досягне межі вікна браузера. 

```html
<body>

<!-- додати розрив рядків для наступних 3-х речень -->

This is regular text.
This is another line after line break.
This is another line after line break.

<!-- форматувати наступні 3 речення як параграфи -->

This is a first paragraph. You can add any kind of text here. 
This is a second paragraph. This is some sample text. 
This is another paragraph. You can add multiple lines of text in this paragraph.

</body>
```

9. Змінити <зміни_мене> (change_me) на відповідні теги HTML

```html

	<!-- Тут має бути розділ сторінки, що містить посилання на інші сторінки або частини сторінок.  -->
	<change_me>
		<!-- Тут має бути елемент списку елементів, де порядок елементів не важливий -->
		<change_me>
 			<!-- Елементи списку є дочірніми вузлами списку елементів. -->
 			<!-- Елементи списку li є дочірніми вузлами ul. -->
	  			<change_me>
	  				<!-- Елемент з обов’язковим атрибутом href, що задає URl-адресу веб-сторінки: -->
	  				<change_me href="/">Home</change_me>
				</change_me>
				<change_me><a href="/events">Current Events</a></change_me>
 			</change_me>
 		</change_me>
	</change_me>
		
	<!-- Тут має бути елемент заголовка що обгортає елемент заголовка 1 та парвграф. -->
	<change_me>
		 <change_me>Welcome to...</change_me>
		 <change_me>Це елемент заголовка 1</change_me>
	</change_me>

	<change_me>
	   <!-- Це початок короткого абзацу. Він має деякі  вкладені теги, щоб підкреслити/виділити частину тексту. Наприклад: -->
	   <change_me>Це жирний текст.</change_me>
	   І, що ще цікавіше:
	   <change_me>Це курсив!</change_me>
	</change_me>

	<!-- Це розділ, що є базовим контейнером для елементів основного потоку. -->
	<change_me>
		<change_me>Це підзаголовок, укладений у теги "h3".</change_me>

   		<change_me>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quam optio expedita provident ratione itaque numquam, dolorem, at consequuntur laborum excepturi magnam culpa impedit obcaecati enim dolor totam. Assumenda, vel impedit?</change_me>
   
		<!-- Наступний тег використовують для визначення рядкових елементів у документі -->
		<p>Частка тексту <change_me style="color:#ff0000">червоного</change_me> кольору.</p>
		
		
   		<!-- Тут має бути горизонтальна лінія  -->
    	<change_me />
   
	    <change_me>
	   		Зменшує розмір шрифта на одиницю по відношенню до розміру звичайного тексту.
	   	</change_me>

   		<!-- Цей тег використовується для виділення цитат всередині документа. Тег має атрибут cite -->
		<change_me cite="https://www.ukrlib.com.ua/books/printit.php?tid=1052">Но зла Юнона, суча дочка, Розкудкудакалась, як квочка, — Енея не любила — страх; Давно уже вона хотіла, Його щоб душка полетіла К чортам і щоб і дух не пах.
		</change_me>

		<!-- Цей тег використовується для виділення коротких цитат.  -->
		<change_me>Розкудкудакалась, як квочка, — Енея не любила — страх</change_me>

		<!-- Цей тег маркує текст как цитату чи примітку на інший матеріал.  -->
		<p>ІВАН КОТЛЯРЕВСЬКИЙ <change_me>ЕНЕЇДА</change_me></p>

   		<!-- Цей тег дозволяє зберегти оригінальне форматування.  -->
		<change_me>
		       Но зла Юнона, суча дочка,
		       Розкудкудакалась, як квочка, —
		       Енея не любила — страх;
		       Давно уже вона хотіла,
		       Його щоб душка полетіла
		       К чортам і щоб і дух не пах.
		</change_me>
	</change_me>

	<!-- Це розділ, що є нижнім колонтитулом для його найближчого предка або кореневого елемента. -->
	<change_me>
	    <!-- container -->
	    <div>
		    <!-- Замінити символ © посиланням на сутність -->
		    <p>© 2024 All rights reserved.</p>
	    </div>
	</change_me>

```

10. Створіть на https://github.com мінімальний сайт, що складається з 4 сторінок:

	1. Головна - index.html
	2. Про нас - about.html
	3. Каталог - catalog.html
	4. Контакти - contact.html

Кожна сторінка повинна мати такі розділи

	- nav
	- header
	- main
	- footer

- Розділ nav повинен містити відносні посилання нв сторінки сайта, наприклад <a href="/">Home</a>
- Розділ header повинен містити тег загодовку 1-го ріаня.
- Розділ footer повинен містити абсолютеі посилання нв зовнішні сторінки, наприклад: <a href="https://www.google.com">Google</a>, та відкривати відповідний документ у новому вікні.

Завантажте створений сайт у власний репозиторій персонального сайту. 


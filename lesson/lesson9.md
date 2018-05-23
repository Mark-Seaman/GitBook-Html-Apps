# Semantic HTML Elements
* BACS 200 - Lesson 9 (Week 4)
* Monday, Jan 29, 2018
* Mark Seaman 

![](img/Bear_Logo.png)
         
### Weekly Learning
* Required reading Chapter 3 in HTML5 and CSS3
    * Use HTML to structure a web page
* Week 1 - Internet
* Week 2 - HTML Basics
* Week 3 - Tables and Images
* Week 4 - Page Layout

### Content Review
* 1-19 - Ex 5 - Hyperlinks & URLs
* 1-22 - Ex 6 - Tables
* 1-24 - Ex 7 - Images
* 1-26 - Ex 8 - Testing
* 1-29 - Ex 9 - Semantic Elements

### Follow Up
* Partial Credit  (10, 5, 0)
    * Do this work and you will get something
    * Submit URL in Canvas to get graded
* Validator errors

### Character encoding

```html
    <!doctype html>
    <html lang="en">
        <head>
            <meta charset="UTF-8">
            <title>Learning HTML</title>
        </head>
        <body>
            <h1>Core HTML elements</h1>
            <p>Paragraph - p</p>
        </body>
    </html>
```

## Today's Content
Semantic HTML Elements let you organize the content of your page.

### Semantic HTML Elements
* Start with Basic Page Template
* Add in Semantic Elements
    * Header
    * Main
        * Nav
    * Footer

### Basic HTML Template
Add this content to index.html

```html
    <!doctype html>
    <html lang="en">
        <head>
            <meta charset="UTF-8">
            <title>Learning HTML</title>
        </head>
        <body>
        </body>
    </html>
```

### Header, Main, Footer
* All elements go in body

```html

<head>
</head>

<body>
    <header> ... </header>
    <main> ... </main>
    <footer> ... </footer>
</body>

```

### Header
* The header element defines a block at the top of the page

```html

<body>
    <header>
        <img src="http://bacs200.unco.edu/BACS_200/img/Bear4.png"
             alt="Bear Logo" style="float:right" width="200">
        <h2>**STUDENT-ID** Title</h2>
    </header>
</body>
```

### Main
* The main element defines bulk of the page content

```html

<main>
    <h1>My Home Page</h1>
    <p>Paragraph</p>
</main>

```

### Nav
* The nav element defines special areas of the page content

```html
<main>
    <h1>My Home Page</h1>
    <nav>
        <ul>
            <li><a href="/">BACS Web Server</a></li>
            <li><a href="exercises">Exercises Page</a></li>
            <li><a href="quiz">Quiz Page</a></li>
        </ul>
    </nav>
    <p>Paragraph</p>
</main>
```

### Footer
* The footer element defines bottom area of the page

```html

<footer>
    <p>&copy; Copyright 2018 - Shrinking World Solutions</p>
</footer>

```

### Full Page Template
```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>My Page</title>
    </head>
    <body>
        <header>
            <img src="http://bacs200.unco.edu/BACS_200/img/Bear4.png"
                 alt="Bear Logo" style="float:right" width="200">
            <h2>My Site Title</h2>
        </header>
        <main>
            <h1>My Home Page</h1>
            <nav>
                <ul>
                    <li><a href="/">BACS Web Server</a></li>
                    <li><a href="exercises">Exercises Page</a></li>
                    <li><a href="quiz">Quiz Page</a></li>
                </ul>
            </nav>
        </main>
        <footer>
            <p>&copy; Copyright 2018 - **STUDENT-ID**</p>
        </footer>
    </body>
</html>
```

## Exercise
* Study the Semantic template code
* Create a page with semantic elements
* Apply semantic elements to your home page

### See you next time
* Read Chapter 3 in HTML5/CSS3
* Complete Ex 9 - due today

![](img/MCB.png)

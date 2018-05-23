# CSS Selectors
* BACS 200 - Lesson 19 (Week 8)
* Monday, Feb 26, 2018
* Mark Seaman

![](img/Bear_Logo.png)

### Class Progress
* Congratulations
* 7 Weeks to build website skills

### Content Review
* Basic CSS
* Blogging Project
* Quiz

### Standard Page Template
HTML Head

```html
<!doctype html>
<html>

    <head>
        <title>Page Title</title>
        <meta charset="UTF-8">
        <link rel="shortcut icon" href="http://unco.edu/favicon.ico">
        <link rel="stylesheet" href="styles.css">
    </head>

    <body>
    </body>

</html>
```

### Standard Page Template
HTML Body

```html

<body>
    <header>
        <nav></nav>
        <h1>Site Title</h1>
    </header>
    <main>
        <h1>Header</h1>
    </main>
    <footer>
        Legal Notices
    </footer>
</body>

```

### Quiz Feedback
Create a basic page using a standard template

* Quiz folder (2 points)
* Quiz6.html (2 points)
* Correct Elements (2 points)
* Valid CSS (2 points)
* Valid HTML (2 points)

### Blog Project
* You wrote your first article
* Blog 2 is due Friday

### 404 Club
* Failing to deliver the product
* Good intentions without follow through
* 404 = Humiliating Defeat
* Do not understand URLs

### Upcoming Topics
* Bootstrap
* Exam
* Blogging Project


## Today's Content
CSS Selector Workshop

* Universal selector
* Element Selectors
* Class Selectors
* ID Selectors

### Universal selector
Reset the default styles used by the browser

```css

* { margin: 10px; }

```

### Element Selectors
Select elements by element type

```css

main { padding: 1em; }

h1 { color:blue; }

```

### Class Selectors
Apply styles to different types of elements

```html

    <h1 class="idea">Headline</h1>

```


```css

    idea { color: green; }

```

### Class Selectors


```html

    <h1 class="button">Headline</h1>
    <p class="button">Paragraph</p>

```

```css
.button {
    background-color: green;
    color: white
}
```

### ID Selectors
Select specific elements

```html
<h1 id="headline">
    Headline
</h1>
<nav id="main-menu"> </nav>
```

```css
#headline {
    background-color: green;
    color: white
}

#main-menu {
    display: inline;
}
```

### Element and Class Selector
Select specific elements with certain classes

```html
<header>
    <h1 id="headline">
        Headline
    </h1>
</header>
```

```css
header.h1 {
    background-color: green; color: white
}
```

### Multiple Selectors
Select multiple element types

```html
<header>
    <h1 id="headline">
        Headline
    </h1>
</header>
```

```css
h1,h2,h3 {
    background-color: green;
    color: white
    font-family: sans-serif;
}
```

### Psuedo-class CSS Selectors
Control styles on hyperlinks


```html
< a href="http://google.com">
    Google
< /a >
```

```css
a:link {
    color: green;
}

a:visited {
    color: blue;
}

a:hover {
    color: red;
}
```


## Exercise
* Clone the CSS Workshop Template
* Don't change the CSS
* Adjust the HTML to use the correct selectors


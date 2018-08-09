# Main Menu
* BACS 200 - Lesson 18 (Week 7)
* Friday, Feb 23, 2018
* Mark Seaman

![](img/Bear_Logo.png)

### Content Review
* Basic CSS Properties
* Page Layout
* Main Menu

## Today's Content
Page Layout Elements

* header
    * nav
* main
    * section
    * aside
    * article
* footer


### Body of Page
* header
* main
* footer

```html

<body>
    <header></header>
    <main></main>
    <footer></footer>
</body>

```


### Navigation - Main Menu
Put the nav element in the header

```html

<header>
    <nav></nav>
</header>

```

### Menu Items
Main menu is a list of hyperlinks

```html

<nav>
    <ul>
        <li></li>
        <li></li>
        <li></li>
    </ul>
</nav>

```


### List Style
CSS Property - list-style-type

```css
nav ul {
    list-style-type: none;
    padding: 0em 1.5em;
    text-align: center;
}
```

### List Items
CSS Property - display

```css
nav ul li {
    display: inline;
    padding: 0em 1.5em;
    width: 200px;
    background-color: blue;
    color: white;
    box-shadow: 2px 2px 5px gray;
}
```


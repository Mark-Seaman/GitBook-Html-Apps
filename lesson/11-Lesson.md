# Page Structure
* BACS 200 - Lesson 11 (Week 4)
* Friday, Feb 2, 2018
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
* 1-26 - Ex 8 - Testing
* 1-29 - Ex 9 - Semantic Elements
* 1-31 - Ex 10 - Special Formatting
* 2-2  - Ex 11 - Page Structure

## Today's Content
* Semantic Elements
* HTML id Attributes
* Page Structure
* div and span

### Semantic Elements
* Outer Structure
    * header, main, footer
* Content Types
    * section, nav, article, aside
* Details
    * figure, figcaption, time

### section
* Area of the web page with special treatment
* Works with CSS to have special appearance of behavior

```html

<main>
    <section id="table-of-contents"> ... </section>
    <section id="inventory"> ... </section>
    <section id="summary"> ... </section>
</main>

```

### nav
* Used for creating menus
* Contains links to pages or ids on this page

```html

<nav id="main-menu">
    <ul>
        <li><a href="#inventory">Inventory</a></li>
        <li><a href="#summary">Summary</a></li>
        <li><a href="#article-1">My Inventory</a></li>
    </ul>
</nav>

```


### article
* Represents a logical topic article
* Examples: newpaper article, blog posting

```html

<main>
    <article id="article-1">This is the first article</article>
    <article id="article-2">Another article </article>
</main>

```

### aside
* Visual callout for sidebars
* Page within a page

```html

<main>
    <aside id="sidebar">
        <h2>About this thing</h2>
        <p>There is a lot to say about this</p>
    </aside>
</main>

```

### figure
* Images with captions

```html

<figure id="monkeys">
    <img src="monkeys.jpg" alt="monkeys">
    <figcaption>Figure 1: Monkeys in Trees</figcaption>
</figure>

```

### time
* Used for showing time (helps with parsing)
* Publication dates on articles

```html

<time datetime="2018-02-02" pubdate="false">Today</time>

```

### HTML id Attributes
* Set id on any element
* Link href uses #id-name

```html

<h2 id="article-1">

<a href="#article-1">Winter Forecast</a>

```

### HTML id Attributes
* Set id on any element
* Link href uses #id-name

```html

<figure id="monkeys">

<a href="#monkeys">Learn about monkeys</a>

```

### Page Structure

```html

<main>

    <nav id="main-menu">
        <ul>
            <li><a href="#article-1">Article 1</a></li>
            <li><a href="#article-2">Article 2</a></li>
        </ul>
    </nav>

    <aside>
        <h2>Table of contents</h2>
        <ul>
            <li>Topic 1</li>
            <li>Topic 2</li>
        </ul>
    </aside>

    <article id="article-1">
        <h2>Article 1</h2>
        <p>Text for topic 1</p>
    </article>

    <article id="article-2">
        <h2>Article 2</h2>
        <p>Text for topic 2</p>
    </article>

</main>

```


## Exercise
* Build a blog curating other content
* Create three articles
    * Video
    * Book info
    * Reviews
* Create a main menu


### See you next time
* Read Chapter 3 in HTML5/CSS3
* Complete Ex 11 - due today

![](img/MCB.png)


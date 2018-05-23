# Forms
* BACS 200 - Lesson 12 (Week 5)
* Monday, Feb 5, 2018
* Mark Seaman

![](img/Bear_Logo.png)

### Weekly Learning
* Required reading Chapter 11 in "HTML5 and CSS3"
    * How to work with Forms
* Week 1 - Internet
* Week 2 - HTML Basics
* Week 3 - Tables and Images
* Week 4 - Page Layout

### Content Review
* 1-26 - Ex 8 - Testing
* 1-29 - Ex 9 - Semantic Elements
* 1-31 - Ex 10 - Special Formatting
* 2-2  - Ex 11 - Page Structure
* 2-5  - Ex 12 - Forms


## Today's Content
Handling forms for input

### Form Handling Skills
* Define a form
* Form fields to collect data
* Submit action

### Define a form
Basic form processing

```html
<form action="subscribe.html">
    <input type="text" value="me@unco.edu">
    <input type="submit">
</form>
```

### Query Parameters
Pass data to a web page in the URL

```
http://bacs200.unco.edu/BACS_200/templates/form-subscribe.html?email=me%40unco.edu
```

* URL domain - http://bacs200.unco.edu
* URL directory - BACS_200/templates
* URL file - form-subscribe.html
* URL query - ?email=me%40unco.edu

### Query Parameters
Pass data to a web page in the URL

* URL query - ?email=me%40unco.edu
* email - me%40unco.edu
* URL is encoded
    * "?" -- Start of variable list
    * "%40" -- @
    * "+" -- space
    * "&" -- next variable

### Form fields to collect data
Input field types
* text
* select
* textarea
* radio
* button
* checkbox

### Field Validation
* required
* autocomplete
* novalidate

```html
<input type="email" name="email" required>
<input type="email" name="email" novalidate>
<input type="email" name="email" autocomplete="off">

```

### More Field Types
* number - min, max, value
* email
* url
* tel
* date
* password

```html
<input type="number" name="counts" min="1" max="5">
```


### Submit action
HTTP Method - GET or POST

* GET - pass data in URL
* POST - pass data in Form

```html
<form action="thanks.html">
<form method="get" action="thanks.html">
<form method="post" action="thanks.html">
```

### target attribute
Go to another tab

```html
<h2>Google Search</h2>
<p>Use this form to search for content on Google.</p>

<form action="http://google.com/search" target="_blank">
    <input type="search" name="q" size="30" maxlength="255">
    <input type="submit">
</form>
```

## Exercise
* Clone ex11
* Submit new customer reviews
* Search for answers on Google


### See you next time
* Chapter 11 in "HTML5 and CSS3"
* Complete Ex 12 - due today

![](img/MCB.png)


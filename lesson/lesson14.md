# Stylesheets
* BACS 200 - Lesson 14 (Week 6)
* Monday, Feb 12, 2018
* Mark Seaman

![](img/Bear_Logo.png)

### Content Review
* Required reading Chapter 4 in "HTML5 and CSS3"
    * Use CSS to format elements
* Week 1-5 - HTML
* Week 6 - CSS Basics

### Grades
* Purpose of grades
    * Direct reflection of skill and knowledge
    * Exercises are for practice of skills
    * Exams are for evaluating knowledge
* Equal weight - exercises, quizzes, exams
* Emphasizes applying skills

### Exam
* Feedback from Exams
    * Good spread of grades
    * Much more successful than last semester
    * Generous partial credit
* Tips for next exam
    * Read the book
    * Review the exercises
    * Pay attention during lectures


## Today's Content
* Linking a CSS
* CSS Syntax
* Text Properties

### CSS Rule Set
CSS syntax

```css
selector {
    property: value;   /* one rule */
    property: value;
}

```

Example Rule Set

```css
h1 {
    font-family: serif;
    font-size: 120%;
}
```

### Hooking up CSS
Link the Stylesheet to each HTML page

```html
<link rel="stylesheet" href="styles.css">
```

### CSS Properties
CSS Property Groups
* Text
* Color
* Spacing
* Borders

### Text Properties
* font-family
* font-size
* font-weight
* text-align
* text-shadow

### font-family
Inherited by all descendants

```css
body {
    font-family: Arial, Helvetica, sans-serif;
}

p {
    font-family: "Times New Roman", Times, serif;
}
```

### Size Units
Units of size for values

    20px - 20 pixels
    10pt - 10 points
    2em - twice the line height (M)
    50% - half the size

### font-size
Multiple units

```css
    font-size: 12pt;  /* in points */
    font-size: 150%;  /* parent element */
    font-size: 1.5em;  /* M is line height */
```

### font-weight
Special font treatment

```css
    font-weight: 400;  /* normal */
    font-weight: normal;  /* 400 */

    font-weight: 700;  /* bold */
    font-weight: bold;  /* 700 */

    font-weight: lighter;  /* parent element */
```

### text-align
Where does the space go?

```css
    text-align: left;
    text-align: center;
    text-align: right;
```

### text-shadow
Give a 3D look

```css
h1 {
    text-shadow: 2px 2px;
}


h2 {
    text-shadow: -2px -2px 4px yellow;
}
```

### font
Shorthand font property

```css
    font: italic bold 16px Arial, sans-serif;

    font: 120% Times;
```


## Exercise
* Clone your template
* Add a stylesheet
* Set up CSS rules
* Validate CSS
    * Visit the http://jigsaw.w3.org/css-validator
    
### See you next time
Required reading

* Chapter 4 in "HTML5 and CSS3"
* Use CSS to format elements

Complete Ex 14 - due today

![](img/MCB.png)


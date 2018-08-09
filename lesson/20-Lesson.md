# Design Review
* BACS 200 - Lesson 20 (Week 8)
* Wednesday, Feb 28, 2018
* Mark Seaman

![](img/Bear_Logo.png)

### Follow Up
* Grades - checkpoint & exam
* CSS Selectors
* Design Review

### Grades (25% each)
* Exercises 30
* Quizzes 10
* Blog 10
* Exams 3  (drop one)

### Exam Study
* HTML Page Template
* URLs for images and links
* CSS for styling pages

## CSS Selectors
CSS Selector Workshop

* Universal selector
* Element Selectors
* Class Selectors
* ID Selectors
* Combo Selectors

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
    <h1 class="headline">
        Headline
    </h1>
</header>
```

```css
header.h1 {
    background-color: green; color: white
}
```

### Nested Element Selector
Select specific elements within other elements

```html
<header>
    <h1>
        Headline
    </h1>
</header>
```

```css
header h1 {
    background-color: green; color: white
}
```

### Multiple Selectors
Select multiple element types

```html
<header>
    <h1>
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


## Design Review
* Every real-world project is reviewed by multiple people
* Measure your success and give feedback

### Review Process
A Seaman's Guide to Design Review

* Assign Reviewers
* Complete Scorecard
* Designer Improvements
* Follow Up Review

### Assign Reviewers
Assignments are found at [Review Groups](/BACS_200/reviews.html)

All feedback will be in writing

You review 3 and get reviewed by 3

### Complete Scorecard
* Scorecard rates requirements
* Use the template in [Review Checklist](/BACS_200/templates/review_checklist.html)
* Create score
* Tell how to get a perfect score
* Should take 20-30 minutes

### Designer Improvements
* Fix your site by Friday
* Should take 20-30 minutes

### Follow Up Review
* Review follow up
* Should take 10 minutes

### Blog Project
* Blog 1 graded
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


## Exercise
* Clone the CSS Workshop Template
* Don't change the CSS
* Adjust the HTML to use the correct selectors


# Tab Views
* BACS 200 - Lesson 21 (Week 8)
* Friday, March 2, 2018
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
Topics for Study Guide

* HTML Page Template
* URLs for images and links
* CSS for styling pages

### Design Review Experience
* Share your story

### Speed over accuracy
* Don't try to get it right
* Get feedback early and often
* Fix it immediately

### Proverb
Development proceeds at the speed of test


## Info Organization
User must be able to see what they are looking for

* Break complex info into chunks
* Provide a clear path

### Tab Views - Before

![](../img/21-1.png)

### Tab Views - After

![](../img/21-2.png)

### Tab Views - JS and CSS
Load CSS styles and Java Script code

```html
<head>
	<link rel="stylesheet" type="text/css" href="jquery-ui.min.css">

	<script src="jquery-2.1.3.min.js"></script>
	<script src="jquery-ui.min.js"></script>

    <script>
		$(document).ready(function() {
			$("#tabs").tabs();
		});
	</script>
</head>
```

### Tab Views - HTML
Define tabs as list and content pages

```html
<section id="tabs">

    <ul>
        <li><a href="#tabs-1">One</a></li>
        <li><a href="#tabs-2">Two</a></li>
        <li><a href="#tabs-3">Three</a></li>
    </ul>

    <div id="tabs-1">
        <h2>Tab One Content</h2>
    </div>
    <div id="tabs-2">
        <h2>Tab Two Content</h2>
    </div>
    <div id="tabs-3">
        <h2>Tab Three Content</h2>
    </div>

</section>
```

### Tab Views - Application
* Design Review Groups
* Study Guide
* Reviews Page

### Design Review Groups
* Review the code
* Make sure that you could rename the groups
* What code would change for a new group?

### Study Guide
Topics for Exam

* HTML Page Layout Template
* CSS Usage and Properties
* URL Mapping

### Reviews Page
Wrap your three reviews in tabs

* Many more reviews will be done
* More tools will be added as needed


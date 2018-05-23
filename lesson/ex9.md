# Ex 9 - Semantic Elements

## Study the code for placing an image on your page
* Visit the [Templates](/BACS_200/templates.html) to see what has changed.
* Visit the [Semantic template](/BACS_200/templates/semantic.html)
to understand how to use the Semantic HTML Elements in your page.


## Create a page ex9.html
* Add the contents of the Semantic Elements template.
* Replace all placeholder text with real text.


## Fix up exercises page
* Your exercises page contains a table of links to the ex page and the validator.
* Add ex9 to the table.
* Test the validator link.


## Fix up home page
* Edit your root level index.html page
* Make sure that it contains the following HTML

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>**STUDENT-ID** Home Page</title>
    </head>
    <body>
        <header>
            <img src="http://bacs200.unco.edu/BACS_200/img/Bear4.png"
                 alt="Bear Logo" style="float:right" width="200">
            <h2>**STUDENT-ID** Title</h2>
        </header>
        <main>
            <h1>**STUDENT-ID** Home Page</h1>
            <nav>
                <ul>
                    <li><a href="/">BACS Web Server</a></li>
                    <li><a href="exercises">Exercises Page</a></li>
                    <li><a href="quiz">Quiz Page</a></li>
                    <li>
                        <a href="https://validator.w3.org/nu/?doc=http://bacs200.unco.edu/**STUDENT-ID**/index.html">
                        Validate this page</a>
                    </li>
                </ul>
            </nav>
        </main>
        <footer>
            <p>&copy; Copyright 2018 - **STUDENT-ID**</p>
        </footer>
    </body>
</html>
```

## Validate your HTML
* You have just created three new pages
* Make sure that each of them contain valid HTML


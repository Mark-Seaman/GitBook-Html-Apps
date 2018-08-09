# Lesson 5 - Hyperlinks and URLs
* BACS 200 - Lesson 5 (Week 2)
* Wednesday, Jan 19, 2018
* Mark Seaman 

![](img/Bear_Logo.png)
         
### Learning Process
* Required reading Chapter 2 in HTML5 and CSS3
    * How to code, test, and validate a web page

### Content Review
* 1-10 - Ex 2 - Setup Windows and One Drive
* 1-12 - Ex 3 - Directory structure
* 1-17 - Ex 4 - Writing HTML
* 1-19 - Ex 5 - Hyperlinks & URLs
* 1-22 - Ex 6 - Images

## URLs
* Uniform Resource Locator - web address

### http://bacs200.unco.edu/BACS_200/templates/index.html
* Protocol - http://
* Domain - bacs200.unco.edu
* Directory Path - BACS_200/templates
* File Name - index.html

### Protocol - http://
how we talk - format of the message response
* http - Hypertext transfer protocol
* file - File
* mailto - Email protocol

### Domain - bacs200.unco.edu
What machine are we accessing
* Root domain - unco.edu
* Sub-domain - bacs200, ursa, canvas

### Directory Path - BACS_200/templates
Directory that holds files
* No spaces
* Path separator  "/"
* URL encoding

### File Name - index.html
Points to the specific file we want
* me.png, index.html, ex5.html, theme.css, coolstuff.js
* Static servers just return files

## Hyperlink
HTML anchor element

```html
<a href="/">Server Root</a>
```

### Page with Link

Sets the page title on the browser tab or the bookmark.

```html
    <!doctype html>
    <html>
        <body>
            <h1>My Root Page</h1>
            <p>
                This is a link to the 
                <a href="/">Server Root</a>
            </p>
        </body>
    </html>
```

### Different types of links
* Relative
    * Path from current directory
* Server Root
    * Path from top of server
* Absolute
    * Path includes domain

### Relative URL
* Path from current directory
* Example: Loading ex4.html
* Link to index.html

    href="index.html"

### Relative Directory URL
From page ex4.html
* Current Directory
```
    href="."
```
* Up One Directory
```
    href=".."
```
### Relative Page URL
* Same Directory
```
    href="index.html"
```
* Child Directory
```
    href="quiz/quiz1.html"
```
* Sibling Directory
```
    href="../quiz/quiz1.html"
```
### Server Root
* Path from top of server
* Top of server
```
    href="/"
```
* Other directory
```
    href="/myfiles/abc"
```
### Absolute
* Path includes domain & protocol
```
    href="http://google.com"
```


## See you next time
* Read Chapter 2 in HTML5/CSS3
* Complete Ex5 - due today
* Quiz 2

![](img/MCB.png)


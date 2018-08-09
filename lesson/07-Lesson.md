# Lesson 7 - Displaying Images
* BACS 200 - Lesson 7 (Week 3)
* Wednesday, Jan 24, 2018
* Mark Seaman 

![](img/Bear_Logo.png)
         
### Weekly Learning
* Required reading Chapter 3 in HTML5 and CSS3
    * Use HTML to structure a web page
* Week 1 - Internet
* Week 2 - HTML Basics
* Week 3 - Tables and Images

### Content Review
* 1-12 - Ex 3 - Directory structure
* 1-17 - Ex 4 - Writing HTML
* 1-19 - Ex 5 - Hyperlinks & URLs
* 1-22 - Ex 6 - Tables
* 1-24 - Ex 7 - Images

## Today's Content
Displaying Images

### Basic Image Element
* img element
* src attribute
* alt text attribute

```html
    <img src="Bear_Logo.png" alt="Bear Logo">
```

### Image Source - Absolute Path
* Includes the protocol and domain
* http://bacs200.unco.edu/BACS_200/img/Bear_Logo.png

```html
<img src="http://bacs200.unco.edu/BACS_200/img/Bear_Logo.png"
    alt="Absolute">
```

### Image Source - Server Path
* Path from top of web server
* /BACS_200/img/Bear_Logo.png

```html
<img src="/BACS_200/img/Bear_Logo.png"
    alt="Server">
```

### Image Source - Relative Path
* Path from this page
* ../img/Bear_Logo.png

```html
<img src="../img/Bear_Logo.png"
    alt="Relative">
```

### Width - pixels
* Width in pixels - scale the image to the requested size

```html
    <img src="Bear_Logo.png" width="100px">
    <img src="Bear_Logo.png" width="50px">
    <img src="Bear_Logo.png" width="800px">
```

### Width - percentage
* Width in percent - scale to a percentage of the available area.
* Only display is affected.

```html
    <img src="Bear_Logo.png" width="100%">
    <img src="Bear_Logo.png" width="50%">
```

### Image Float
* Flow the text around the image

```html
<img src="Logo.png" style="float:left">
<p>This is a lot of text that flows around the image.</p>
<p>This is a lot of text that flows around the image.</p>
```

### Max Width
* Limit the image to the available display space
* Important for Responsive Web Design

```html
<img src="Logo.png" width="800px" style="max-width:100%">
```


## Chrome Developer Tools
* Visit [Image Templates](/BACS_200/templates/image.html)
* Run dev tools - F12
* Inspect last image on page
* Mouse over Elements
* Styles
* Computed


## Exercise 7
* Review the template file
* Create an article that contains an image
* Use developer tools to set attributes

### See you next time
* Read Chapter 3 in HTML5/CSS3
* Complete Ex7 - due today

![](img/MCB.png)


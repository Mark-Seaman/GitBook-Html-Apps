# Deploy a web page

## Create Files in Windows Directory

Create a Folder using Windows

* Right click on the Windows Desktop
* Choose New Folder "BACS200"
* Visit the HTML page at [http://bacs200.unco.edu/ex1.html](http://bacs200.unco.edu/ex1.html)
* Save page as "Desktop\\BACS200\\ex1.html"
* Test the page by double-clicking "Desktop\\BACS200\\ex1.html"


## Configure Filezilla

Run FileZilla

* Click on Start Menu and type FileZilla

Create Site Manager entry

* Click on Site Manager in file menu
* New Site
* Host name: BACS200.UNCO.EDU
<br>

Configure FTP Site Manager General Options

![](img/1-11.png)

* Host: bacs200.unco.edu
* Protocol: FTP - File Transfer Protocol
* Encryption: Require explicit FTP over TLS
* Logon Type: Normal
* User: student1\\your-id
* Password: your canvas password
<br>

Configure FTP Site Manager Advanced Options
![](img/1-10.png)

* Default local directory:  C:\\Users\\xxx\\Desktop\\BACS200
<br>

Using FileZilla

![](img/1-12.png)
<br>

Disconnect from FTP server

* Close FileZilla
* Open FileZilla
* Reconnect again to make sure that everything still works


## Copy to the File Server

Connect to the File Server

* Login to the File Server using FileZilla
* Local Directory: Desktop\\BACS200
* Remote Directory: /
* Upload: ex1.html

Test the web server page

* Visit the URL - http://bacs200.unco.edu/your_id/index.html
* If your page does not load (404) then revisit all the steps that you did to find the error.


## Update Canvas

* Login to Canvas
* Visit Modules, Week 1, Ex 1 - Deploy your web page
* Submit the URL for the exercise "http://bacs200.unco.edu/your_id/index.html"

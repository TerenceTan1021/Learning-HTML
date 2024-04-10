# HTML stands for 
- H: Hyper
- T: Text
- M: Mark-up
- L: Language

You could say that HTML add structure for a website, a foundation to saupport content for a website.

# Basic index.html starting point

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

**useful tags**
```
<br>    <!--breaks the line-->
<hr>    <!--adds a horizontal line-->

<!-- THIS IS A COMMENT-->
```

**Heading**
-----------------------------------------------------------------------------------------------------------------------------
![Picture of the heading style](image/heading.png)

```
<body>
    <h1>This is h1 heading</h1>
    <h2>This is h2 heading</h2>
    <h3>This is h3 heading</h3>
    <h4>This is h4 heading</h4>
    <h5>This is h5 heading</h5>
</body>
```

**Paragraph**
-----------------------------------------------------------------------------------------------------------------------------
```
<p>Hello world</p>    <!--This will hold the paragraph and no matter
                          what changes you make to it it will retain its         
                           paragraph form-->

<pre>                   <!--This way the text between will contain the line break-->

Hello

World

</pre>
```

**Hyper Link**
-----------------------------------------------------------------------------------------------------------------------------
> _To other links_
```
<a href = "(YOUR LINK)"
target ="_blank"            <!-- Open new tab or new window-->
title="Goes to link"
click me                     <!--name of the link-->
</a>
```
> _To other html file_
index.html
```
<body>
    <a href="Hello_World.html">
    HelloWorldTEXT

    </a>
</body>
```
Hello_World.html
```
<h1> Hellow World</h1>
```
> _To process of email_
```
<body>
    <a href="mailto: test@fake.com>
    email me
    </a>
</body>
```

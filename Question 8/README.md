# HTML tags like `<a>` can have certain attributes. The href attribute is mandatory in the `<a>`tag. Additionally it is possible to use the title attribute which specifies a text that emerges when the mouse cursor is moved above a link. This kind of text is called a tool tip. Modify the link that you created in the previous exercise so that a tool tip says "This leads you to another page." when the mouse cursor is over the link.

## *index.html*
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Web Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        h1 {
            color: #333;
        }
        p {
            font-size: 16px;
            line-height: 1.5;
            margin: 15px 0;
        }
        ul, ol {
            margin: 20px 0;
            padding-left: 20px;
        }
        img {
            max-width: 100%;
            height: auto;
            border: 2px solid #333;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <h1>Welcome to My First Web Page</h1>
    
    <p>This is the first paragraph of my web page. It provides a brief introduction to the content I will share. HTML is a simple language for creating web pages, and it’s easy to learn the basics.</p>
    
    <p>This is the second paragraph. Here, I might talk about how I’m learning HTML and how excited I am to create my first webpage. Adding headings, paragraphs, lists, and images makes the content more engaging.</p>
    
    <h2>Things I've Learned About HTML</h2>
    <ul>
        <li>An unordered list can be specified with the tags <code>&lt;ul&gt;</code> and <code>&lt;/ul&gt;</code>.</li>
        <li>An unordered list typically contains a number of list items that can be specified with tags <code>&lt;li&gt;</code> and <code>&lt;/li&gt;</code>.</li>
        <li>After you have created your unordered list, check out what happens when you convert it to an ordered list by replacing the tags <code>&lt;ul&gt;</code> and <code>&lt;/ul&gt;</code> with <code>&lt;ol&gt;</code> and <code>&lt;/ol&gt;</code>, respectively.</li>
    </ul>

    <h2>Here’s an Image I Like</h2>
    <img src="img.png" alt="Sample Image" />

    <!-- Link to the second page with a tooltip -->
    <p><a href="another_page.html" title="This leads you to another page.">Go to the other page.</a></p>

</body>
</html>

```

## *another_page.html*
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Another Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        h1 {
            color: #333;
        }
        p {
            font-size: 16px;
            line-height: 1.5;
            margin: 15px 0;
        }
    </style>
</head>
<body>

    <h1>Welcome to Another Page</h1>
    
    <p>This is the first paragraph of the second page. Here, you can continue to explore different HTML elements and how they work together to create web pages.</p>
    
    <p>This is the second paragraph on this page. Linking between pages is an essential feature of the web, allowing you to navigate between different sections of a website easily.</p>

</body>
</html>
```

## PAGE 1
![Screenshot (42)](https://github.com/user-attachments/assets/56ea2b8e-948b-4e34-a740-cc886ffeba8a)
## PAGE 2
![Screenshot (41)](https://github.com/user-attachments/assets/eb551717-f6f5-4728-83e5-fe6c85e562f8)

# Create another .html file that contains a heading and a couple of paragraphs. You could name this new file another_page.html, and you should place it into the same folder where your first .html is. After you have created the new .html page, add a link to the first page so that the browser will load another_page.html when you click the text Go to the other page. in the first page. You need to use the `<a> and </a>` tags in this exercise. Inside the tag <a> you need to use a href attribute that specifies which page will be loaded when the link is clicked.

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

    <!-- Link to the second page -->
    <p><a href="another_page.html">Go to the other page.</a></p>

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

### PAGE 1
![Screenshot (40)](https://github.com/user-attachments/assets/d8b9d33f-2e7f-43e1-8fae-405209db83ce)
### PAGE 2
![Screenshot (41)](https://github.com/user-attachments/assets/0931cc72-ce33-412a-ab30-25f2ebb7a812)

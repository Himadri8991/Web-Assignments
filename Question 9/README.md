# It is possible to use a picture (image) as a link. Modify your page so that the picture that is on your page will also serve as a link that leads to another page

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
    <!-- Make the image a link to another page -->
    <a href="another_page.html" title="Click the image to go to another page">
        <img src="img.png" alt="Sample Image" />
    </a>

</body>
</html>

```

![Screenshot (43)](https://github.com/user-attachments/assets/78d0a379-9c7b-46f9-bad4-11fa086bd6f0)

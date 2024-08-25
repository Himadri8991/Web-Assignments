# Create an HTML file (e.g. first_page.html) that specifies a page that contains a heading and two paragraphs of text. Use the HTML tags `<h1>, </h1>, <p> and </p>` in this exercise. As the texts in the heading and paragraphs you can use any texts you like.
#  Add an unordered list to this web page. An unordered list should look like the following when it is shown by a browser:
#  An unordered list can be specified with the tags `<ul> and </ul>`.
#  An unordered list typically contains a number of list items that can be specified with tags `<li> and </li>`.
#  After you have created your unordered list, check out what happens when you convert it to an ordered list by replacing the tags `<ul> and </ul>` with `<ol> and </ol>`, respectively.
#  Add an image to your web page. In this exercise you must use the <img> tag. As an image, you can use any .jpg or .png file you find on the Internet.

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

</body>
</html>
```

![Screenshot (39)](https://github.com/user-attachments/assets/abcbd496-f070-4dad-9f01-5b17fdd687e5)

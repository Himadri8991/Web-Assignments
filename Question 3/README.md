# Create a webpage using list tags of HTML.

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML List Tags</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        h1, h2 {
            color: #333;
        }
        ul, ol {
            margin: 20px 0;
        }
        ul {
            list-style-type: disc;
        }
        ol {
            list-style-type: decimal;
        }
        ul ul, ol ol {
            margin-left: 20px;
            list-style-type: circle;
        }
        dt {
            font-weight: bold;
        }
    </style>
</head>
<body>

    <h1>HTML List Tags</h1>

    <h2>Unordered List</h2>
    <ul>
        <li>Item 1</li>
        <li>Item 2
            <ul>
                <li>Subitem 1</li>
                <li>Subitem 2</li>
            </ul>
        </li>
        <li>Item 3</li>
    </ul>

    <h2>Ordered List</h2>
    <ol>
        <li>First item</li>
        <li>Second item
            <ol>
                <li>Subitem A</li>
                <li>Subitem B</li>
            </ol>
        </li>
        <li>Third item</li>
    </ol>

    <h2>Description List</h2>
    <dl>
        <dt>HTML</dt>
        <dd>A markup language for creating web pages.</dd>

        <dt>CSS</dt>
        <dd>A style sheet language used for describing the presentation of a document written in HTML.</dd>

        <dt>JavaScript</dt>
        <dd>A programming language used to make web pages interactive.</dd>
    </dl>

</body>
</html>

```

![Screenshot (36)](https://github.com/user-attachments/assets/f6f9f41c-66f6-449c-ac31-47c445a301d5)

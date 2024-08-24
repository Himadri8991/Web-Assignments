# Create a static web page which defines all text formatting tags of HTML in tabular format.

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Text Formatting Tags</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        table, th, td {
            border: 1px solid black;
        }
        th, td {
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>

    <h1>HTML Text Formatting Tags</h1>

    <table>
        <thead>
            <tr>
                <th>Tag</th>
                <th>Description</th>
                <th>Example</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>&lt;b&gt;</td>
                <td>Makes text bold.</td>
                <td><b>This text is bold.</b></td>
            </tr>
            <tr>
                <td>&lt;strong&gt;</td>
                <td>Makes text strong (important) and bold.</td>
                <td><strong>This text is strong and bold.</strong></td>
            </tr>
            <tr>
                <td>&lt;i&gt;</td>
                <td>Makes text italic.</td>
                <td><i>This text is italic.</i></td>
            </tr>
            <tr>
                <td>&lt;em&gt;</td>
                <td>Makes text emphasized (italic).</td>
                <td><em>This text is emphasized and italic.</em></td>
            </tr>
            <tr>
                <td>&lt;u&gt;</td>
                <td>Underlines text.</td>
                <td><u>This text is underlined.</u></td>
            </tr>
            <tr>
                <td>&lt;mark&gt;</td>
                <td>Highlights text.</td>
                <td><mark>This text is highlighted.</mark></td>
            </tr>
            <tr>
                <td>&lt;small&gt;</td>
                <td>Makes text smaller.</td>
                <td><small>This text is small.</small></td>
            </tr>
            <tr>
                <td>&lt;del&gt;</td>
                <td>Marks text as deleted (strikethrough).</td>
                <td><del>This text is deleted.</del></td>
            </tr>
            <tr>
                <td>&lt;ins&gt;</td>
                <td>Marks text as inserted (underlined).</td>
                <td><ins>This text is inserted.</ins></td>
            </tr>
            <tr>
                <td>&lt;sub&gt;</td>
                <td>Displays text as subscript.</td>
                <td>This is <sub>subscript</sub> text.</td>
            </tr>
            <tr>
                <td>&lt;sup&gt;</td>
                <td>Displays text as superscript.</td>
                <td>This is <sup>superscript</sup> text.</td>
            </tr>
            <tr>
                <td>&lt;q&gt;</td>
                <td>Displays text as a short quotation.</td>
                <td><q>This is a short quotation.</q></td>
            </tr>
            <tr>
                <td>&lt;blockquote&gt;</td>
                <td>Displays text as a blockquote.</td>
                <td><blockquote>This is a blockquote.</blockquote></td>
            </tr>
            <tr>
                <td>&lt;abbr&gt;</td>
                <td>Displays an abbreviation with a title.</td>
                <td><abbr title="Hypertext Markup Language">HTML</abbr></td>
            </tr>
            <tr>
                <td>&lt;cite&gt;</td>
                <td>Displays a citation.</td>
                <td><cite>This is a citation.</cite></td>
            </tr>
            <tr>
                <td>&lt;code&gt;</td>
                <td>Displays text as computer code.</td>
                <td><code>&lt;div&gt;This is code.&lt;/div&gt;</code></td>
            </tr>
            <tr>
                <td>&lt;kbd&gt;</td>
                <td>Displays text as keyboard input.</td>
                <td><kbd>Ctrl + C</kbd></td>
            </tr>
            <tr>
                <td>&lt;pre&gt;</td>
                <td>Displays preformatted text.</td>
                <td><pre>This is preformatted text.</pre></td>
            </tr>
            <tr>
                <td>&lt;samp&gt;</td>
                <td>Displays text as sample output.</td>
                <td><samp>This is sample output.</samp></td>
            </tr>
            <tr>
                <td>&lt;var&gt;</td>
                <td>Displays text as a variable.</td>
                <td><var>x</var> = 5;</td>
            </tr>
        </tbody>
    </table>

</body>
</html>

```
![Create a static web page which defines all text formatting tags of HTML in tabular format](https://github.com/user-attachments/assets/a5fe2c13-ace3-476a-8ada-49b055c9f174)

<!-- HTML & CSS Cheatsheet (max. 100 Zeilen) -->

<!-- HTML Basics -->
<!DOCTYPE html>
<html>
<head>
  <title>Seitentitel</title>
</head>
<body>

<!-- Textelemente -->
<h1>Überschrift</h1>
<p>Absatz</p>
<strong>Fett</strong> <em>Kursiv</em> <br>

<!-- Links & Bilder -->
<a href="https://example.com">Link</a>
<img src="bild.jpg" alt="Beispielbild">

<!-- Listen -->
<ul>
  <li>Liste 1</li>
  <li>Liste 2</li>
</ul>
<ol>
  <li>Nummer 1</li>
  <li>Nummer 2</li>
</ol>

<!-- Tabellen -->
<table>
  <tr><th>Name</th><th>Alter</th></tr>
  <tr><td>Max</td><td>25</td></tr>
</table>

<!-- Formulare -->
<form action="/submit" method="post">
  <input type="text" name="name">
  <input type="submit" value="Senden">
</form>

<dl>
  <dt>&lt;ul&gt;</dt>
  <dd>Erstellt eine ungeordnete Liste mit Bullet-Points</dd>

  <dt>&lt;ol&gt;</dt>
  <dd>Erstellt eine nummerierte Liste</dd>

  <dt>CSS: list-style-type</dt>
  <dd>z. B. square, upper-roman, none</dd>

  <dt>CSS: border</dt>
  <dd>z. B. 1px solid red, mit border-radius für runde Ecken</dd>
</dl>

<dt>.klasse</dt>
<dd>Wendet CSS-Regeln auf alle Elemente mit dieser Klasse an</dd>

<dt>#id</dt>
<dd>Wendet CSS-Regeln auf genau ein Element mit dieser ID an</dd>

<dt>Box Model</dt>
<dd>Besteht aus: content, padding, border, margin</dd>

<dt>float: left;</dt>
<dd>Lässt ein Element nach links fließen (z. B. für Bilder oder Layout)</dd>

<dt>clear: both;</dt>
<dd>Bricht das Umfließen durch float ab</dd>

<!-- HTML-Kommentar -->
<!-- Das ist ein Kommentar -->

<!-- CSS Basics -->
<style>
  /* Kommentar in CSS */
  body {
    background-color: #f2f2f2;
    font-family: Arial;
  }

  h1 {
    color: blue;
    text-align: center;
  }

  p {
    color: gray;
    font-size: 16px;
  }

  a {
    text-decoration: none;
    color: red;
  }

  img {
    width: 200px;
    height: auto;
  }

  ul {
    list-style-type: square;
  }

  table, th, td {
    border: 1px solid black;
    border-collapse: collapse;
    padding: 5px;
  }

  form input[type="text"] {
    border: 1px solid #ccc;
    padding: 5px;
  }

  form input[type="submit"] {
    background-color: green;
    color: white;
  }
</style>

</body>
</html>

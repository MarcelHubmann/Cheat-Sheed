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

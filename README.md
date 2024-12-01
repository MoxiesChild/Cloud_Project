<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Gestion de Bibliothèque</title>
</head>
<body>
    <h1>Ma Bibliothèque</h1>
    <input type="file" id="bookImage" accept="image/*">
    <button onclick="uploadBook()">Ajouter un livre</button>
    <div id="bookList"></div>

    <script src="script.js"></script>
</body>
</html>

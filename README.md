<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script>
    for  (let i = 1; i < 1000; i++) {
        if (i % 2 === 0) {
        document.write(`<h1 style="color: red;">${i} adalah kelipatan genap <br>`);
        }
        else {
        document.write(`<h1 style="color: blue;">${i} adalah kelipatan ganjil <br>`);}
    }
    </script>
</body>
</html>

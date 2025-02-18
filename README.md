<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Colouring Paragraph</title>
    <style>
        p{
            background-color: blue;
            color: white;
        }
        div p:first-child{
            background-color: yellow;
            color: red;
        }
    </style>
</head>
<body>
    <div>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias mollitia sint placeat porro, ratione voluptas repellendus saepe atque ab vitae ipsum quia harum, quisquam possimus cumque id numquam esse provident.
        </p>
        <p> This another para Graph</p>
        <p>This is also another paragraph</p>
    </div>
    <div>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias mollitia sint placeat porro, ratione voluptas repellendus saepe atque ab vitae ipsum quia harum, quisquam possimus cumque id numquam esse provident.
        </p>
        <p> This another para Graph in another div</p>
        <p>This is also another paragraph in another div</p>
    </div>
</body>
</html>

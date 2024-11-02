# HTML Code

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Acme</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Be+Vietnam+Pro:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800&display=swap" rel="stylesheet">
    <style>
        html {
            font-family: 'Be Vietnam Pro', sans-serif;
            scroll-behavior: smooth;
        }

        body {
            margin: 0;
            padding: 0;
            background-color: white;
        }

        .inline-container {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding-inline: 42px;
        }

        nav {
            display: flex;
            gap: 18px;
            align-items: center;
        }

        .--button {
            display: flex;
            padding-inline: 16px;
            padding-block: 8px;
            border: 1px solid #e4e4e4;
        }
    </style>
</head>
<body>
    <header>
        <div class="inline-container">
            <h1>ACME</h1>
            <nav>
                <a href="#">Home</a>
                <a href="#">About</a>
                <a href="#">Shop</a>
                <a href="#">Contact</a>
                <a href="#" class="--button">Login</a>
            </nav>
        </div>
    </header>
</body>
</html>
```


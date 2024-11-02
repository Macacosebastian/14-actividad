# Acme Website

## Descripción

Este es un proyecto de página web simple llamado **Acme**. La página incluye un encabezado con un menú de navegación y está diseñada con estilos CSS utilizando la fuente 'Be Vietnam Pro'.

## Ejemplo de Código

### HTML

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
        /* Aquí puedes agregar tu CSS si es necesario */
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

### CSS

```css
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
```

## Instalación

Para ver este proyecto en tu propio entorno, sigue estos pasos:

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/nombre-del-repositorio.git
   ```

2. Navega al directorio del proyecto:
   ```bash
   cd nombre-del-repositorio
   ```

3. Abre el archivo `index.html` en tu navegador web.

## Uso

Una vez que hayas abierto el archivo `index.html`, verás la página web con el título "ACME" y un menú de navegación que incluye los enlaces a las secciones de Home, About, Shop, Contact, y Login.

## Créditos

Este proyecto fue creado por **Sebastián Marrone Castillo**.

## Licencia

Este proyecto está bajo la licencia MIT.

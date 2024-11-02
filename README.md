<img src="https://c.wallhere.com/photos/60/bc/The_Invincible_Gaming_Series_video_game_art-2289196.jpg!d" alt="image of refference" width="1000">

# Welcome to Mars

### Parte 1

1. Dibuja un **“wireframe”** en una pizarra.
    - Mantenlo en baja fidelidad.

        <img src="https://img.notionusercontent.com/s3/prod-files-secure%2Febfb0089-c563-4b29-ae68-f61069c1c8a5%2F70051b60-9465-42d2-9533-dc34fc5c134d%2F1000154890.jpg/size/w=2000?exp=1730660647&sig=l36yS5WnVVEiW4ZZyV3-WK2hGLvI7fpW00dOB42Fh2M" alt="imagen de wireframe" height="500">

   ## Identifica las áreas de contenidos generales

    - El área de **navegación**
        - menu, logo, botones.
    - Area **Hero**
        - imagen, titular, texto descriotivo, botón
    - Area de **grid para los cards**
        - Sección de cards con su respectiva diagramación
    - Footer
        - con lista de 3 elementos como el about, links y contact

2. Aplica HTML a la estructura.
    - Señala qué etiquetas HTML deberían usarse para cada parte de tu wireframe.
        - **Aŕea de navegación**
            - Aquí irá el contenedor de navegación `*<nav></nav>*`
                - contenedor del logo `*`<div> </div>*`
                - navegación de menú `*<div> </div>*`
                - inserción de imagen logo usando `<img src= “####”>`
                - Hamburguesa para el responsive
                - un tag `<span>` para agregar la marca o nombre de la empresa —> “Mars Tours”
            - Menú responsive
                - Tags `<input>` con classes para hacer referencia en CSS
                - etiqueta `<label>` coo contenedor
            - Menú de navegación
                - Tag `<ul>`para agregar elementos de lista
                - Tag `<li>` para agregar los `*`list items*` que irán como elentos de lista
                - Tag anchor `<a>` para linkear los textos de `<li>`

            - Área Hero
                - Contenedor hero `*<div> </div>*`
                - tags `<img></img>` Para la imagen principal
                - `<h1></h1>` Para el texto titular
                - `<p></p>`: Para el texto descriptivo
                - `<button></button>`: Botón de acción

            - Grid de productos
                - Etiqueta `<div class=”products-grid”>` que será el contenedor principal de las cards
                - Tag `<div class=”product-card”>`que contenera la imagen del card
                - Otro tag al mismo nivel del tag anterior que contendrá el texto titulo del card `<div class=”product-content”>`
                - Tag `<h3>` para el título del card
                - Tag `<p>` para texto descriptivo del card y div de cierre para este primer bloque
                - luego un div de apertura y cierre para crear otro contenedor hijo dentro del principal `<div class=”product-footer”>`
                - Tag `<div>` 1 para calificación por estrellas
                - Tag `<div>` 2 para el precio
                - Tag `<button>` para llamar a la acción al botón
            - Footer
                - Tag `<footer>` como contenedor principal del bloque
                - Tags `<div>` para cada sub bloque como el ‘about’, ‘links’ y ‘contacto’
                - Respectivos tags tales como `<h3>, <ul>, <li>, <a> y <p>` según corresponda

    - Piensa detenidamente cómo se anidarán los elementos HTML.
        - La anidación la expliqué en el paso anterior
3. Escoge tus palabras.
    1. #Nota: No estoy seguro qué es lo que tengo que responder en este bloque
    - Escribe el contenido clave para completar las áreas del contenido del wireframe.
        - Bloque de navegación
        - Bloque Hero
        - Bloque gird o cards
        - Bloque footer
        -
    - No necesitas oraciones completas, pero al menos un plan para cada área.
        - Comenzar el desarrollo implementado la estructura principal base del html y entender qué bloques creo, dónde y cómo enlazo los padres con los hijos
        - agregar meta tags necesarios
        - vincular el CSS
        - luego comiezo por la navegación
        - la sección hero
        - el grid con los cards
        - y el footer
        - Crear el css para modificar colores, tipografías, márgenes, espaciados etc.
        - probar que todo funcione según avance para evitar construir todo de golpe y terminar confundido con un gran código fuente
        - validar que el css y html estén conectados
        - usar imagenes que estén convertidas a modo web para optimizar el uso de datos
        - tener en mente el seo

### Parte 2

1. Define una paleta de 3 a 5 colores.

<img src="https://img.notionusercontent.com/s3/prod-files-secure%2Febfb0089-c563-4b29-ae68-f61069c1c8a5%2Fd60e17de-32f9-44be-8fe0-68da6d835194%2FScreenshot_From_2024-10-30_10-46-37.png/size/w=2000?exp=1730660909&sig=zdgfdxV-CYXUvKNNql59HMRTi9irj8Hv_yAmtDieMlQ">

1. Agrega etiquetas a tu wireframe con los colores elegidos y en dónde irán.

    <img src="https://elegant-effect-ccc.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Febfb0089-c563-4b29-ae68-f61069c1c8a5%2F40a405ca-019a-4c21-ade6-4e6da8754a83%2Fmars-tours-wireframe.jpg?table=block&id=473059d1-fc2f-42bf-b8f2-4181c5600667&spaceId=ebfb0089-c563-4b29-ae68-f61069c1c8a5&width=2000&userId=&cache=v2" height="600">

# Mi Paleta de Colores

<iframe src="./colors.html" style="width: 100%; height: 800px; border: none;"></iframe>

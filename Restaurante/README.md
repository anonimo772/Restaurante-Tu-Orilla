Descripción
Este es un proyecto web para el restaurante "Tu Orilla". La página está enfocada en presentar información sobre el restaurante, qué ofrecemos y cómo contactar con nosotros. El diseño está orientado a ofrecer una experiencia limpia, visualmente atractiva y fácil de usar.

Estructura del Proyecto
El proyecto está compuesto por dos archivos principales:

HTML: Estructura del contenido y uso de etiquetas HTML.

CSS: Diseño y estilo visual.

Proceso de Desarrollo
1. Estructura HTML
Usamos HTML5 para estructurar el contenido de la página de manera semántica. Las principales etiquetas utilizadas fueron:

<header>:
Este elemento se usa para contener el título de la página y el encabezado principal. Se utiliza dentro de un contenedor con bordes redondeados y fondo de color azul para destacar la sección.

html
Copiar
Editar
<header class="titulo">
    <h1>¿Quiénes somos?</h1>
</header>
<section>:
Se utiliza para dividir la página en secciones con contenido relevante. La sección "Nosotros" contiene información detallada sobre el restaurante.

html
Copiar
Editar
<section class="contenedor">
    <p>Texto explicativo sobre el restaurante.</p>
</section>
<strong>:
Dentro de los párrafos, se usa la etiqueta <strong> para resaltar ciertas palabras clave, como el nombre del restaurante y montos importantes.

html
Copiar
Editar
<p><strong>RESTAURANTE TU ORILLA</strong> es un restaurante listo para servirte tus comidas preferidas.</p>
2. Estilos CSS
El archivo estilo_2.css contiene todos los estilos visuales que mejoran la apariencia de la página. Aquí se utilizan propiedades para centrado, bordes redondeados, y efectos visuales.

Centrado del contenido y bordes redondeados:
Se aplica un diseño que hace que el encabezado se muestre centrado, con bordes redondeados y un color de fondo atractivo.

css
Copiar
Editar
header {
    width: 80%;
    max-width: 600px;
    margin: 40px auto;
    text-align: center;
    border-radius: 20px;
    background-color: rgb(68, 0, 255);
    padding: 30px;
    color: white;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
}
Estilo de la sección de contenido:
Se da un estilo a la sección "Nosotros", con un fondo claro, bordes redondeados y una sombra ligera para darle un toque moderno.

css
Copiar
Editar
.nosotros {
    background-color: #eafbea;
    padding: 30px;
    margin: 40px auto;
    max-width: 800px;
    border-left: 6px solid #3cb371;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}
3. Responsive Design
Se utiliza un diseño adaptable para asegurar que la página se vea bien en diferentes dispositivos (móviles, tabletas, escritorios). Esto se logra utilizando @media en el CSS.

css
Copiar
Editar
@media screen and (max-width: 600px) {
    header.titulo h1 {
        font-size: 2em;
    }

    .nosotros {
        padding: 20px;
        margin: 20px;
    }

    .nosotros p {
        font-size: 1em;
    }
}
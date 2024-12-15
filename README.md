# Proyecto Final: Sitio web de la empresa STARBUCKS (Uso académico)

## Descripción
El siguiente archivo, presenta un marco completo sobre el proyecto final que se desarrollará en el módulo II del Curso de Font-End impartido en Campus DEV.F. El producto final que se entrega es un sitio web que tenga (lo más cercano posible) un parecido al sitio diseñado por **STARBUCKS**, es importante recalcar que **este trabajo no busca usan la información e imágenes de la empresa para fines de lucro, solo es con el fin de aprendizaje de los elementos, propiedades y etiquetas empleadas en la creación de sitios web.**

## 🎯 Objetivo principal
El objetivo del proyecto es crear, estilizar y asemejar lo más posible un sitio web con estructura HTML, al realizado por la compañía **Starbucks**, para lo cual se emplearán los conocimientos adquiridos en **módulo I: Introducción a la programación** y se complementarán con el aprendizaje del **módulo II: CSS**, lo cuál le dara a nuestro sitio una mejor apariencia.

## Objetivos Específicos
- Escribir de manera estructurada los archivos HTML, para una fácil comprension de los archivos.
- Emplear la semántica de HTML para una mejor organización de la información.
- Crear uno o varios archivos **.css**, que permitan controlar de forma eficaz el diseño del sitio web.
- Usar la herramienta de IA **ChatGPT** como un complemento en la resolución de dificultades presentes en el trabajo.
- Escribir un buen README, que describa de forma simple, comprensible y ordena el desarrollo del proyecto.

## 🛠️ Herramientas empleadas

- **Visual Studio Code** (IDE para la escritura de los archivos **.html** y **.css**)
- **GIT** (herramienta para enlazar repositorios locales con centrales)
- **GitHub** (sitio donde se ubica el repositorio central del proyecto)
- **HTML** (como lenguaje de marcado para la creación del sitio web).
- **CSS** (para el diseño y estilo del sitio).

### Comentarios y notas
- Los nombres de los commits, estan en inglés  (no 100% correctos en escritura), para práctica del idioma, además de que en muchas empresas usan este idioma.
- Todas las imágenes y links que contengan el sitio web diseñado son propiedad de Starbucks.
- Se crearon distintos archivos **.css** para las partes principales del sitio web.
- Se agregaron comentarios en los archivos de HTML y CSS, para distribuir y organizar la estructura del código.

## Contenido

### I. CSS (Cascading Style Sheets)
#### I.1. Definición
CSS (Cascading Style Sheets) es un lenguaje que define el estilo y diseño de una página web, permitiendo agregar colores, fuentes, espacios y otros elementos visuales. Su principal función es separar el contenido HTML de la presentación visual, facilitando modificaciones de diseño sin alterar la estructura del contenido.

Además, CSS permite crear diseños responsivos, adaptando la apariencia de la página a distintos tamaños de pantalla, desde computadoras hasta dispositivos móviles.<br>

#### I.2. Estructura básica de CSS

La escritura en CSS se hace a partir de reglas, como se muestra en la figura. <br>

<img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXduKdev8HgKZCCzxzp7ESo3FhgWOe39whKnx4b1JT1lHr6o78UBrNSczWeuv-Yav47NpPuz0NZIGaRfwHFUkOjbK5uRn7Fpn2cj555N8a2qT0ckKgui1cArcH0vYw3HaGkRzXr_a__8U8VQu3OmCGCTYLOh?key=9nviClNEFdtYbYgm6NMrXA" width="400px"> <br>
*Estructura básica de una regla en CSS. Derechos de Campus DEV.F* <br>

Una regla CSS completa incluye varias partes:

- **Selector**: Define el elemento HTML al que se aplicará el estilo *(por ejemplo, <**p**>)*.
- **Declaración**: Especifica qué propiedad se modificará *(por ejemplo, color: red;)*.
- **Propiedades**: Son las características que puedes modificar de un elemento *(como color)*.
- **Valor de la propiedad**: Determina el aspecto específico de la propiedad *(por ejemplo, red)*.

**Sintaxis clave**:

- Las declaraciones van entre llaves **{}**.
- Propiedad y valor se separan con dos puntos **:**.
- Las declaraciones múltiples se separan con punto y coma **;**.

### II.Selectores y propiedades empleados
#### II.1 Selectores
Los selectores en CSS se utilizan para seleccionar y aplicar estilos a elementos específicos en un documento HTML. A continuación se enlistan los selectores más comunes:

1. **Selector Universal (*)**: Selecciona todos los elementos del documento.
2. **Selector de Tipo (elemento)**: Selecciona todos los elementos de un tipo específico (como h1, p, div, section).
3. **Selector de Clase (.nombreClase)**: Selecciona todos los elementos con una clase específica.
4. **Selector de ID (#nombreID)**: Selecciona un elemento único con un identificador específico.
5. **Selector de Atributo ([atributo])**: Selecciona elementos con un atributo específico.
6. **Selectores Combinados**
   - **Selector de Descendientes (elemento elemento)**: Selecciona elementos dentro de un contenedor.
   - **Selector de Hijo Directo (elemento > elemento)**: Selecciona solo hijos directos.
   - **Selector General de Hermanos (elemento ~ elemento)**: Selecciona todos los hermanos que coincidan.
7. **Pseudoclases**
   - **Estado (:hover, :focus, :active)**: Aplica estilos basados en interacciones del usuario.
   - **Posición (:first-child, :last-child, :nth-child(n))**: Selecciona elementos según su posición en un contenedor.
8. **Pseudoelementos**
   - **::before y ::after**: Insertan contenido antes o después de un elemento.

#### II.2 Propiedades básicas de CSS
Las propiedades de CSS controlan los estilos de los elementos. Estas propiedades pueden clasificarse en varias categorías:

1. **Propiedades de Texto**
   - *color*: Define el color del texto.
   - *font-size*: Tamaño de la fuente.
   - *font-family*: Tipo de fuente.
   - *text-align*: Alineación del texto (left, right, center, justify).
   - *line-height*: Altura de las líneas.
2. **Propiedades de Fondo**
   - *background-color*: Color de fondo.
   - *background-image*: Imagen de fondo.
   - *background-size*: Tamaño del fondo (cover, contain).
   - *background-position*: Posición del fondo.
3. **Propiedades de Caja (Box Model)**
   - *margin*: Espaciado externo.
   - *padding*: Espaciado interno.
   - *border*: Bordes de un elemento.
   - *width* y *height*: Dimensiones de un elemento.
4. **Propiedades de Posicionamiento**
   - *position*: Define la posición (static, relative, absolute, fixed, sticky).
   - *top, right, bottom, left*: Posición relativa al contenedor.
   - *z-index*: Define la profundidad de los elementos.
5. **Propiedades de Flexbox y Grid**
   - *display*: Define el modelo de caja (flex, grid, etc.).
   - *justify-content*: Alineación horizontal en flexbox o grid.
   - *align-items*: Alineación vertical.
   - *grid-template-columns*: Definir columnas en Grid.
   - *grid-template-rows*: Definir renglones en Grid.
6. **Propiedades de Animación y Transición**
   - *transition*: Cambios suaves entre estados.
   - *animation*: Define animaciones
#### **Clasificación General de las Propiedades de CSS**
1. **Texto**: color, font-size, text-align.
2. **Fondo**: background-color, background-image.
3. **Caja**: margin, padding, border.
4. **Posicionamiento**: position, z-index.
5. **Modelo de Diseño**: display, grid-template-rows, flex-direction.
6. **Animación**: transition, animation.

### III.Historial de commits
#### III.1 Lección 1
- [**Styling navbar and completing sections**](https://github.com/SergioRamz02/Starbucks_home_page/commit/b4127d4276b449144d551b0f2a6cc65f918c4d75)

#### III.2 Lección 2
- [**Styling home page, load project 2**](https://github.com/SergioRamz02/Starbucks_home_page/commit/36b3e168666493dd6a49fee7cb4c2a6e71ba77c5)

#### III.3 Lección 3
- [**Starting to style rewards (project3)**](https://github.com/SergioRamz02/Starbucks_home_page/commit/1ddc05fa183edeb43c7040e453e31bff4b76d0e3)

#### III.4 Lección 4
- [**Project 4 (Rewards completed)**](https://github.com/SergioRamz02/Starbucks_home_page/commit/8bd599bbbd1e490fc21d15e52e9cbb548fafbccd)

#### III.5 Lección 5
- [**Project 5 completed**](https://github.com/SergioRamz02/Starbucks_home_page/commit/f94e72c0f32074619953bd69dfde1285251d6076)

#### III.6 Lección 6
- [**Project 6: Responsive Design**](https://github.com/SergioRamz02/Starbucks_home_page/commit/93854f2922d6c2770c70cdee3622a114b16f22f2)

#### III.7 Lección 7
- [**Project 7 completed**](https://github.com/SergioRamz02/Starbucks_home_page/commit/c1d9c12c792408140136cec7a577c7931b5bbe2e)

#### III.8 Lección 8
- [**Final Project completed (Project 8)**](https://github.com/SergioRamz02/Starbucks_home_page/commit/8fede513e167dba4f27e7af57c1161925ff622a6)

### IV.Etapas del proyecto

### Lección 1: Introducción a CSS (Inicio de Home Page de Starbucks)

#### **Código HTML**

<img src="https://i.postimg.cc/Kjk2KZDb/Lecci-n-1-html.jpg" width="100%">

#### **Estructura CSS**

<img src="https://i.postimg.cc/HWRJ6nKQ/lecci-n-1-css.jpg" width="100%">

### Lección 2: Propiedades básicas de CSS (Home Page completa)

#### **Código HTML**

<img src="https://i.postimg.cc/59Yq36pV/Lecci-n-2-html.jpg" width="100%">

#### **Estructura CSS**

<img src="https://i.postimg.cc/0Q9FS77P/lecci-n-2-css.jpg" width="100%">

### Lección 3: Herencia en CSS (Inicio del Apartado de Rewards)

#### **Código HTML**

<img src="https://i.postimg.cc/YSzytjZV/lecci-n-3-html.jpg" width="100%">

#### **Estructura CSS**

<img src="https://i.postimg.cc/RVJsNg2w/lecci-n-3-css.jpg" width="100%">

### Lección 4: Introducción a Flexbox (Apartado de Rewards Completo)

#### **Código HTML**

<img src="https://i.postimg.cc/Df9DdVrx/lecci-n-4-html.jpg" width="100%">

#### **Estructura CSS**

<img src="https://i.postimg.cc/Wz2rm11B/lecci-n-4-css.jpg" width="100%">

### Lección 5: Alineación con Flexbox (Apartado de Menú Completo)

#### **Código HTML**

<img src="https://i.postimg.cc/2yGZ6NrC/lecci-n-5-html.jpg" width="100%">

#### **Estructura CSS**

<img src="https://i.postimg.cc/pL9jJ7PL/lecci-n-5-css.jpg" width="100%">

### Lección 6: Position con CSS (Diseño Responsivo de los Apartados de Menú, Rewards y Home Page)

#### **Diseño Responsivo de Home y Menú**

<img src="https://i.postimg.cc/j2KYqGSq/lecci-n-6-css1.jpg" width="100%">

#### **Diseño Responsivo de Rewards**

<img src="https://i.postimg.cc/VLdDrK0z/lecci-n-6-css2.jpg" width="100%">

### Lección 7: Estilos Responsivos (Apartados de Iniciar Sesión y Únete, así como su Diseño Responsivo)

#### **Apartado de Iniciar Sesión (HTML)**

<img src="https://i.postimg.cc/JzhD4FsQ/lecci-n-7-ingresar.jpg" width="100%">

#### **Apartado de Únete (HTML)**

<img src="https://i.postimg.cc/CLhdm2sV/lecci-n-7-unete.jpg" width="100%">

#### **Estructura CSS**

<img src="https://i.postimg.cc/fbZcKCyt/lecci-n-7-css.jpg" width="100%">

#### **Diseño Responsivo**

<img src="https://i.postimg.cc/VvSZ8gjs/lecci-n-7-desing.jpg" width="100%">

### Lección 8: Proyecto final (Sitio Web Completo)

#### **Home Page**

<img src="https://i.postimg.cc/Sx24d0jR/Home-starbucks.jpg" width="100%">

#### **Menú**

<img src="https://i.postimg.cc/TwGXTp05/menu.jpg" width="100%">

#### **Rewards**

<img src="https://i.postimg.cc/tgQKzYLv/rewards.jpg" width="100%">

#### **Iniciar Sesión**

<img src="https://i.postimg.cc/C5Qtn1GN/Iniciar-sesion.jpg" width="100%">

#### **Únete**

<img src="https://i.postimg.cc/VNWVB495/unete.jpg" width="100%">

## Conclusión
A lo largo de este módulo, se adquirieron conocimientos teóricos y prácticos sobre el lenguaje **CSS**, el cual permite mejorar el estilo y diseño de un sitio web, haciendo que sea más atractivo tanto en el texto como en la organización y distribución del contenido. Para reforzar el aprendizaje en el uso de **CSS**, se desarrolló un proyecto que consistió en crear un duplicado lo más fiel posible al sitio web de **Starbucks**, replicando tanto su contenido como su diseño visual.

Durante el desarrollo y finalización de este trabajo, se evidenció lo complejo que puede resultar construir sitios web con diseños atractivos. Además, se destacó la importancia de ampliar nuestras expectativas y entender las necesidades y preferencias del cliente respecto al servicio que ofrecemos, ya que esto influye directamente en el éxito del sitio web.

Por último, se emplearon **media queries** para implementar un diseño responsivo, adaptable y agradable en distintos dispositivos electrónicos, atendiendo las demandas tecnológicas actuales.

## Agradecimientos
Quiero agradecer al *Sensei **Carlos Ivan García Fouregat*** por su tiempo, dedicación y enseña durante los módulos de este curso, además de que sus clases siempre fueron muy didácticas. También, a **DEV.F** y **Becalos Tech Challenge**, por esta beca y por la gran oportunidad de adquirir nuevos conocimientos y habilidades.

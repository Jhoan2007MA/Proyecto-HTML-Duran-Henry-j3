# 📄 Hoja de presentacion- Henry Jhoan Durán Peña

Este proyecto es una **página web personal tipo CV (Currículum Vitae)** desarrollada en **HTML y CSS**, con el objetivo de mostrar información personal, académica, laboral y de contacto de manera clara y organizada.  

## 🚀 Características
- Diseño en **3 columnas**:
  - **Columna 1**: Información personal, contacto y redes sociales.  
  - **Columna 2**: Formación académica, proyectos y experiencia laboral.  
  - **Columna 3**: Conocimientos técnicos, idiomas y video de presentación.  
- Estilo responsivo gracias al uso de `meta viewport`.  
- Imagen de perfil incluida.  
- Secciones organizadas y fáciles de leer.  

## 🛠️ Tecnologías utilizadas
- **HTML5** para la estructura del CV.  
- **CSS3** (archivo externo `css/style.css`) para el diseño y estilo visual.  

## 🏷️ Explicación de las etiquetas usadas en `index.html`


### 🔹 Contenido del cuerpo
- `<body>` → Contiene todo el contenido visible en la página.  
- `<div>` → Crea divisiones o contenedores. Se usó para organizar la **estructura en columnas**.  
- `<div class="container">` → Contenedor principal de toda la página.  
- `<div class="column">` → Representa cada columna del CV.  
- `<div class="section">` → Agrupa una sección dentro de cada columna (ej: información personal, proyectos, idiomas).  

### 🔹 Información personal y contacto
- `<img src="..." alt="avatar" class="avatar">` → Inserta una imagen de perfil (avatar).  
- `<h3>` → Encabezados para títulos de sección (ej: “Información personal”, “Idiomas”).  
- `<ul>` → Lista no ordenada, usada para listar datos personales, académicos, etc.  
- `<li>` → Cada elemento dentro de la lista (ej: nombre, correo, idioma).  
- `<strong>` → Resalta en **negrita** palabras clave (ej: “Nombre:”, “Email:”).  

### 🔹 Información académica, proyectos y experiencia
- Estructura repetida con `<ul>` y `<li>` para mostrar educación, experiencia y proyectos.  
- Se usaron **placeholders** para datos que aún no se completaron.  

### 🔹 Conocimientos e idiomas
- Nuevamente `<ul>` y `<li>` para detallar stacks, nivel de conocimientos e idiomas.  

### 🔹 Video de presentación
- `<video src=""></video>` → Etiqueta para insertar un **video** de presentación.

## 🎨 Estilos con `style.css`
El CSS define el diseño visual. Sus funciones principales son:  
- **Reset**: quitar márgenes/paddings por defecto.  
- **Body**: aplicar fondo y fuente.  
- **.container**: definir el diseño en **flexbox** para mostrar las columnas.  
- **.column**: dar color de fondo blanco, sombras y bordes redondeados.  
- **.section h3**: títulos de sección con color azul y línea inferior.  
- **.avatar**: imagen circular con borde azul.  
- **.video**: caja de fondo gris claro para el video de presentación. 
 
 Desarrollado por : Henry Jhoan Duran Peña j-3
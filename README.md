# 🏋️‍♂️ Sitio Web de Gimnasio - Proyecto de Programacion y Servicios Web

Este es un sitio web para un gimnasio ficticio, desarrollado como trabajo practico utilizando unicamente **HTML** y **CSS**, con un poco de **JavaScript**. Esta diseñado para ser moderno, funcional y atractivo.

---

## 📂 Estructura del sitio

- **Header:** El header para todas las paginas debe contener enlaces hacia las demas paginas, para permitir el cambio entre las distintas paginas, solo se permite la redireccion a traves de navbar, debe incluir un mega-menu desplegable.
- **Footer:** Para el footer solo se necesita una parte para poder suscribirse a un newsletter, redes sociales, y otra parte donde habra un mapa embebido, el mapa apunta hacia la facultad de ingenieria.
- **Home (Inicio):** Debe tener secciones, una con un video motivacional con una frase por encima del video, una donde aparecen las clases destacadas, un contador contador con un poco de animacion y una seccion donde van los testimonios de socios con un diseño de carrusel.
- **Clases:** Debe tener tarjetas de clases, estas tienen un filtro por tipo (musculacion, yoga, crossfit, spinning), tarjetas informativas, sin imagenes, galeria tipo masonry y tabla de horarios semanales.
- **Entrenadores:** Incluye tarjetas con efecto flip, estas tarjetas tienen la foto de los entrenadores, barras de habilidades animadas, sistema de rating con estrellas animadas.
- **Contacto:** Formulario avanzado con validacion en tiempo real, al enviar debe aparecer un spinner y luego de unos seguhndos una ventana emergente confirmando el envio.
- **Precios:** Comparador de planes con tabla interactiva, toggle mensual/semestral/anual, tooltips explicativos.
- **Blog:** Contiene posts publicados por usuarios, tiene scroll reveal utilizando javascript y css, tambien tiene una seccion de comentarios de usuarios anonimos, con imagen de avatar generada en css.

---

## 🎨 Decisiones de diseño

- **Colores calidos y modernos** (naranja, negro, blanco) para transmitir energía y dinamismo.
- **Diseño parcialmente responsivo**, usando Flexbox y Grid adaptado a distintos dispositivos.
- **Modo oscuro** con toggle en el borde inferior derecho de la pantalla, que sigue al usuario donde sea que haga scroll, tiene iconos de sol y luna para poder cambiar entre los modos, este esta en todas las paginas y la preferencia elegida se guarda en el cache. Fue realizado con javascript y css.
- **Interaccion visual**, utiliza efectos hover, animaciones suaves y transiciones CSS, mediante la utilizacion de keyframes.
- **Accesibilidad** estructura facil de entender y usar.

---

## 🛠️ Tecnologías utilizadas

- **HTML5**
- **CSS3**
- **JavaScript** solo para el scroll reveal, y el modo oscuro
- **GitHub Pages** para publicación del sitio

---

## 💡 Funcionalidades destacadas

✅ Mega-menu desplegable con solo css  
✅ Mapa embebido en el footer  
-- Pagina Principal  
✅ Pagina principal con un video motivacional con una frase por encima  
✅ Tarjetas de clases destacadas con efecto hover  
✅ Contador animado al cargar la pagina con solo css  
✅ Seccion de testimonios con un carrusel que va mostrando los distintos comentarios  
-- Pagina de clases  
✅ Sistema de filtrado con css para poder mostrar solamente clases especificas  
✅ Galeria de fotos con estilo masonry utilizando solamente css, tiene efecto lightbox para poder mostrar la imagen completa al seleccionarla  
✅ Tabla de horarios semanales responsiva  
-- Pagina de entrenadores  
✅ Tarjetas con imagenes y un poco de informacion sobre los entrenadores  
✅ Efecto flip en las tarjetas  
✅ En la parte trasera de la tarjeta tiene barras de estadisticas animadas con un rating de estrellas utilizando solo css  
-- Pagina de formulario de contacto  
✅ Es un formulario que no deja enviar si no se completan los datos correctamente  
✅ Tiene validacion por parte del usuario  
✅ Al enviar el formulario, aparece un spinner de carga  
✅ Luego de unos segundos aparece el modal de confirmacion, indicando que se envio la consulta  
-- Pagina de precios  
✅ Contiene botones para cambiar entre los tipos de plan en mensual, semestral y anual  
✅ Tiene planes en 3 niveles incluyendo distintos servicios  
✅ Los planes tienen efecto hover y un marco que cambia dependiendo del tiempo del plan  
✅ Incluye tooltips en los servicios que ofrece cada plan  
-- Pagina de blog  
✅ Contiene distintos posts dejados por usuarios  
✅ Estos contienen efecto de scroll reveal  
✅ Filtrado de blogs por tipos seleccionados utilziando solamente css  
✅ Tiene seccion de comentarios  
✅ Los avatares de los usuarios que dejaron comentario son hechos con css  
-- Modo oscuro  
✅ Intercambia entre modo oscuro y normal con un toggle fijo en la parte inferior derecha  
✅ Esta presente en todas las paginas  
✅ Guarda la seleccion utilizada por ultima vez en la cache local  
✅ Realizado con javascript minimo  

---

## 🌐 Demo

📍 [Ver el sitio en GitHub Pages](https://floresrodrigo.github.io)

---

## ✍️ Autor

Desarrollado por Flores Rodrigo.

---
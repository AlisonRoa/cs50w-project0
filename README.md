# cs50w-project0
 Web50 Project0 - Portafolio Personal: [cs50w-project0]  Repositorio de GitHub para el curso Web50. Proyecto1: página web personal en HTML, CSS y SCSS. Uso de Git para historial de cambios y commits. Registra el progreso y evolución del HomePage, demostrando dominio de las herramientas del curso.

# Explicación del Proyecto

Se inicio creando un menu lateral con SCSS que contiene las 4 entradas del project (Proyectos, Certificados, Musica, Videojuegos) con sus respectivos iconoes en él, en la parte superior, se contiene un mesaje y por debajo de este, un icono de imagen de perfil junto a mi nombre que al presionar click se activa un hipervinculo al "index.html".

Se creo un estilo de menú junto a las dimensiones del "main-container" para todas las entradas de las paginas que se vincularon con las entradas de las demás páginas con la etiqueta "link".

De manera similar se siguió la misma estructura para crear el "footer", que es una serie de "path" con vínculos a redes sociales personales.

Se uso anidamiento de scss con menú, footer y puzzle. Al ejecutar estos archivos se generó el archivo ".css" que se vincularía a las páginas y el archivo ".map.css".

A cada entrada se le creo un archivo ".css" respectivamente para la edición de las entradas. 

La carpeta img, contiene todas las imagenes del proyecto exceptuando las imagenes de los certificados y las tarjetas del "index" que son insertadas por medios de vínculos.

Una vez listo el menu y el footer de "index.html" se le agrego una "Tooltips on links" de bootstraps junto con un "Bootstrap grid layout" que funcionan como columnas para añadir 4 "Cards" de "Bootstrap".

Luego se creo el contenido de "music.html", en esta entrada se utilizo el "Reproductor de audio" de Bootstrap y una tabla que contenia filas con mis musicas.

A "puzzle.html" equivalente a "Proyectos" en el sitio se le asigno "puzzle" debido al icono que está puesto a su par. En esta entrada utilizando "Columns Layout" se mostrarón 4 tarjetas con especificaciones, imagen y vinculos a codigos de mis proyectos.

Con "certificados.html", se uso un "Carousel" de "Bootstrap" que mostrara mediante vinculos los certificados obtenidos por mi.

Por ultimo "games.html", contiene una serie de "Cards" que contienen mis juegos favoritos y las horas jugadas acomodados de forma dinámica con un "Columns Layout Horizontal Alignment".

# Requisitos para Project0

* Tu sitio debe contener al menos 4 diferentes páginas .html, y debe ser posible entrar desde una página hasta otra siguiendo uno o más hipervínculos.

*Mi proyecto posee el index, más certificados, proyectos, musica y videojuegos cumple con 5 paginas diferentes, también en el menu lateral todas las páginas están correctamente conectadas por hipervínculos*

* Tu sitio debe contener al menos una lista (ordenada o desordenada), al menos una tabla y al menos una imagen.

*En "puzzle" simulando botones con diseño de etiquetas/"tags" se utilizo una lista desordenada que al presionar envía a vinculos en la red. En "music" hay una tabla con 9 filas t 3 columnas. En "puzzle", "certificados", "index" y el menú hay imagenes alrededor de unas 26 imagenes*

* Tu sitio debe contener al menos una hoja de estilos.

*Mi sitio contiene en total 10 hojas de estilos css y scss*

* Tu sitio debe usar al menos 5 diferentes propiedades CSS, y al menos 5 selectores diferentes. Debes usar el selector de #id y el de .class al menos una vez.

*Estas condiciones se cumplen en las hojas de estilos pero sobretodo en "style.css" y "menu.scss"*

* Tu sitio debe contener al menos un selector responsivo @media query, que debe aplicarse a pantallas más pequeñas.

*En el "menu.css" se cuenta con una de estas @media que se encuentran en mi sitio, funciona para darole un estilo responsivo al hacer la ventana más pequeña*

* Debes usar bootstrap 4 en tu sitio, para utilizar al menos un componente de bootstrap, y al menos dos columnas de bootstrap usando su grid layout.

*Según explique mi proyecto anteriormente, se puede apreciar que el contenido de mis paginas es en su mayoria Bootstrap personalizado debido a las variaciones que hice para adaptarlo al proyecto*

* Tus hojas de estilo deben contener al menos una variable SCSS, al menos un ejemplo de anidamiento SCSS y al menos un uso de herencia SCSS.

*En "menu.scss", "footer.scss" y "puzzle.scss" se encuentran una serie de variables, anidamiento y herencia*

* En README.md, incluye una breve descripción de tu proyecto, opcionalmente, que contiene cada archivo, y cualquier otra información adicional para el staff.

*Se ha redactado este archivo cuidadosemente para corregir este requisito con la descripción inicial de proyectos, el desmenusar cada archivo*
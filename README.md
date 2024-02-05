
Se crearon 6 archivos css para la maquetacion de las diferentes paginas en el index principal





                    ** LAS FUNCIONES DEL HEADER Y EL FOOTER SE REPITEN EN TODOS LOS ARCHIVOS CSS *

                        Consideremos los archivos style.css y gamepage.css como los principales ya que de estos se reutilizaron funciones





**style.css Utiliza las siguientes funciones ** :


    Reset de estilos: Elimina los márgenes, subrayados y estilos de lista predeterminados, y establece una fuente predeterminada para todos los elementos.


    Estilo del cuerpo (body): Define el color de fondo del cuerpo del documento HTML.


    Estilo de los enlaces (a): Quita la decoración de subrayado predeterminada de los enlaces.


    Estilo del encabezado (header): Define el estilo del encabezado de la página, como el color de fondo, el tamaño y el espaciado.

    Estilo de la barra de navegación (header nav ul): Define el estilo de la lista de elementos de navegación en el encabezado, como la alineación y el espaciado.

    Estilo de los elementos de la barra de navegación (header nav ul li a): Define el estilo de los elementos de la lista de navegación, como el tamaño de fuente, el color y el espaciado.

    Estilo de los iconos de los lanzadores (launchers img): Establece el tamaño y el espaciado de los iconos de los lanzadores de juegos.

    Estilo de la sección de novedades de juegos (novedadesJuegos): Define el diseño de la sección que muestra los nuevos juegos, como la disposición en cuadrícula y el espaciado.

    Media Queries: Se utilizan para ajustar el diseño en dispositivos con diferentes tamaños de pantalla. En este caso, se ajusta el padding del encabezado para pantallas más pequeñas y el diseño de la sección de novedades de juegos para pantallas más grandes.


    Estilo del logotipo en el encabezado (header .logo1): Define el estilo del logotipo en el encabezado, como el cursor y el tamaño de la imagen.

    Estilo del menú principal (mainMenu): Define el estilo del menú principal, como la alineación de los elementos, el color de fondo y el espaciado.

    Estilo del contenedor de la frase 1 (frase1): Define el estilo del contenedor que muestra la frase 1, como el color del texto, la alineación y el margen.

    Estilo del contenedor del banner (banner): Define el estilo del contenedor del banner, como la alineación de elementos y el tamaño máximo.

    Estilo del contenedor de la frase 2 (frase2): Define el estilo del contenedor que muestra la frase 2, como el color del texto, el tamaño de fuente y el espaciado.

    Estilo del contenedor de los juegos destacados (showContainer): Define el estilo del contenedor que muestra los juegos destacados, como el tamaño máximo y el espaciado.

    Estilo de los elementos en el escaparate de juegos (showcase1): Define el estilo de los elementos individuales en el escaparate de juegos, como el tamaño, la transición al pasar el ratón sobre ellos y el espaciado.

    Estilo del botón "Mirar" (botonMirar): Define el estilo del botón "Mirar", como el tamaño, el color de fondo, el color del texto y el espaciado.

    Estilo del pie de página (gameFooter): Define el estilo del pie de página, como la disposición de los elementos en cuadrícula, el color de fondo y el espaciado.

    Estilo de las secciones del pie de página (seccion): Define el estilo de las secciones individuales del pie de página, como el espaciado y la transición de color al pasar el ratón sobre ellas.

    Estilo de las redes sociales (redes): Define el estilo de los iconos de las redes sociales, como el tamaño, el color de fondo y la transición al pasar el ratón sobre ellos.




** LAS FUNCIONES DEL HEADER Y EL FOOTER SE REPITEN EN TODOS LOS ARCHIVOS CSS *



**gamepage.css Utiliza las siguientes funciones ** :


    Reset de estilos: Establece márgenes, decoración de texto y estilo de lista a cero para todos los elementos, y hace que el modelo de caja sea border-box.

    Estilo de los enlaces: Elimina la decoración de subrayado predeterminada de los enlaces.

    Estilo del menú principal: Define el estilo del menú principal, como la alineación de los elementos, el color de fondo y el espaciado.

    Estilo de las opciones de la barra de navegación: Define el estilo de los elementos de la lista de navegación, como el tamaño de fuente, el color y el espaciado, y establece una transición de color al pasar el ratón sobre ellos.

    Estilo del botón de menú desplegable: Define el estilo del botón de menú desplegable, como el cursor y la visualización.

    Estilo del separador: Define el estilo del separador, como el color de fondo y el espaciado.


    Estilo del contenedor de imágenes: Define el estilo del contenedor que muestra las imágenes del juego, como el tamaño máximo, el margen y el relleno.


    Estilo de las miniaturas de imágenes: Define el estilo de las miniaturas de imágenes, como la disposición de flexbox y el tamaño.


    Estilo de las imágenes del juego: Define el estilo de las imágenes del juego, como el tamaño, el borde y el radio de borde.


    Estilo de la información del juego: Define el estilo de la información del juego, como el tamaño y el margen.


    Estilo de las reseñas: Define el estilo de las reseñas, como el tamaño de fuente, el color y el margen.


    Estilo de los precios del juego: Define el estilo de los precios del juego, como el color de fondo, el relleno, el radio de borde y el color del texto.


    Estilo del botón de compra: Define el estilo del botón de compra, como el color de fondo, el color del texto, el borde, el relleno y el cursor.


    Estilo de las sugerencias de juegos: Define el estilo de las sugerencias de juegos, como el margen superior y el tamaño de fuente.


    Estilo de las sugerencias de juego individuales: Define el estilo de las sugerencias de juego individuales, como el tamaño y el margen.


    Estilo de las redes sociales: Define el estilo de los iconos de las redes sociales, como el tamaño, el color de fondo y la transición al pasar el ratón sobre ellos.

    Media Queries: Ajusta el diseño en dispositivos con diferentes tamaños de pantalla, reorganizando los elementos según sea necesario. Por ejemplo, cambia la disposición de los elementos en la versión móvil para que se vean bien en pantallas más pequeñas.


    Desde este punto, basicamente los demas archivos css usan los mismos atributos que estos, ya que se utilizaron secciones de gamepage y style juntas para construir las demas.
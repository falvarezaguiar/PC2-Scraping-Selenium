# PC2-Scraping-Selenium
Es un proyecto para el Master en Inteligenica Artificial del MBTIT
Herramientas utilizadas Web Scraping, API Rest y Steamlit
De forma autónoma combinamos poryectos de caputra, procesamiento de datos y visualización basados en un sistema o entre dos o más distintos.

Reto1 BeatifulSoup y Streamlit: Capturar estadísticas de equipos de hockey

Reto2 Selenium: Capturar de valor del oro de la web   wwww.inversoro.es/precio-del-oro/precio-oro-hoy/

Reto3 Selenium, BeautifulSoup y Streamlit: El comprador de precios, buscamos un ISBN  del libro "Harry Potter y la piedra filosofal"
y damos los precios consultanod 
Los comparadores de precios <u>es uno de los nichos de mercado más lucrativos en Internet.</u> Dado un producto o servicio a nivel de usuario nos beneficiamos del precio más bajo existente y a nivel de empresa éstas obtienen grandes beneficios gracias a sistemas de referidos o de comisiones por venta realizada.
En esta ocasión vamos a realizar un simple comparador de precios basado en el número ISBN. Un ISBN es un código normalizado internacional para libros (International Standard Book Number). Estos estaban compuestos por 10 dígitos hasta diciembre de 2006 pero, desde enero de 2007, tienen una extensión de 13 dígitos. 
Por ejemplo, el ISBN [9788478884452](https://www.google.es/search?q=9788478884452) (haz click) corresponde al libro "Harry Potter y la piedra filosofal".
Dado que no disponemos de acceso a APIs de las tiendas principales <u>capturaremos el precio a través de técnicas de Web Sraping.</u>
##### Ejercicio 
El objetivo es realizar la consulta de un ISBN, por ejemplo el de "Harry Potter y la Piedra filosofal" en al menos **tres** de las siguientes tiendas propuestas. Captura el primer resultado en EUROS, y devuelve cómo resultado cuál tiene el precio más bajo. 
Crea un sencillo interfaz en Streamlit que pregunte por el ISBN de un número (entre 10 y 13 dígitos) y devuelva como resultado el primer elemento de cada tienda examinada, con el título, la imagen (si la hubiese), el precio y un enlace para hacer click.

Como puntos extra:
* Incluye en la comparativa más de las 3 tiendas propuestas.
* Incluye por texto posteriormente cuál es la diferencia de precio en euros y en porcentaje respecto al valor más bajo detectado para saber cuánto nos estamos ahorrando.
* Crea un diagrama de barras con el precio en cada tienda para representar visualmente el ahorro en precio.

Ejemplo de tiendas propuestas:
- https://www.casadellibro.com/
- https://www.libreriacentral.com/
- https://www.iberlibro.com/
- https://www.amazon.es/
- https://ebay.es
- https://www.elcorteingles.es/

Recuerda que para cada página debes realizar ingeniería inversa, averiguando cómo se comportan las URLs de cada sitio web para hacer una búsqueda directa.

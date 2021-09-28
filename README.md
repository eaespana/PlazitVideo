# PlazitVideo

Curso Frontend Developer donde se evidencia el manejo basicode HTML y CCS.

# ¿Qué son y para qué nos sirven HTML y CSS?

HTML: Es un lenguaje de marcado usado para decirle a tu navegador cómo estructurar las páginas web que visitas. No es un lenguaje de programación.
https://htmlreference.io/
CSS: Es un lenguaje que nos permite crear páginas web con un diseño agradable para los usuarios. Tampoco es un lenguaje de programación.
https://cssreference.io/

DOM, CSSOM, Render Tree y el proceso de renderizado de la Web
DOM: Document Object Model. Es una transformación del código HTML escrito por nosotros a objetos entendibles para el navegador.

CSSOM: así como el DOM para el HTML, EL CSSOM es una representación de objetos de nuestros estilos en CSS.

Render Tree: es la unión entre el DOM y el CSSOM para renderizar todo el código de nuestra página web.

Pasos que sigue el navegador para construir las páginas web:

Procesa el HTML para construir el DOM.
Procesa el CSS para construir el CSSOM.
El DOM se une con el CSSOM para crear el Render Tree.
Se aplican los estilos CSS en el Render Tree.
Se ““pintan”” los nodos en la pantalla para que los usuarios vean el contenido de la página web.

Como el navegador lee el código

1- El navegador transforma el código en bytes

2- teniendo el código en bytes este los transforma en caracteres y este se da cuenta leyendo el meta charset

3- Tokens, este los transforma en elementos html y los ordena

4- Transforma estos en Nodos y estos son los que entiende el y clasifica los objetos y los contenidos

5- El dom es el árbol de los elementos que se forma con todos estos pasos.				

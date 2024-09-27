# Informe Técnico

## Análisis de los modelos de ejecución cliente/servidor






### Cliente

En el lado cliente se usará HTML5, CSS3 y JAVASCRIPT.

- HMTL5: Se elige HTML5 para la estructura y el contenido de la página web. El esqueleto de la página que organiza elementos como 
textos, imágenes, formularios, enlaces, etc...

- CSS3: Usamos CSS para dar estilo y diseño a los elementos HTML. Controla la apariencia visual de la página, incluyendo colores, fuentes, márgenes, alineación y diseño responsivo ( adaptación a diferentes tamaños de pantalla ).

- JavaScript: El lenguaje de programación por exelencia en el lado cliente de una página web. Permite interactividad en la página web. Se usa para crear comportamientos dinámicos como la validación de formularios, control de eventos ( clicks, movimientos de ratón ), manipulación del DOM y comunicación asíncrona con el servidor mediante AJAX.

- AJAX: Permite que las páginas web se actualicen de forma asíncrona mediante el intercambio de datos con un servidor web detrás de la escena. Esto significa que es posible actualizar partes de una página web sin recargar toda la página.
AJAX no es un lenguaje de programación, solo usa una combinación de un objeto XMLHttpRequest incorporado en el navegador para solicitar datos a un servidor web.
Y se utiliza JavaScript y HMTL para mostrar o utilizar estos datos.

AJAX : https://www.w3schools.com/whatis/whatis_ajax.asp


### Servidor

En el lado servidor se utilizará Node.js y el framework Express.js

- Node.js: Es un entorno de ejecución para JavaScript que permite usarlo en el servidor. La ventaja de usar Node.js es que se ejecuta con un hilo (monohilo) con entradas y salidas asíncronas. Un proceso con un bucle que gestiona de forma asíncrona, todos los eventos.

![funcionamiento de node.js](./images/node.png)

- Express.js: Framework que sirve para crear APIs y rutas. Es simple y minimalista, significa que es fácil de usar, tiene una configuración muy simple y proporciona todas las herramientas necesarias para crear un backend.
Te da libertad para elegir los patrones y herramientas, cómo manejar rutas, controladores y la lógica de la aplicación.
Al estar construido en Node.js, aprovecha su arquitectura basada en eventos y asincronía, lo que permite manejar grander volúmenes de manera eficiente sin bloquear el servidor.

### Por qué he elegido estos modelos y no otros.


En el lado cliente se han elegido este modelo de ejecución porque son los principales para hacer una página web y estoy muy familiarizado con HTML5, CSS3 y JavaScript. 

### Uso de Frameworks en el lado cliente.

Existen frameworks para casi todo tipo de lenguajes o tecnologías, se van a repasar los diferentes frameworks existentes y la decisión de por qué no se van a usar frameworks en el lado Front End.

- CSS3: 
    - Bootstrap : Es un framework CSS desarrollado por Twitter en 2010 para estandarizar las herramientas de la compañía. En 2011 se transformó en código abierto. El framework combina CSS y JavaScript para estilizar los elementos en una página HTML. 
    Además de todas las características que ofrece el framework, su principa objetivo es permitir la construcción de sitios web responsive para dispositivos móviles.

    - Foundation: Framework para cualquier dispositivo, medio y accesibilidad, así se definen en su página web. Foundation hace que el diseño responsive sea fácil de realizar en sitios web, apps o incluso emails.
    Igual que bootstrap funcina con CSS y JavaScript haciendo que el maketado resulte mucho mas fácil de implementar.

    - Materialize: Framework de CSS responsivo, robusto y adaptable, donde las bases de diseño las hereda de Google y su estándar de desarrollo Material Design, que es el lenguaje visual que concentra los principios clásicos del bien diseño con la innovación de la tecnología u ciencia moderna para entornos móviles y para internet. 
    Acelera los tiempoos de desarrollo a través de la incorporación de componentes personalizados documentados de manera detallada junto con códigos específicos.

- JavaScript: 
    - React: Desarrollado por Facebook, es una librería de JavaScript de código abierto enfocada a la visualización. Esta tecnología nos permite el desarrollo de interfaces de usuario de forma sencilla. 
    Según una encuesta en StacOverflow, React es el framework más querido y más deseado este último año, además de ser el segundo más usado por detrás de jQuery.

    Fácil de integrar con otros frameworks o bibiliotecas.

    ![Ejemplo React](./images/ejemploReact.png)

    React usa una sintaxis de marcado JSX, hace que la lógica de renderizado sea mas fáciles de crear, mantener y eliminar al ser una extensión de la sintaxis de JavaScript.

    -Angular: Es un framework basado en componentes para crear aplicaciones web escalables, construida sobre TypeScript. 
    Tiene una amplia variedad de características, que incluyen enrutamiento, administración de formularios, comunicación cliente-servidor y mucho más. Su principal objetivo es desarrollar aplicaciones de una sola página. Goo



bootstap: https://rockcontent.com/es/blog/bootstrap/
foundation: https://get.foundation
materialize : https://openwebinars.net/blog/materialize-que-es-ventajas-y-primeros-pasos/
React: https://es.react.dev
Angular: 

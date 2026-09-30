# A1.-JavaScript-y-su-entorno-de-trabajo

JS desde cero en el navegador... antes que REACT.
El objetivo de esta práctica es crear un formulario básico en HTML y JavaScript que permita saludar a un usuario. Publicarlo en un repositorio de GitHub con GitHub Pages. Todo debes documentarlo con un pantallazo en este mismo archivo y personalizarlo con tu tus datos personales.

Por qué REACT
REACT es una biblioteca de JavaScript para construir interfaces de usuario.
Es mantenida por Meta y una comunidad de desarrolladores.
Permite construir componentes reutilizables.
Es ampliamente utilizada en la industria, lo que la hace relevante para desarrolladores web.
Aprender REACT abre oportunidades laborales y mejora las habilidades en desarrollo frontend.
Cuenta con un ecosistema robusto, incluyendo herramientas como Redux para la gestión del estado y React Router para la navegación.
Tiene un rendimiento optimizado gracias a su uso del Virtual DOM.
Se sitúa como uno de los frameworks más populares en la actualidad. State of JS 2023
Por qué JavaScript antes de REACT
REACT está construido sobre JavaScript, por lo que es esencial tener una buena comprensión de este lenguaje antes de aprender REACT.
JavaScript es el lenguaje de programación principal para el desarrollo web frontend.
¿Qué es JavaScript?
JavaScript (JS) es un lenguaje de programación interpretado, ligero y multiplataforma, creado inicialmente para dotar de interactividad a las páginas web. Hoy en día, se utiliza tanto en el desarrollo frontend (navegadores) como en el backend (servidores, gracias a Node.js), aplicaciones móviles, de escritorio y más.

Versiones
ECMAScript es el estándar que define el lenguaje. Las versiones más importantes son:
ES5 (2009): Amplió la compatibilidad y funcionalidades.
ES6/ES2015: Introdujo let/const, arrow functions, clases, módulos, promesas, etc.
Desde 2015, cada año se publica una nueva versión con mejoras y nuevas características.
Potencia
Permite crear desde páginas web dinámicas hasta aplicaciones complejas, videojuegos, servidores, inteligencia artificial y más.
Es asíncrono, flexible y tiene una enorme cantidad de librerías y frameworks (React, Angular, Vue, etc.).
Es esencial para el desarrollo web y uno de los lenguajes más demandados en el mercado laboral.
Parte 1: Instalación y configuración
Instala Visual Studio Code
Descarga e instala VS Code desde code.visualstudio.com.
Parte 2: Primeros pasos con la consola del navegador
Abre tu navegador web (Chrome, Firefox, Edge, etc.).
Accede a cualquier página web y pulsa F12 o Ctrl+Shift+I para abrir las herramientas de desarrollo.
Haz clic en la pestaña "Consola".
Prueba los siguientes comandos uno por uno y observa el resultado:


<img width="720" height="647" alt="Parte 2" src="https://github.com/user-attachments/assets/76d2503d-b9e0-487e-aa97-36b114233911" />

Parte 3: Tu primer archivo HTML + JavaScript
Crea una carpeta llamada 00JSyEntorno dentro de tu espacio de trabajo.
Dentro de esa carpeta, crea un archivo llamado hola.html.
Escribe el siguiente código en hola.html:

<img width="1903" height="976" alt="Parte 3" src="https://github.com/user-attachments/assets/91374ead-6b95-4ddb-86ff-dd7418d72dd6" />

Desde VSCode abre el archivo hola.html en tu navegador.
Observa el resultado en la consola del navegador.

parte 5: formulario HTML + JavaScript
Crea un archivo llamado formulario.html en la misma carpeta 00JSyEntorno.
Crea un archivo llamado formulario.js en la misma carpeta 00JSyEntorno.
Escribe el siguiente código en formulario.html:

<img width="1912" height="976" alt="Parte 5" src="https://github.com/user-attachments/assets/b9d89608-31c4-4bc5-94dd-de70bf583cce" />

Escribe el siguiente código en formulario.js:

<img width="937" height="366" alt="Parte 5_2" src="https://github.com/user-attachments/assets/63cb61c8-73f7-42f7-8b8c-841f71431b0a" />

Desde VSCode abre formulario.html en tu navegador y prueba el formulario.

Parte 6: Preguntas de reflexión

¿Qué hace console.log?

-Muestra mensajes o datos en la consola para comprobar qué está haciendo el código.

¿Qué ocurre si cambias el valor de la variable desde la consola? ¿Se puede?

-Sí se puede si usa let. Si usa const, da error porque su valor es fijo y no se puede modificar.

¿Para qué sirve la consola del navegador en este contexto?

-Para ver errores, probar cosas rápidamente y ver los mensajes del código.

¿Para qué sirve el archivo HTML en este contexto?

-Es la estructura visual de la página web (los botones, textos y elementos que ves en pantalla).

¿Por qué es una buena práctica separar el código JavaScript del HTML?

-Para mantener el código ordenado, limpio y más fácil de arreglar o modificar.

¿Por qué se llama Vanilla JavaScript?

-Porque es el JavaScript puro original, sin librerías ni complementos añadidos.

¿Cuándo se usa JavaScript puro y cuándo frameworks como React?

-JavaScript puro para páginas sencillas; React para aplicaciones web grandes y complejas.

¿Cómo se define una función en JS?

-Se puede escribir como function miFuncion() {} o usando una flecha const miFuncion = () => {}.

Diferencia entre let y const:

-Const se usa para valores que no van a cambiar, y let para variables cuyo valor sí va a cambiar.

¿Se puede evitar el uso de let?

-En el ejemplo del contador no, porque necesitamos que el número cambie (aumente) constantemente.

¿Cuántos eventos hay en el código y para qué sirven?

-Hay 1 evento (click). Sirve para detectar el momento exacto en que el usuario hace clic sobre un botón y activar una acción.

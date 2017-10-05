# 0011203489
//juego en javascript

Este es un pequeño proyecto cuyo objetivo es la creación de un rpg.
Como elementos de dibujo usa la biblioteca p5.js
No pretende nada sofisticado y está orientado principalmente al aprendizaje: su valor principal se derivará de la trama, 
de caracter irónico y ambientada en una universidad.

Actualmente cuenta con:
0) demo.html archivo que ejecuta el juego.
i) demo.js. Dispone la pantalla e inicializa los elementos necesarios, contiene la función draw() que es llamada en bucle por p5.js 
ii)functions.js Contiene las funciones principales utilizadas por demo.js
iii)objects.js Contiene los objetos necesarios para el desarrollo del juego. De momento solo tiene un objeto player.
iv)values.js Contiene los valores que sientan las constantes necesarias para el desarrollo del juego.

El mapa del juego es guardado de momento en un archivo separado, para poder usar con mas facilidad un pequeño script de python que 
emplea pygame para favorecer la creación de mapas.
v)map.js
y el script de python:
vi) mapw.py

Se apreciarán ciertas deficiencias y ausencias que se explican por tratar en un primer momento de crear el elemento funcional más
básico.

¡ADVERTENCIA!

Se verá que los bloques de texturas en ausencia de dibujos propios se cargan llamando a enlaces en internet. Para cargar el personaje
principal ha de bloquearse la política CORS en el navegador. 


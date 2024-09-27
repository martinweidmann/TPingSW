
2b) Tendriamos que crear una carpeta llamada .gitignore, y dentro de la carpeta poner la ruta de los archivos que queremos ignorar
luego ejecutar los comandos de add, commit y push de gitignore

2e) Para seguir GitFlow lo que hacemos es realizar un merge con la rama productiva en este caso Master, y ademas para que los cambios esten tambien en la rama de desarrollo
hacemos un merge con develop

2f) Para poder corregirlo se realiza una rama llamada hotfix la cual se encarga de realizar las correcciones a los distingos errores menores que tenga el release ya en la rama
productiva. Ademas para terminar de introducir el arreglo realizamos un merge con la rama master y la rama develop

2j) Lo que hacemos para seguir GitFlow al realizar un nuevo feature es mergear la rama de la feature realizada con la rama de develop, de la cual se crea una rama de release nueva
para presentar las nuevas funcionalidades. Por ultimo una vez controlado y revisado, se mergean las ramas de release con la rama productiva y la de desarrollo


3a)El Readme es importante para poder dar indicaciones necesarias para cuando alguien inicializa el repositorio. En este caso, lo utilizamos para realizar las respuestas de desarrollo
que pedia el enunciado.

3b)Para entender los cambios realizados en una pull request, es util pedir un titulo claro, que describa en breves palabras la funcionalidad o modificacion al sistema.
Ademas luego se debera escribir una descripcion mas detallada de los cambios realizados, si es que esta relacionada con un issue u bug anterior y como afectaria esto al sistema.

Las herramientas que nos da Github en este caso son, el control del codigo, de esta manera podemos revisar previamente antes de aceptar un pull request las lineas de codigo que fueron
modificada, ademas de una separacion por branches la cual indica quienes estuvieron trabajando en la misma para tener un control de las personas que realizan los cambios.

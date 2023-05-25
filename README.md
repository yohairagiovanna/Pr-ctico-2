# Práctico N 2
## Lista de 5 sistemas de Control de Versiones (VCS):

1. Subversion
2. SourceSafe
3. Darcs
4. Mercurial
5. Git

___
## Ventajas y desventajas de los sistemas de control de versiones:
### Ventajas de subversión: 
**Varios usuarios pueden editar el mismo archivo simultáneamente** . Todos pueden trabajar sin interrupciones en su copia local, luego, a la hora de enviar los cambios, el sistema brindará herramientas para integrarlos al repositorio sin sobrescribir los realizados por otro desarrollador.


**Asociar las modificaciones a una tarea.** Cada vez que se envían cambios al repositorio se pueden asociar a una tarea en particular (ej: desarrollo de una nueva funcionalidad, modificación, solución de un bug, etc).


**Se puede volver a versiones anteriores.** En cualquier momento se puede volver a cualquier versión anterior del producto.


**Se tiene un historial de los cambios realizados en el repositorio.** Útil en caso de que no recordemos que archivos se modificaron en una tarea en particular. Se cuenta con un historial de todos los cambios enviados y para cada uno cuales archivos fueron modificados.


**Permite obtener métricas.** Útil para medir la calidad y cantidad de trabajo realizado en una unidad de tiempo.


**Restringir lectura/escritura de directorios.** Permite configurar permisos de escritura y lectura sobre cada directorio a diferentes usuarios. De esta manera solo se dan accesos según el perfil y el tipo de tareas a realizar por cada integrante.


**Backup.** Todas las versiones del producto están alojadas en el servidor remoto. Solo basta con que el administrador del mismo se encargue de realizar el respaldo del repositorio.

### Desventajas de subversión:
•	La principal desventaja de Subversion es que es más lento que CVS y que una verificación local de Subversion requiere mayor espacio en disco.

•	El manejo de cambio de nombres de archivos no es completo. Lo maneja como la suma de una operación de copia y una de borrado.

•	El manejo de archivos binarios los trata internamente como si fuera de texto no como de Subversion.

### Ventajas de SourceSafe:

Para las personas que desarrollan programas en el sistema operativo Windows, resulta una herramienta útil ya que se integra fuertemente con el entorno de desarrollo integrado o IDE de Visual Studio permitiendo un manejo relativamente simple de versiones sobre una computadora individual y en equipos de trabajo relativamente pequeños.

### Desventajas de SourceSafe:
•	La principal desventaja de Visual SourceSafe reside en el método de acceso a los archivos compartidos que constituyen su repositorio mediante el protocolo SMB que no impide que estos sean manipulados de manera externa al producto por cualquier persona que tenga acceso al mismo, provocando corrupción de datos. Este mismo tipo de acceso a archivos compartidos provoca que en equipos de trabajo grandes, el acceso concurrente pueda ser particularmente lento.

•	El SourceSafe es configurable, permitiendo que un solo programador modifique el código fuente (recomendado) o que lo hagan varios. Las herramientas de gestión de diferencias para reunificar el código fuente modificado por varios programadores no son demasiado buenas comparadas con las de otros gestores de código fuente.

•	El SourceSafe es inestable cuando se suben ficheros binarios de gran tamaño, ya que espera solo ficheros de texto. Así que no es útil para almacenar documentación, solo código fuente.
### Ventajas de Darcs:

● Todas las copias de un repositorio son repositorios en sí mismos 

● Esto facilita: 
– el trabajo con múltiples repositorios, 
– la creación de repositorios temporarios para desarrollar cosas nuevas, y 
– la publicación de éstos; se puede usar cualquier servidor Web.

● Posee una muy buena integración con el correo electrónico, facilitando el envío de detalles de changesets por este medio. 

● Está escrito en el lenguaje funcional Haskell, y por lo tanto es multiplataforma. 

● Flexible: Para empezar un nuevo repositorio se hace un init en cualquier directorio.

### Desventajas de Darcs:

•	Darcs ha sido criticado por motivos de rendimiento.

•	La peor de estas cuestiones fue el algoritmo de fusión de Darcs 1.x que, en el peor de los casos, podría hacer un trabajo exponencial de fusionar algunos conflictos.

### Ventajas de Mercurial:

•	Escalable y adaptable al tamaño y exigencias del proyecto.

•	Escrito en Python por ende es más fácil su manejo.

•	Funciona bien sobre páginas y directorios web

### Desventajas de Mercurial:

•	Pocas caracterizas añadidas por default

•	Comunidad de desarrollo muy pequeña.

## Ventajas de git:

•	Sistema distribuido, sin un punto central de fallo, que permite el trabajo incluso sin conexión.

•	Superrápido y ligero, optimizado para hacer operaciones de control muy rápidas.

•	Crear ramas y mezclarlas es rápido y poco propenso a problemas, al contrario que en otros sistemas tradicionales.

•	La integridad de la información está asegurada gracias a su modelo de almacenamiento, que permite predecir este tipo de problemas. En sistemas tradicionales este era un problema grave.

•	Permite flujos de trabajo muy flexibles.

•	El concepto de área de preparación o staging permite versionar los cambios como nos convenga, no todo o nada.

•	¡Es gratis! y de código abierto.

### Desventajas de git:

•	Es más complejo que los sistemas centralizados tradicionales porque entran en juego más repositorios, más operaciones y más posibilidades para trabajar en equipo, que hay que decidir.

•	La curva de aprendizaje es empinada. Lo básico lo aprendes enseguida, pero la realidad te demuestra que no es suficiente "tocar de oído" con él. La documentación es tan compleja que muchas veces no resulta de ayuda.

•	Los comandos y algunos conceptos que usa pueden llegar a ser confusos, al igual que algunos mensajes que muestra.

•	Por defecto, se lleva mal con archivos binarios muy grandes, como vídeos o documentos gráficos muy pesados. Por suerte existen soluciones para ello (Git LFS).

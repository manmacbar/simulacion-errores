Recuperación de archivos borrados en Git

Se eliminó accidentalmente el archivo errores.sh y se confirmó el cambio con un commit.

Comandos utilizados para recuperar el archivo

Se utilizó el siguiente comando para recuperar el archivo desde el commit anterior:

git checkout HEAD~1 -- errores.sh

Se añadió nuevamente el archivo al repositorio:

git add errores.sh

Se confirmó la recuperación con un commit:

git commit -m "Recupero el archivo errores.sh"

Aprendizaje obtenido

He aprendido que Git permite recuperar archivos incluso después de haberlos eliminado y confirmado en un commit.
El uso de comandos como git checkout facilita volver a estados anteriores sin perder información.
También he entendido la importancia de no entrar en pánico ante errores, ya que Git guarda un historial completo de cambios.

# programa-para-backup
Un archivo ejecutable (por lotes) para hacer una copia automática de una carpeta en el disco duro y en un pendrive. Mantiene un número máximo de copias de seguridad, elegible, y cuando se hace una nueva se borra la más antigua.

**DETALLES**
- Copiará todos los archivos y carpetas con tildes, nombres largos, etc. (no copiará ni ocultos ni ficheros de sistema, para eso habría que tener privilegios de administrador)
- Hará una copia en el disco duro y otra en un pendrive. Si no estuviera conectado el pendrive con el nombre indicado hace sólo la copia en el disco duro.

**INSTRUCCIONES**

1. Abrir el fichero txt
2. En las primeras líneas del archivo cambiar...
- Nombre de la Carpeta de trabajo (Fíjate que hay que poner la ruta completa C:\blabla...)
- Nombre de la Carpeta de backup (Fíjate que hay que poner la ruta completa C:\blabla...)
- Nombre del pendrive
- Número de copias que quieras que se mantengan (cuando pasen de ese número cada copia nueva lleva el borrado de la más antigua)
3. Guardar como, el nombre que quieras y añadir la extensión .bat
4. Cuando le hagas doble click se ejecutará y se quedará la ventana de comando abierta para que veas lo que ha pasado y los mensajes de éxito o de no haber podido hacer alguna cosa. La ventana de comandos esperará a que pulses cualquier tecla para cerrarse.
5. Si una vez creado el .bat quieres editarlo, sólo tienes que darle a botón derecho y "editar con block de notas" (por si quieres cambiar el nombre de las carpetas, número de copias, etc.), luego le das a guardar y se actualiza el .bat

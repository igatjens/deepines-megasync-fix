# deepines-megasync-fix
Parche para hacer que Megasync se abra correctamente en Deepin 20

Instala megasync y agrega el parámetro env QT_SCALE_FACTOR=1 a la ejecución del lanzador de megasync.

Luego instala un servicio que se ejecuta una vez en cada arranque del sistema que verifica el parche y lo aplica de ser necesario.

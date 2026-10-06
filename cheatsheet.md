| Comando | ¿Qué hace? (En palabras sencillas) |
| :--- | :--- |
| `git status` | **Tu brújula:** Te dice exactamente en qué estado está tu proyecto: qué archivos has modificado (en rojo), cuáles ya metiste a la caja (en verde) y cuáles son nuevos que Git aún no sigue. |
| `git add <archivo>` | **Meter a la caja:** Guarda una foto rápida de tus cambios y los coloca en la zona de preparación (*staging area*). Es elegir qué vas a guardar. |
| `git commit -m "mensaje"` | **Cerrar y etiquetar la caja:** Registra una foto fija (*snapshot*) permanente en el historial de tu computadora con una nota breve de lo que hiciste. |
| `git push` | **Enviar el paquete:** Sube todos los commits que guardaste localmente hacia el repositorio remoto en GitHub para que tu equipo los vea. |
| `git pull` | **Traer lo nuevo:** Descarga los cambios que subieron tus compañeros a GitHub y los junta con tu trabajo. ¡Hazlo siempre antes de empezar a programar! |
| `git log` / `git log --oneline` | **La línea del tiempo:** Te muestra la lista de fotos/commits que has guardado hacia atrás, con su código identificador (*hash*) y su mensaje. |
| `git diff` | **Ver qué cambió:** Compara lo que tienes editado ahorita contra la última foto guardada, enseñándote qué líneas agregaste o borraste. |
| `git restore <archivo>` | **El botón de deshacer:** Si modificaste un archivo y te arrepentiste (sin haber hecho `add`), lo regresa a como estaba en el último commit. *(Ojo: lo que no guardaste se pierde)*. |
| `git restore --staged <archivo>` | **Sacar de la caja:** Si le diste `add` a un archivo por error, lo saca de la zona de preparación pero **conserva todos tus cambios e impresiones intactos**. |
| `git clone <url>` | **Descargar el proyecto:** Copia por primera vez un repositorio completo desde GitHub a tu computadora con todo su historial y la conexión lista. |
| `git init` | **Empezar desde cero:** Convierte una carpeta vacía de tu computadora en un repositorio de Git local (ideal para carpetas de prueba). |
| `git commit --amend -m "mensaje"` | **Corregir la etiqueta:** Reescribe el mensaje o contenido del último commit si te equivocaste y **todavía no has hecho push**. |
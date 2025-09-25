1️⃣ Configurar tu identidad en Git
git config --global user.name "welding30001994"
git config --global user.email "welding30001994@gmail.com"


🔹 git config: Sirve para configurar opciones de Git.
🔹 --global: Significa que esta configuración aplicará a todos los repositorios en tu computadora (no solo en uno).
🔹 user.name / user.email: Son los datos que Git usa para identificarte en cada commit (registro de cambios).
✅ En resumen: Le estás diciendo a Git "Cada vez que haga un commit, pon que yo soy welding30001994 y mi correo es welding30001994@gmail.com".

2️⃣ Cambiar de carpeta en la terminal
cd d:\Desktop\beaver trading\Beaver-main


🔹 cd = change directory → Cambiar de carpeta.
🔹 Aquí estás entrando a la carpeta de tu proyecto:
📂 d:\Desktop\beaver trading\Beaver-main
✅ En resumen: Te posicionas dentro del proyecto para que Git sepa en qué carpeta debe trabajar.

3️⃣ Ver el estado del repositorio
git status


🔹 Muestra el estado actual del repositorio:

En qué rama (branch) estás trabajando.

Si hay archivos nuevos, modificados o listos para hacer commit.
🔹 En tu caso respondió:

On branch main


✅ En resumen: Estás en la rama principal (main) y Git te dice si hay algo pendiente de guardar.

4️⃣ Vincular el repositorio local con GitHub
git remote add origin https://github.com/welding30001994/Beaver_Course.git


🔹 git remote: Administra las conexiones con repositorios remotos (GitHub, GitLab, etc.).
🔹 add origin:

add = agregar una conexión.

origin = nombre que le das al remoto (por convención siempre se llama origin).
🔹 Luego pones la URL del repositorio en GitHub.
✅ En resumen: Le dices a Git:
"Este proyecto local ahora está conectado con este repositorio de GitHub."

5️⃣ Subir los archivos a GitHub
git push -u origin main


🔹 git push: Envía (empuja) los cambios desde tu computadora hacia el repositorio remoto (GitHub).
🔹 -u: Crea una relación entre la rama local (main) y la remota (main) para que en el futuro solo tengas que escribir:

git push


y Git ya sabrá a dónde enviar los cambios.
🔹 origin: Es el nombre de la conexión remota.
🔹 main: Es la rama que estás subiendo.
✅ En resumen: Subes el proyecto local a la rama principal del repositorio de GitHub.
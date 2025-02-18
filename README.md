# Clonar el repositorio (reemplaza <URL-del-repo> con la URL de tu repositorio)
git clone <URL-del-repo>
cd <última oportunidad>

# Copiar los archivos al repositorio
cp /documents/index.html .
cp /documents/styles.css .
cp /documents/script.js .

# Agregar los archivos al repositorio
git add index.html styles.css script.js

# Hacer commit de los archivos
git commit -m "Añadir archivos iniciales"

# Subir los cambios a GitHub
git push origin main

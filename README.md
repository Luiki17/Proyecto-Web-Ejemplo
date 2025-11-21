# Proyecto-Web-Ejemplo

## 📌 Descripción del Proyecto
Este repositorio forma parte de la actividad **“Integrando HTML con Git y GitHub”** del curso de Git y GitHub.  
El objetivo de esta actividad es practicar el uso de Git, la creación de ramas, la resolución de conflictos y el trabajo colaborativo simulado, utilizando un proyecto web simple hecho con **HTML y CSS**.

---

## 🧾 1. Pasos realizados en la actividad

### ✔️ Creación del repositorio
- Se creó un repositorio público en GitHub llamado **Proyecto-Web-Ejemplo**.
- Se inicializó con un archivo **README.md** con una breve descripción del proyecto.

### ✔️ Clonación y subida del proyecto web
- El repositorio fue clonado en la máquina local con el siguiente comando:

git clone https://github.com/Luiki17/Proyecto-Web-Ejemplo.git

- Se añadieron los archivos HTML y CSS del proyecto web.
- Se realizó el commit inicial:

git add .
git commit -m "add archivos html y css"
git push

- Se creó una rama llamada feature-mejora-estilo:

git checkout -b feature-mejora-estilo

En esta rama se alineó el título

- Los cambios se documentaron con varios commits claros.
- La rama se subió a GitHub y se creó un Pull Request para integrarla en main.

⚠️ 2. Simulación y resolución de un conflicto de merge

Durante la práctica, se simuló el caso donde otro colaborador hubiese modificado el mismo archivo en la rama main.

Pasos realizados:

Se modificó el mismo archivo tanto en main como en feature-mejora-estilo.

Al intentar fusionar las ramas, Git mostró un conflicto.

Se resolvió el conflicto manualmente editando el archivo y eliminando las marcas:

<<<<<<< HEAD
=======
>>>>>>> main


Una vez corregido el archivo, se completó el merge con:

git add .
git commit -m "Conflicto resuelto entre main y feature-mejora-estilo"


Finalmente, los cambios se integraron correctamente a main.

💻 3. Cómo clonar y ejecutar el proyecto en local
📥 Clonar el repositorio
git clone https://github.com/Luiki17/Proyecto-Web-Ejemplo.git
cd Proyecto-Web-Ejemplo

▶️ Ejecutar el proyecto

Solo es necesario abrir el archivo index.html en cualquier navegador web.
El estilo se carga automáticamente desde style.css.

▶️ Ejecutar el proyecto

Solo es necesario abrir el archivo index.html en cualquier navegador web.
El estilo se carga automáticamente desde style.css.

🌿 4. Ramas del proyecto

main	Contiene la versión estable del proyecto.
feature-mejora-estilo	Incluye mejoras visuales aplicadas al sitio web.

📌 5. Estado final del repositorio

✔ Proyecto HTML + CSS
✔ Documentación actualizada
✔ Ramas integradas correctamente
✔ Conflictos resueltos y registrados en los commits

🎓 Sugerencias aprendidas

Trabajar con ramas facilita el desarrollo colaborativo.

Los conflictos de merge deben resolverse revisando el archivo afectado.

Los mensajes de commit deben ser claros y descriptivos.

La documentación (README.md) es clave para entender un proyecto.

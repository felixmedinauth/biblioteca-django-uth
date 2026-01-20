este proyecto es para crear una api donde se guarda un registro de una libreria capaz de hacer prestamos, guardar catalogos, contener informacion de escritores, entre muchas funciones mas.
las tecnologias utilizadas para este proyecto fueron: visual studio code, github, pythonanywhere,Python 3.10+ y Django 4.2,mysqlclient,Bootstrap 5 para diseño responsive, Font Awesome para iconos, CSS personalizado y JavaScript. .
Clonar el repositorio:

Bash

git clone https://github.com/TU_USUARIO/biblioteca-django-uth.git
cd biblioteca-django-uth
Crear y activar entorno virtual:

Bash

python -m venv venv
.\venv\Scripts\Activate  # En Windows [cite: 1]
Instalar dependencias:

Bash

pip install -r requirements.txt 

Configurar variables de entorno: Crear un archivo .env en la raíz del proyecto con tus credenciales de MySQL (DB_NAME, DB_USER, DB_PASSWORD, etc.).

Ejecutar migraciones:

Bash
python manage.py makemigrations 
python manage.py migrate 
Iniciar el servidor:

Bash

python manage.py runserver 
Estructura del Proyecto
La organización de las carpetas principales es la siguiente:


biblioteca_project/: Configuración global del proyecto Django (settings, urls, wsgi).
+1


libros/: Aplicación principal que contiene los modelos (Autor, Libro, Categoria, etc.), vistas y controladores.
+1


templates/: Archivos HTML divididos en base/ (estructura general) y libros/ (vistas específicas).


static/: Recursos de frontend incluyendo css/, js/ e images/.


media/: Carpeta para el almacenamiento de portadas de libros y fotos de autores (no se sube a GitHub).
utor: fekix medina

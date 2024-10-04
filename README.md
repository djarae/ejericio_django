# ejericio_django
Ejercicio django restframework basico

# video tutorial :
https://www.youtube.com/watch?v=38XWpyEK8IY&t=1839s

# Pasos
# Confirmar instalacion python : python --version( min 1 aprox)
#  crear entorno virtual. (m2 aprox)
    pip install virtualenv
    python -m venv venv  //Ojo que el segundo "venv" es el nombre de la carpeta que se crea 
                         //con el entorno virtual

# activar el entorno virtual(m5 aprox ):
    venv\Scripts\activate 

# desactivar entorno virtual:
    deactivate

# Creacion projecto
    django-admin startproject django_crud_api . //El punto coloca los archivs al inicio

# ejecutar projecto  (m7 aprox)
     python manage.py runserver

## Iniciamos una aplicacion: (m7 aprox)
     python manage.py startapp tasks     
     <Confguramos en settings.py agregamos tasks>
## Migramos
 python manage.py migrate
 // Con el comando anterior , creamos todas las tablas necesarias del projecto que  necesita para funcionar
                


# Notas solucion al error del "pip install"
    https://stackoverflow.com/questions/37220055/pip-fatal-error-in-launcher-unable-to-create-process-using


# Notas: Django restframework es mucha config, todo automatizado y rigido esta bien
 
# Instalación y ejecución

1. Descargar e instalar python desde el siguiente link:

    [Link de descargas Python](https://www.python.org/downloads/)

2. Descargar los archivos "insta-unfollower.py" y "requirements.txt" desde el siguiente link:

    [insta-unfollower.py](https://drive.google.com/open?id=1JIMLpJ6ADX5VHkttwMCX5zmODvCPAYXy&authuser=daniel.arbelaez.alvarez%40gmail.com&usp=drive_fs)

    [requirements.txt](https://drive.google.com/open?id=1JDJGuwu5YKxK81dTavIZFb6rhS9J9yhy&authuser=daniel.arbelaez.alvarez%40gmail.com&usp=drive_fs)

3. Abrir la ventana de PowerShell desde la carpeta de descargas o en su defecto la que contenga los archivos descargados:

   ~~~~
   Shift (:) + Click derecho
   ~~~~
   
4. Instalar desde PowerShell y por una sola vez los requerimientos para el buen funcionamiento del algoritmo con el siguiente comando:
    ~~~~
    python -m pip install -r .\requirements.txt
    ~~~~
5. Ejecutar cada vez que se requiera desde el cmd el siguiente comando en el programa 
    ~~~~
    python insta-unfollower.py USERNAME PASSWORD
    ~~~~
6. En tu perfil de instagram aparecerá la solicitud de confirmación de que has iniciado sesión desde otro dispositivo. Debes de seleccionar "Fui yo".
7. Debes de ***ejecutar*** el algoritmo máximo 8 horas al día alcanzando alrededor de 200 unfollows.
8.  La ejecución del algoritmo se recomienda realizar ***máximo*** durante 5 días, luego ***suspender*** el uso 1 o 2 días. 
9.  Los anteriores pasos fueron probados y actualizados para evitar el bloqueo de tu cuenta de instagram por **"Actividad sospechosa"**

---
## Bloqueo de cuenta

En caso de que te aparezca **"Tu cuenta se bloqueó temporalmente"**, deberás seguir los pasos que te indique instagram para volver acceder a ella; sin embargo, si sigues los pasos anteriormente descritos lo más probable es que no suceda.

---
## Créditos 
[tuxity/insta-unfollower](https://github.com/tuxity/insta-unfollower)
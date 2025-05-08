### 1. Crea una credencial en GitHub
Primero debemos crear un Token en GITHUB
Settings** > Developer settings > Personal access tokens.

<img width="690" alt="image" src="https://github.com/user-attachments/assets/37f30a99-2634-49f8-8346-cfaf6c8c5551" />
New personal access token (Classic)
<img width="696" alt="image" src="https://github.com/user-attachments/assets/d560dd19-4d1a-413e-8f62-fef6f36e4f3c" />

Copiar el token y guardarlo en vuestra password manager !!!!!!!!!!!!!!!!!!!!!!!!!
<img width="696" alt="image" src="https://github.com/user-attachments/assets/b2dbbc82-981c-456f-963e-22ba8d992920" />

### 2. Crea una credencial en Jenkins

Es mas sencillo desde el propio pipeline, esperar a crearlo en la creación del pipeline.
Crear nuevo pipeline. Nuevo Item; Tipo Pipeline
<img width="699" alt="image" src="https://github.com/user-attachments/assets/c05eac7a-444b-411d-9f45-d58b9d8ce14c" />


Configuración del Pipeline:
En "Definition", selecciona "Pipeline script from SCM".
En "SCM", selecciona "Git".
**Repository URL:** Ingresa la URL de tu repositorio de GitHub.   (MUCHO CUIDADO SOLO HTTPS)
<img width="1039" alt="image" src="https://github.com/user-attachments/assets/bcd5a6e5-bcfd-45e6-aeef-9a43d161ea7f" />

Credentials +ADD
<img width="699" alt="image" src="https://github.com/user-attachments/assets/0adf14e8-75c8-4dd2-92e3-4effd6427a50" />


Como hemos elegido un script SCM, Tenemos que indicar el path de nuestro Jenkinfile
<img width="698" alt="image" src="https://github.com/user-attachments/assets/5f8ca5ae-9632-4d6d-b415-43b08238014c" />



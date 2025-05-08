### 1. Crea una credencial en GitHub
Primero debemos crear un Token en GITHUB
**Settings** > **Developer settings** > **Personal access tokens**.

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

![[Pasted image 20250503170002.png]]

Credentials +ADD

![[Pasted image 20250503165533.png]]

Como hemos elegido un script SCM, Tenemos que indicar el path de nuestro Jenkinfile

![[Pasted image 20250503170150.png]]

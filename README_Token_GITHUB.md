### 1. Crea una credencial en GitHub
Primero debemos crear un Token en GITHUB
**Settings** > **Developer settings** > **Personal access tokens**.

![[Pasted image 20250503161617.png]]

New personal access token (Classic)
![[Pasted image 20250503163425.png]]
![[Pasted image 20250503163443.png]]

Copiar el token y guardarlo en vuestra password manager !!!!!!!!!!!!!!!!!!!!!!!!!
![[Pasted image 20250503163740.png]]

### 2. Crea una credencial en Jenkins

Es mas sencillo desde el propio pipeline, esperar a crearlo en la creación del pipeline.
Crear nuevo pipeline. Nuevo Item; Tipo Pipeline
![[Pasted image 20250503160718.png]]

Configuración del Pipeline:
En "Definition", selecciona "Pipeline script from SCM".
En "SCM", selecciona "Git".
**Repository URL:** Ingresa la URL de tu repositorio de GitHub.   (MUCHO CUIDADO SOLO HTTPS)

![[Pasted image 20250503170002.png]]

Credentials +ADD

![[Pasted image 20250503165533.png]]

Como hemos elegido un script SCM, Tenemos que indicar el path de nuestro Jenkinfile

![[Pasted image 20250503170150.png]]

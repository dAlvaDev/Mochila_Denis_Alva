# Command sheet Git & GitHub 
![GityGitHub](https://i.ibb.co/f9ZsRZX/Gity-Git-Hub.png "GityGitHub")

### Preguntas 📝
**a. ¿Quién inventó el sistema de control de versión Git y por qué?**
Según investigué lo inventó Linus Torvallds, buscaba una herramienta que feura rápida, confiable y capaz de manejar proyectos de gran envergadura distribuidos en equipos de desarrolladores dispersos geográficamente.

**b. ¿A quién pertenece actualmente Github y por qué?**
Microsoft adquirió Github, la compró cuyo objetivo fue fortalecer el enfoque de Microsoft en el desarrollo de software y en la colaboración de código abierto.

**c. ¿Hay otra forma que no sea la terminal para trabajar con Github?**
si, tenemos a la interfaz gráfica de Github, aplicaciones de escritorio y clientes git gráficos de terceros

## Comandos Git 💻

Ayuda
```bash
  git help
```
Comando expecífico
```bash
  git help add
  git help commit
```
Establecer el usuario y el e-mail
```bash
  git config --global user.name "nombre de usuario"
  git config --global user.email email@email.com
```
Crear un nuevo repositorio
```bash
  git init
```
Verificar el estado de los archivos/directorios
```bash
  git status (muestra el estado de los archivos en su repositorio)
```
Añadir un archivo
```bash
  git add nombre_archivo_directorio (archivo específico)
  git add . / git add --all (todos los archivos)
```
Commitear un archivo/directorio
```bash
  git commit nombre_archivo -m "mensaje del commit"
```
Remover un archivo o directorio
```bash
  git rm archivo
  git rm -r directorio (remueve el directorio y los archivos que contiene)
```
Subir los archivos al staging area
```bash
  git add .
```
Cambiar el nombre de la rama principal de Master a main
```bash
  git branch -M main
```
Subir los archivos al repositorio en la nube
```bash
  git push origin main
```
Bajar los archivos del repositorio de GitHub
```bash
  git pull origin main
```
Crear una nueva rama
```bash
  git branch rama2
```
Cambiarse a otra rama
```bash
  git checkout rama2
```
## Comandos de la terminal Bash
|  Comando | Descripción  |
| ------------ | ------------ |
|  ls | Lista los archivos en el directorio actual  |
|  mkdir [carpeta] | Crea un nuevo directorio o carpeta  |
|  touch [Nombre del archivo] | Crea un nuevo archivo |
|  rm [Nombre del archivo] | Elimina un archivo  |
|  cd .. | Sube un nivel de carpeta  |


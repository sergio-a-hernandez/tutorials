# Tus primeros pasos en GitHub. 
Aquí tienes una guía básica para iniciarte en GitHub.

## Paso 1: Crear una cuenta en GitHub

Lo primero es lo primero. Dirígete a [GitHub](https://github.com/) y regístrate. Es un proceso sencillo que solo te llevará unos minutos.

## Paso 2: Instalar Git

GitHub utiliza Git para el control de versiones. Puedes descargar Git [aquí](https://git-scm.com/downloads) e instalarlo en tu máquina.

## Paso 3: Configurar Git

Después de la instalación, necesitas configurar tu nombre de usuario y tu dirección de correo electrónico en Git. Abre tu terminal y ejecuta los siguientes comandos, reemplazando "TuNombre" y "TuCorreo" con tu nombre de usuario y tu correo electrónico de GitHub:

```bash
git config --global user.name "TuNombre"
git config --global user.email "TuCorreo"
```

## Paso 4: Crear tu primer repositorio

Ahora, es hora de crear tu primer repositorio en GitHub. En tu página principal de GitHub, haz clic en el botón "Nuevo" (esquina superior derecha) y dale un nombre a tu repositorio. Puedes inicializarlo con un README si lo deseas.

## Paso 5: Clonar tu repositorio

Para empezar a trabajar en tu máquina local, necesitas clonar tu repositorio. Copia la URL de tu repositorio en GitHub y ejecuta el siguiente comando en tu terminal:

```bash
git clone URL_del_repositorio
```

Esto creará una copia local de tu repositorio.

## Paso 6: Añadir archivos y hacer tu primer commit

Ahora, añade archivos a tu repositorio clonado. Puedes crear un archivo `README.md` y algunos archivos de código. Después, ejecuta los siguientes comandos para realizar tu primer commit:

```bash
git add .
git commit -m "Primer commit: Agregado README y archivos iniciales"
```

## Paso 7: Subir cambios a GitHub

Ahora que has hecho tu commit, es hora de subir esos cambios a GitHub. Utiliza el siguiente comando:

```bash
git push origin main
```

Esto enviará tus cambios al repositorio remoto en GitHub.

## Paso 8: Ramas y colaboración

GitHub es genial para colaborar en proyectos. Puedes crear ramas para trabajar en funciones específicas y fusionarlas cuando estén listas. Investiga sobre comandos como `git branch`, `git checkout`, y `git merge`.

## Paso 9: Issues y Pull Requests

Aprende a utilizar las "Issues" para realizar un seguimiento de errores y funciones pendientes. Los "Pull Requests" son fundamentales para contribuir a proyectos de código abierto. Te permiten proponer cambios y fusionarlos con el proyecto principal.

## Paso 10: Explorar proyectos y colaborar

No te limites a tus propios proyectos. Explora GitHub, encuentra proyectos que te interesen y contribuye. Puedes hacerlo reportando problemas, proponiendo cambios o mejorando la documentación.

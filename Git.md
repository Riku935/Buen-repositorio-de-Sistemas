![Git](https://blog.coffeedevs.com/content/images/2016/07/Git-rename-branch.jpg)
# Practica 4 
## Resumen de Git
Git es una herramienta que realiza una función del control de versiones de código de forma distribuida. Permite gestionar los diversos cambios sobre los elementos de algun producto o una configuracion del mismo.

Git fue creado pensando en la eficiencia y la confiabilidad del mantenimiento de versiones de aplicaciones cuando éstas tienen un gran número de archivos de código fuente, es decir Git nos proporciona las herramientas para desarrollar un trabajo en equipo de manera inteligente y rápida 

### Caracteristicas de Git
- Con ella podemos mantener un historial completo de versiones
- Es software libre
- No depende de un repositorio central
- Tiene un sistema de trabajo con ramas  

### Estructura de trabajo en Git
1. El área del working directory, que es dónde vamos a tener todos nuestros ficheros
1. El staging area, que es donde van los archivos que estamos modificando y que aceptamos para que vayan en una futura revisión.
1. El área de commit o el git directory, que es dónde se almacenan la revisión completa.

### Comandos basicos de Git

- git init creará un nuevo repositorio local
    > git init

- git add se usa para agregar archivos al área de preparación.
    >git add [nombre del archivo]

- git commit creará una instantánea de los cambios y la guardará en el directorio git.
    >git commit –m “El mensaje que acompaña al commit va aquí”
- git config puede ser usado para establecer una configuración específica de usuario, como el email.
    >git config --global user.email tuemail@ejemplo.com
- git status muestra la lista de los archivos que se han cambiado junto con los archivos que están por ser preparados o confirmados.
    >git status
- git push se usa para enviar confirmaciones locales a la rama maestra del repositorio remoto
    >git push  origin 
- Subir la rama(branch) “nombre_rama” al servidor remoto.
    >git push origin “nombre rama”
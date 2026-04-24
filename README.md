# Hacer-un-repositorio-Git
Pasos a seguir
GUÍA DE PRÁCTICA: TRABAJANDO CON GIT

Objetivo general

T. Aprender a utilizar Git para el control de versiones y y el trabajo colaborativo en proyectos de software.

Objetivos específicos

1. Configurar Git en tu equipo.

2. Crear y gestionar repositorios locales y remotos.

3. Usar comandos básicos para registrar y controlar cambios.

4. Trabajar con ramas y fusiones (merge).

5. Subir y descargar proyectos con GitHub.

Requisitos previos

- Tener instalado Git (https://git-scm.com).

- Contar con una cuenta en GitHub.
Parte 1: Configuración inicial

1. Abre la terminal o consola de Git.

2. Configura tu nombre y correo:

git config --global user.name "TuNombre" git config --global user.email "tuemail@example.com"

3. Verifica la configuración:

git config --list

I

Evidencia: captura de pantalla mostrando la configuración.

Parte 2: Creación del repositorio local

1. Crea una carpeta llamada proyecto-git.

2. Entra a la carpeta y escribe:

git init

3. Crea un archivo README.md con tu nombre y una breve descripción.

4. Agrega y guarda los cambios:

git add README.md

git commit -m "Primer commit: creación del README"
- Tener un editor de texto o IDE (por ejemplo, Visual Studio Code).

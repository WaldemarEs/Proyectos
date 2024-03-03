# ¡Guía básica de Git!

Git es un sistema de control de versiones que te permite:

- Rastrear cambios en tus archivos.
- Colaborar con otros en proyectos.
- Revertir errores y volver a versiones anteriores.

## Pasos para usar Git en un proyecto en desarrollo:

1. **Inicializa el repositorio**: En la carpeta de tu proyecto, ejecuta `git init` para inicializar un nuevo repositorio Git.

2. **Agrega archivos**: Usa `git add <archivo>` para agregar archivos al área de preparación. Puedes usar `git add .` para agregar todos los archivos en la carpeta actual.

3. **Crea un commit**: Una vez que hayas hecho algunos cambios en tus archivos, puedes usar `git commit -m "Mensaje"` para crear un nuevo commit con esos cambios.

4. **Sube tus cambios**: Si estás trabajando con un repositorio remoto, puedes usar `git push` para subir tus cambios a ese repositorio.

5. **Descarga los cambios**: Si otros han hecho cambios en el repositorio remoto, puedes usar `git pull` para descargar esos cambios y fusionarlos con tu copia local.

6. **Crea una nueva rama**: Si deseas trabajar en una nueva característica o experimentar sin afectar el código principal, puedes usar `git branch <nombre>` para crear una nueva rama.

7. **Cambia de rama**: Usa `git checkout <nombre>` para cambiar a otra rama y trabajar en ella.

8. **Fusiona cambios**: Una vez que hayas terminado de trabajar en una rama, puedes usar `git merge <nombre>` para fusionar los cambios de esa rama con la rama principal.


## Tabla de comandos básicos de Git en terminal:

| Comando | Descripción |
| --- | --- |
| `git init` | Inicializa un repositorio Git en la carpeta actual. |
| `git add <archivo>` | Agrega un archivo al área de preparación. |
| `git commit -m "Mensaje"` | Crea un commit con los cambios del área de preparación. |
| `git push` | Sube tus cambios al repositorio remoto. |
| `git pull` | Descarga los cambios del repositorio remoto y los fusiona con tu copia local. |
| `git clone <url>` | Clona un repositorio remoto en tu computadora. |
| `git branch <nombre>` | Crea una nueva rama. |
| `git checkout <nombre>` | Cambia a la rama indicada. |
| `git merge <nombre>` | Fusiona la rama indicada con la rama actual. |
| `git log` | Muestra un historial de los commits. |
| `git reset HEAD~1` | Deshace el último commit. |

## Consejos adicionales:

- Usa alias para los comandos que más uses.
- Configura un editor de texto por defecto para Git.
- Aprende a usar `git diff` para ver las diferencias entre archivos.
- Investiga las opciones de `git config` para personalizar tu experiencia.


## Pasos para crear una nueva rama de Git para cada proyecto:

*  Crea una carpeta para tu nuevo proyecto dentro de la carpeta del repositorio.

*  Navega a la carpeta del nuevo proyecto.
Ejecuta el siguiente comando para crear una nueva rama:
git checkout -b nombre_de_la_rama
* Realiza los cambios y confirmaciones en la nueva rama.
* Cuando estés listo para integrar los cambios en la rama principal:
git checkout main
git merge nombre_de_la_rama
* Sube los cambios al repositorio remoto:
git push origin main


### Consejos adicionales:

* Puedes usar un alias para el comando git checkout -b para que sea más rápido.
* Puedes usar la opción -m con el comando git commit para agregar un mensaje de confirmación.
* Puedes usar la opción --no-ff con el comando git merge para crear una nueva confirmación de fusión incluso si la rama se puede fusionar sin ella.
Ejemplo:

    1.  Crea una carpeta para el nuevo proyecto, 
mkdir proyecto_nuevo

# Navega a la carpeta del nuevo proyecto
cd proyecto_nuevo

# Crea una nueva rama
git checkout -b proyecto_nuevo

# Realiza cambios y confirmaciones

# Integra los cambios en la rama principal
git checkout main
git merge proyecto_nuevo

# Sube los cambios al repositorio remoto
git push origin main
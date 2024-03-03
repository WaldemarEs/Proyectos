# Guía de Uso de Terminal para Desarrollo Web

## Navegación por Carpetas

| Comando | Descripción |
|---------|-------------|
| `ls`    | Listar archivos y carpetas en el directorio actual. |
| `cd nombre_del_directorio` | Cambiar al directorio especificado. |
| `cd ..` | Retroceder un nivel en la jerarquía de directorios. |
| `cd /`  | Ir al directorio raíz. |

## Crear y Manipular Directorios

| Comando | Descripción |
|---------|-------------|
| `mkdir nombre_del_directorio` | Crear un nuevo directorio. |
| `mkdir -p directorio_padre/directorio_hijo` | Crear directorios anidados. |
| `mv nombre_actual nuevo_nombre` | Mover o renombrar directorios. |
| `cp -r origen destino` | Copiar directorios y archivos. |
| `rm -r nombre_del_directorio` | Eliminar directorios y su contenido. |
| `rm nombre_del_archivo` | Eliminar un archivo. |

## Manipulación de Archivos

| Comando | Descripción |
|---------|-------------|
| `touch nombre_del_archivo` | Crear un nuevo archivo vacío. |
| `nano nombre_del_archivo` | Abrir el archivo en el editor de texto nano. (Guarda con `Ctrl + o` y Salir con `Ctrl + X`) |
| `cat nombre_del_archivo` | Mostrar el contenido completo de un archivo. |
| `cp archivo_origen archivo_destino` | Copiar un archivo a otro destino. |
| `mv archivo_actual nuevo_nombre` | Mover o renombrar un archivo. |
| `rm nombre_del_archivo` | Eliminar un archivo. |

### Notas:
- Utiliza `ls -a` para mostrar archivos ocultos.
- En `mv` y `cp`, el flag `-r` es necesario para operar con directorios.
- En `rm`, ten precaución, ya que elimina de manera irreversible.

## Rutas y Referencias

- **Ruta Absoluta:** Inicia desde la raíz (ej. `/usr/bin`).
- **Ruta Relativa:** Inicia desde el directorio actual (ej. `./carpeta`).

Es crucial comprender estos comandos para la gestión efectiva de archivos y directorios en el desarrollo web. 

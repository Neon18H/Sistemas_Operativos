# Sistemas_Operativos
Notas de mi clase de sistemas operativos.
Comandos Basicos Guias

- Navegación en el Sistema de Archivos
 pwd: Muestra el directorio de trabajo actual.

ls: Lista los archivos y directorios en el directorio actual.

ls -l: Muestra detalles de los archivos (permisos, tamaño, etc.).
ls -a: Muestra todos los archivos, incluidos los ocultos.
cd : Cambia al directorio especificado.

cd ..: Regresa al directorio padre.
cd ~: Cambia al directorio home del usuario.
Manipulación de Archivos y Directorios
mkdir : Crea un nuevo directorio.
rmdir : Elimina un directorio vacío.
rm : Elimina un archivo.
rm -r : Elimina un directorio y su contenido.
cp : Copia un archivo o directorio.
cp -r : Copia un directorio y su contenido.
mv : Mueve o renombra un archivo o directorio.

- Visualización de Archivos
cat : Muestra el contenido de un archivo en la terminal.
less : Permite navegar por un archivo de texto (usa q para salir).
head : Muestra las primeras líneas de un archivo.
tail : Muestra las últimas líneas de un archivo.

- Buscar y Filtrar
grep : Busca un patrón dentro de un archivo.
find  -name : Busca archivos por nombre en una ruta específica.

- Información del Sistema
df -h: Muestra el uso del espacio en disco.
top: Muestra los procesos en ejecución y el uso de recursos.
uname -a: Muestra información del sistema.
Permisos y Propiedades
chmod [permisos] [archivo]: Cambia los permisos de un archivo.
chown [usuario]:[grupo] [archivo]: Cambia el propietario y grupo de un archivo.

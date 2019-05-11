# Permisos de los archivos

Cuando se despliegan los archivos en forma de lista, en la primera columna  aparece un formato tipo F/---/---/---/M. F te indica sí el archivo es un directorio o no. Los siguientes parametros aparecen con los valores rwx, que significan read, write y excute respectivamente y siempre se despliegan en ese orden.  En la primera entrada, osea el primer grupo de rwx indican los permisos que tiene el usuario para leer, escribir o ejecutar el archivo, la segunda es del grupo del usuario y el ultimo son los permisos universales. Este código  esta asociado a un número en binario, de tal forma que donde hay escrito un valor \(r o w o x\) se asocia con 1 y donde no con 0. Con este codigo podemos modificar los permisos de un archivo con el comando chmod NNN.


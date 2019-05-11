# Comandos de básicos

## Comandos de navegación

| Comandos | Acción |
| :--- | :--- |
| **pwd** | Te indica el dirrectorio en donde estás |
| **ls** | Enlista los archivos |
| **cd** | Cambia el directorio hacia \[arg\] |
| **du -h** | enlista el tamaño de los archivos |
| **pushd-popd** | NO ME ACUERDOO AHHHHHH |
| **mkdir** | Crea un nuevo directorio \[arg\] |
| **touch** | Crea un nuevo archivo o modifica la hora de acceso |
| **more** | Muestra el contenido del archivo por partes |
| **cat** | Muestra todo el contenido del archivo |
| **tail** | Muestra las ultimas 10 lineas del archivo |
| **ln -s \[Arc\] \[Apuntador\]** | Crea un apuntador |

## Comandos de control y manipulación de streams

| Comando | Acción |
| :--- | :--- |
| **\(CO\) &gt; 'archivo.log'** | El operador &gt; escribe los datos en al archivo 'archivo.log' |
| **\(CO\) 1&gt;'log1' 2&gt;'log2'** | Escribe en los archivos 'log1' y 'log2' el STD\_OUT y STD\_ERROR respectivamente. |
| **\(CO\) &gt; 'todo' 2&gt;&1** | Escribe en el archivo 'todo', el STD\_OUT y STD\_ERROR |

## Comandos para control de procesos

| Comando | Acción |
| :--- | :--- |
| top | Enlista los procesos en ejecución. Se puede cambiar el orden con O. |
| ps -wA | Enlista todos los procesos y manda una lista al STD\_OUT |
| kill -9 | Mata cualquier proceso |

## Comandos de búsqueda y filtrado

| Comando | Acción |
| :--- | :--- |
| grep | Busca una cadena de caracteres en archivos, regresa al STD\_OUT la linea con la que hace match |
| find | Busca cadenas de caracteres en nombres de archivos |
| awk | Analiza archivos. Ejemplo el comando '\(CO\) \| awk -F, ‘{printf\(%S\[codigo\],$variable\(1,2,3\)\)}’ imprime una columna del archivo \(CO\). |

## Comandos de red

| Comando | Acción |
| :--- | :--- |
| curl | Trae al STD\_OUT el texto plano, -o guarda el archivo. |

## Comandos de compresión

| Comando | Acción |
| :--- | :--- |
| zip \[nombre.zip\] \[arc a comprimir\] | Comprime un archivoa .zip |
| unzip | Descomprime un archivo .zip |
| tar cfz \[archivo.tar.gz\] | Comprime |
| tar xfz \[archivo.tar.gz\] | Descomprime |

## Operadores de comandos

| Operador | Acción |
| :--- | :--- |
| Pipe \| | Manda el STD\_OUT al STD\_IN del siguiente comando |
| ; | Ejecuta el comando en orden, uno despues del otro |
| && | No estoy seguro |
| \(CO\) & | Manda el proceso a background, por lo tanto te brinda el ID y tener el contro sobre el proceso |
| alias | Te permite renomabrar un comando o serie de comandos |

## Hotkeys en Mac

| Hotkey | Acción |
| :--- | :--- |
| ctrl + r | Buscar comandos anteriormente usados |
| ctrl + k | Borra todo lo que esta despues de \| |
| comd + k | ejecuta clear |
| comd + l | Borra la salida del ultimo comando ejecutado |


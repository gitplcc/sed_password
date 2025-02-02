# Trabajo de SED: CONTRASEÑA

## Descripción

Trabajo para la asignatura de Sistemas Electronicos Digitales.

Desarrollo contraseña en la placa Nexys 4 DDR.

Programado en VHDL.

## Creación del fichero de proyecto

Abrir Vivado y en la consola de Tcl ejecutar el comando:

```
pwd
```

Este comando imprime el directorio de trabajo actual:

```
C:/Users/nombre/AppData/Roaming/Xilinx/Vivado
```

Normalmente no será el que queremos. Usaremos el comando:

```
cd C:/Mi_directorio_raiz/mi_subdirectorio/.../mi_proyecto
```

para ir al directorio donde he clonado mi proyecto. Una vez en el directorio
donde está el script Tcl, lo ejecutaremos con:

```
source  ./sed_password.tcl
```

El proyecto se creará en la carpeta:

```
C:/Mi_directorio_raiz/mi_subdirectorio/.../mi_proyecto
```

y se abrirá automáticamente.

## Adición de nuevos ficheros

Vivado insistirá en crear los nuevos ficheros de VHDL en su estructura de
directorios. No nos interesa. En mejor crear ficheros vacíos en src/ con el
explorador, incorporarlos al proyecto (vigilar que no esté marcada "Copy to
project") y luego ya editarlos en Vivado.

Depués, no olvidar regenerar el fichero Tcl con : "File" -> "Project" -> "Write Tcl...". Asegurarse
de nuevo de que no esté marcada la opción "Copy to project".

## Diagrama de bloques

![Diagrama de bloques 1](/assets/images/block_diagram_221207.png)

![Diagrama de bloques 2](/assets/images/block_diagram_221129.png)

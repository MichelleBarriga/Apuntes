# Apuntes
## Comandos
### git init
El comando `git init` es utilizado para iniciar un repositorio dentro de una carpeta ya existente. Y si se quiere crear un proyecto desde 0 se usa el comando `git init nombre-proyecto`.

### git commit
Los commits son las unidades centrales de la línea de tiempo de un proyecto Git. Los commits se crean con el comando `git commit` para capturar el estado de un proyecto en ese momento. 

### git commit -m
Se utiliza `git commit -m` para poder subir un commit con su mensaje respectivo.

### git add
El comando `git add` agrega un cambio en el directorio de trabajo al área de preparación (Pasa de modified a staged).

### git status
El comando `git status` muestra el estado del directorio de trabajo y el área de preparación. Permite ver qué cambios se han establecido, cuáles no y qué archivos no están siendo tomados en cuenta por Git.

### git log
El comando `git log` muestra los commits realizados.

### git restore
El comando `git restore` restaura la versión previa de un fichero.

### git branch
El comando `git branch` sirve para crear ramas.

### git switch
El comando `git switch` es utilizado para movernos de una rama a otra. 
## Preguntas interesantes
### ¿Cuáles son los estados en git?
- Modified
- Staged
- Committed
### ¿Qué es el HEAD?
> Es el puntero que referencia el punto actual del historial de cambios del repositorio en el que estas trabajando.
### ¿Para qué sirve una rama en git?
- Desarrollar nuevas funcionalidades.
- Corregir errores.
- Experimentar nuevas ideas en un área segura.
- etc.
### Si se elimina una rama
### ¿Qué pasa si al querer fusionar 2 ramas, la de destino ha realizado cambios en las mismas lineas del fichero que queremos fusionar?
Se genera un conflicto, un conflicto es...

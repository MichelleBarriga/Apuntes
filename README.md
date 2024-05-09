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


#### git branch --delete
Para eliminar ramas se usa: `git brach --delete`.

#### git branch -a
Para poder visualizar las ramas tanto remotas como locales se usa: `git branch -a`.

### git switch
El comando `git switch` es utilizado para movernos de una rama a otra. \
El comando `git switch -c` crea una rama y te lleva a esta en un solo paso.

### git merge
Utilizamos `git merge` para fusionar los cambios de una rama a la que nos encontramos en ese momento.
### git remote

#### git remote add
El comando `git remote add <alias> <direccion>` sirve para enlazar un repositorio local con uno remoto.

#### git remote prune
El comando `git remote prune <alias>` sirve para eliminar ramas de mi repositorio local que ya no se usan en el reporsitorio remoto.

### git push
El comando `git push` permite enviar los cambios de un repositorio local a
un repositorio remoto. Se le pasa 2 parametros (el alias del repositorio remoto y la rama sobre la que queremos enviar los cambios) `git push <alias> <rama>`.

### git fetch
Se utiliza `git fetch` para actualizar cambios.

### git clone
Se utiliza `git clone <url_repositorio>` para clonar un repositorio remoto.



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

### ¿Qué pasa si al querer fusionar 2 ramas, la de destino ha realizado cambios en las mismas lineas del fichero que queremos fusionar?
Se genera un conflicto, un conflicto es una situación el la que git no es capaz de determinar que cambio tiene que mantener.

### Diferencia entre Git y GitHub
- **Git** es el sistema de control de versiones.
- **GitHub** es un servicio de alojamiento en la nube de código fuente.

### ¿Por qué no me deja hacer push?
Normalmente esto se debe a que hay cambios en repositorio remoto que no hay en el repositorio local, esto ocurre generalmente al trabajar con un equipo de desarrolladores.

### ¿Qué es un pull request?
Es una petición de cambios que se envía al repositorio original.

### ¿Para qué sirve marcar un pull request como draft?
Para dar visibilidad a los cambios que quieres realizar, y puedas empezar a recibir comentarios pero dejas bien claro que todavía no está terminado.
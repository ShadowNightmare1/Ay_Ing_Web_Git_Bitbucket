# Glosario

### Control de Versiones (VC)
	
> Herramienta que sirve para mantener un historial de los cambios realizados a un archivo o conjunto de archivos. Y en caso de haber realizado alg�n cambio que desencadenara alguna falla en los archivos, poder volver a una versi�n anterior funcional sin mayor problema.
>[Source](https://git-scm.com/book/es/v1/Empezando-Acerca-del-control-de-versiones) 
	
### Control de Versiones Distribuido (DVC)

> Similar al VC, con la diferencia de que no es necesario que el usuario est� siempre conectado al servidor, y adem�s de que cada uno mantiene una copia completa del repositorio.
>[Source](http://www.mclibre.org/consultar/informatica/lecciones/git.html)

### Repositorio Remoto
	
> Versi�n de un proyecto que se encuentra en l�nea, al que se puede acceder dependiendo de los permisos del mismo.
>[Source](https://git-scm.com/book/es/v1/Fundamentos-de-Git-Trabajando-con-repositorios-remotos)
	
### Repositorio Local
	
> Versi�n del proyecto que se encuentra en el computador.
>[Source](https://colaboratorio.net/atareao/developer/2017/git-y-github-trabajando-con-repositorios-locales/)

### Copia de Trabajo / *Working Copy*

> Es en s� una repo, que permite subir los cambios de la misma, a la versi�n en el servidor. Por otro lado, tambi�n es posible actualizar la working copy descargando los cambios que presenta con la versi�n en l�nea.
> [Source](https://www.thomas-krenn.com/en/wiki/Git_Basic_Terms)

### Área de Trabajo / *Staging Area*

> Un archivo que generalmente está contenido en el directorio git del proyecto. Se encarga de almacenar lo que irá en el próximo commit (Similar a un Index, pero se estandarizó llamarlo Staging Area).
> [Source](https://git-scm.com/book/en/v1/Getting-Started-Git-Basics)

### Preparar Cambios / *Stage Changes*

> Hace referencia a añadir sólo las líneas que han cambiado a la Staging Area, para poder después subir dichos cambios a la repo remota.
> [Source](https://softwareengineering.stackexchange.com/questions/119782/what-does-stage-mean-in-git)

### Confirmar Cambios / *Commit Changes*
> El último paso para confirmar y guardar los cambios hechos a la repo local. Se almacena con un comentario para poder llevar un registro de los cambios hechos, y cuando fue hecho (generalmente el comentario es una breve descripción bastante explicativa de los cambios hechos). Cabe señalar que los cambios son guardados a nivel local.
> [Source](https://www.git-tower.com/learn/git/commands/git-commit)

### *Commit*
> Comando que permite realizar lo anterior descrito.
> [Source](https://www.git-tower.com/learn/git/commands/git-commit)

### *Clone*
> Consiste en clonar un repositorio existente. En términos más simples, es bajar toda la carpeta del proyecto o parte de ella, ya que es posible solamente bajar la versión existente en algún branch específico.
> [Source](https://git-scm.com/book/es/v1/Fundamentos-de-Git-Obteniendo-un-repositorio-Git)

### *Pull*
> Consiste en descargar los datos que han cambiado en alguna de las *staging areas* presentes en los colaboradores de la repo.
> [Source](https://git-scm.com/book/es/v1/Fundamentos-de-Git-Trabajando-con-repositorios-remotos)

### *Push*
> Consiste en enviar los datos que han cambiado en la *staging area* local, al servidor donde se ubica la repo.
> [Source](https://git-scm.com/book/es/v1/Fundamentos-de-Git-Trabajando-con-repositorios-remotos)


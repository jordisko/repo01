# **PASOS PARA CREAR UN REPOSITORIO**
*En nuestro caso utilizaremos Git Bash y la plataforma GitHub* 

Comandos utiles para empezar:
- Abriremos Git Bash, para situarnos en que directorio estamos podemos utilizar la comanda "**pwd**".
- Con "**ls**"" se nos listará el contenido del directorio actual.
- Para movernos por los direfentes directorios utilizaremos "**cd \<nombre de directorio>**" para avanzar a \<nombre de direcotrio> y "**cd ..**"" para retroceder.
- Podemos crear un directorio de forma tradicional o desde la consola de Git : "**mkdir**".  
- Necesitamos también crear el documento que subiremos a nuestro repositorio, para ello podemos hacerlo otra vez de la forma tradicional con las herramientas de windows o podemos utilizar "**code .**" para abrir el directorio en *Visual Studio Code* y una vez ahí crear nuestro documento.  
- Para poder visualizar nuestro repositorio deberemos de activar la visualización de elementos ocultos, también nos será util visualizar las extensiones de los nombre de los archivos. Todo ello lo podremos activar desde el menu Vista de qualquier carpeta.
- Con el comandamiento "**git status**" podremos ver el estatus de nuestro repositorio.
  
  
## Con estas herramientas ya podremos crear nuestro repositorio local y conectarlo con un repositorio remoto que habremos creado.  

1. Contamos que hemos seguido las instruciones anteriores y por tanto ya tenemos creado nuestro documento que está alocado en lo que llamaremos a partir de ahora como "Working Directory".
2. Para que nuestro directorio funcione como repositorio utilizaremos :  "**git innit**".(estando seguros que estamos dentro del directorio en el que queramos crear nuestro repositorio, nos ayudará la comanda "**pwd**")
3. Podemos subir los documentos que tengamos en nuestro Working Directory al "Staging Area" que será un punto intermedio entre nuestro Working Directory y el "Repositorio Local". Subimos los documentos a la Staging Area con la comanda : "**git add \<file>**" donde \<file> es el nombre de nuestro documento. Podemos hacer una subida masiva de documentos con : "**git add .**".
4. Una vez subidos estos documentos a nuesta Staging Area podremos quitarlos con: "**git rm --cached \<file>**"" donde file es el nombre del documento que queramos quitar.
5. Una vez tenemos nuestros documentos en la Staging Area ( recordamos podemos chequearlo con la comanda "**git status**" ) podremos hacer nuestro *Snapshot* es decir subirlo a nuestro Repositorio Local. Esto lo haremos con: "**git commit -m "comentario"**" de esta manera subiremos TODOS los archivos que estén en nuestra Staging Area al repositorio, podemos chequear que archivos tenemos en este con la comanda: "**git log**".

Siguiendo estos pasos habremos conseguido crear nuestro repositorio

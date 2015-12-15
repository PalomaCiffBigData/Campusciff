# Campusciff
Clonar repositorio: 
- es necesaria la instruccion git clone URL-Repositorio, para mi git@github.com:PalomaCiffBigData.git. Para poder clonarlo, el sistema nos pide la clave privada.

Commit inicial y subida al repositorio remoto: 
- para poder realizar un commit, primero hay que subir los datos a la staging area mediante el comando git add y ya estaremos en disposicion de realizar el commit para subir los cambios al repositorio localy de aqui al repositorio remotomediante el comando git push NombreRama.

Git ignore archivos/carpetas:
- hay que especificarselo mediante el comando.gitignore

Crear una segunda rama remota:
- mediante el comando git branch y nos situaremos en ella mediante el comando git checkout 
- o podemos realizar ambas acciones mediante un solo comando git checkout -b.

Merge con conflicto:
- Cambiamos los texto de los ficheros 1.txt de cada rama y al intentar realizar el merge nos da error ya que estos son diferentes y no sabe cual es el correcto.
- vemos las diferencias entre las ramas con el comando git brach --merge/--no-merge
- para solucionar el problema devemos indicar cual de los dos ficheros es el correcto, es decir, subirlo al staging area y asi ya poder realizar el commit.

Borrar rama:
- para borrar una rama se utiliza el comando git branch -d NombreRama (v0.2)





Creamos una tabla con los datos de algunos de los compañeros de clase

|Nombre   |Github                             |
|---------|----------------------------------:|
|Jose Dios|http://github.com/jrdios           |
|Sara     |https://github.com/ciffSara        |
|Macarena |https://github.com/macarenagaranena|
|Miguel   |https://github.com/MiguelCerdan    |


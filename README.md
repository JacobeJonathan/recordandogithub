## PlatziCursoGithub
Primer entrar a la carpeta del proyecto ojo "Tenemos que tener una cuenta en github y descargar git como tambien habilitar en el path" y creamos el repositorio en github.Luego poner estos comandos :
  - git config --global user.email "you@example.com"
  - git config --global user.name "Your Name"
  - git init (Sirver para crear un init en la carpeta del proyecto " es como un repositorio de Db")
  - git remote add origin link (en la aprte del link pegar el repositorio creado en github)
  - git status ( para ver los archivos estaran de color rojo)
  - git add * ( para agregar todos los achivos y enter)
  - git status ( y se pondra ahora de verde todo)
  - git commit -m "aqui frase" (en aqui frase poner ejemplo version 1 = sirve para ver los cambios)
  - git push origin master ( para subirpor fin todos los archivos)

Y ve a tus REPOSITORIO en GITHUB y observaras que ya se subio todo los archivos

##Como hacer cambios en un repositorio de git
  - git clone "link" ( Primero clonamos es repositorio = donde dice link pegar el link del repositorio)
  - git status (para ver si estan todos los archivos)
  - git add . (. es un punto es igual que el * los dos suben todo " subimos el archivo)
  - git commit - m "version 2" (Segundo realizamos un commit = donde version 2 puede ir los cambios que se realizaron al anterior archivo)
  - git push origin master
  - git show (Cuarto vemos todos los cambios hechos ejemplo hola jonathan " esto estara en rojo " hola jonathan jacob " estara en verde y es la nueva version ")

##Ver el archivo oculto de git en windows
  - Ir a la carpeta win + e
  - Ve a vista
  - Habilitar el que dice comandos ocultos i nos aparecera un ".git"

##Comandos para repositorios remotos
  - Git push
##Comados basicos
  - pwd ( nos dice en que carpeta estamos )
  - cd / (  para ir al inico i nos lsadra un / cd es para navegar por carpetas)
  - Ñ ( Si me aparece el signo de arriba de la Ñ es porqeu estmaos en una carpeta )
  - ls ( archivos que estan en todas la raiz )
  - Clear ( limpiar toda la pantalla )
  - cd .. ( para retroceder una carpeta )
  - mkdir proyectos1 ( mkdir = crea la carpeta proyecto1 = es el nombre )
  - history ( nos muestra todos los comandos que emos hecho )

##Ver todos los cambios por ID y volver a la version anterior de un codigo
  - Git log ( para ver todos los commits )
  - Git reset 6c8840989521d6441943feb2780f766ca73aa28e --hard ( el numero sale cuando hacemos el "GIT LOG" ejemplo  commit 6c8840989521d6441943feb2780f766ca73aa28e
el --hard hace volver todo al anteior co --soft algunas partes )
  - Git diff ( sirve para hacer diferencias )

##Para ver nuestra configuracion es dcir nuestro usuario y correo que emos puesto al inicio y creamos las llaves ssh
  - Git config -l ( ojo debemos estar fuera de ( master ) con cd .. salimos de master )
  - git config --global user.email "jonathanf4.32@hotmail.com" ( cambiamos el email )
  - git config -l ( miramos si se cambio )
  -  ssh-keygen -t rsa -b 4096 -C "75171766@continental.edu.pe" ( solo enter y enter l orecomendable es poner nombre )
  -  $ eval $(ssh-agent -s) (no saldra estoAgent pid 938)
  -  ssh-add ~/.ssh/id_rsa

##Conexion por ssh
  - 



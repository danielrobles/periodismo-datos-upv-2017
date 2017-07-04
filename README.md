# Curso de Periodismo de Datos UPV 2017

## Docente
ADOLFO ANTÓN

https://twitter.com/adolflow

gh @flowsta

infotics.es

blog.infotics.es

Doctor Ciencias Información 2016 UCM

## Revisar
- https://html5up.net/
- https://www.startpage.com/
- Alberto Cairo, libro 2012 El País, para elegir gráficos. The Functional Art' (2012) Knight Chair at the University of Miami. Author of 'The Truthful Art' (2016), and 'The Functional Art' (2012) 
- #periodismodatos 
- Taller de periodismo de datos 2017 - La España vacía PROYECTOS
- Tableau
- http://pad.haroopress.com/user.html
  
## Antes de empezar
1 NAVEGADOR 

2 EDITOR DE TEXTO con capacidades Markdown
	Favorito Emacs (curva de aprendizaje alta)
	Notepad++
	Sublime https://www.sublimetext.com/
	
3 PROGRAMAS
	Consola (por defecto en Mac y Linux)
	Consola Windows CYGWIN

## Test

[UPV](http://www.upv.es "UPV")

## Día 2


```
# /etc/nsswitch.conf
#
#    This file is read once by the first process in a Cygwin process tree.
#    To pick up changes, restart all Cygwin processes.  For a description
#    see https://cygwin.com/cygwin-ug-net/ntsec.html#ntsec-mapping-nsswitch
#
# Defaults:
# passwd:   files db
# group:    files db
# db_enum:  cache builtin
# db_home:  /home/%U
# db_shell: /bin/bash
# db_gecos: <empty>
db_home:  /%H
```

```
Last login: Mon Jun 12 20:25:42 on console
veraw140-220:~ drobles$ cd /Users/drobles/Dropbox/2017\ CURSO\ PERIODISMO\ DE\ DATOS/periodismo-datos-upv-2017-master/periodismo-datos-upv-2017-master 
veraw140-220:periodismo-datos-upv-2017-master drobles$ ls
LICENSE		README.md
veraw140-220:periodismo-datos-upv-2017-master drobles$ ls -a
.		..		LICENSE		README.md
veraw140-220:periodismo-datos-upv-2017-master drobles$ git init
xcode-select: note: no developer tools were found at '/Applications/Xcode.app', requesting install. Choose an option in the dialog to download the command line developer tools.
veraw140-220:periodismo-datos-upv-2017-master drobles$ p
Display all 173 possibilities? (y or n)
veraw140-220:periodismo-datos-upv-2017-master drobles$ pw
pwd         pwd_mkdb    pwhich      pwhich5.16  pwhich5.18  pwpolicy    
veraw140-220:periodismo-datos-upv-2017-master drobles$ pwd
/Users/drobles/Dropbox/2017 CURSO PERIODISMO DE DATOS/periodismo-datos-upv-2017-master/periodismo-datos-upv-2017-master
veraw140-220:periodismo-datos-upv-2017-master drobles$ git init
Initialized empty Git repository in /Users/drobles/Dropbox/2017 CURSO PERIODISMO DE DATOS/periodismo-datos-upv-2017-master/periodismo-datos-upv-2017-master/.git/
veraw140-220:periodismo-datos-upv-2017-master drobles$ ls -a
.		..		.DS_Store	.git		LICENSE		README.md
veraw140-220:periodismo-datos-upv-2017-master drobles$ ls
LICENSE		README.md
veraw140-220:periodismo-datos-upv-2017-master drobles$ ls -a
.		..		.DS_Store	.git		LICENSE		README.md
veraw140-220:periodismo-datos-upv-2017-master drobles$ cd
veraw140-220:~ drobles$ cd
veraw140-220:~ drobles$ pwd
/Users/drobles
veraw140-220:~ drobles$ cd /Users/drobles/Dropbox/2017\ CURSO\ PERIODISMO\ DE\ DATOS/periodismo-datos-upv-2017-master/periodismo-datos-upv-2017-master 
veraw140-220:periodismo-datos-upv-2017-master drobles$ pwd
/Users/drobles/Dropbox/2017 CURSO PERIODISMO DE DATOS/periodismo-datos-upv-2017-master/periodismo-datos-upv-2017-master
veraw140-220:periodismo-datos-upv-2017-master drobles$ ls -a
.		..		.DS_Store	.git		LICENSE		README.md
veraw140-220:periodismo-datos-upv-2017-master drobles$ pwd
/Users/drobles/Dropbox/2017 CURSO PERIODISMO DE DATOS/periodismo-datos-upv-2017-master/periodismo-datos-upv-2017-master
veraw140-220:periodismo-datos-upv-2017-master drobles$ cd c:
-bash: cd: c:: No such file or directory
veraw140-220:periodismo-datos-upv-2017-master drobles$ cd C:
-bash: cd: C:: No such file or directory
veraw140-220:periodismo-datos-upv-2017-master drobles$ pdw
-bash: pdw: command not found
veraw140-220:periodismo-datos-upv-2017-master drobles$ ls
LICENSE		README.md
veraw140-220:periodismo-datos-upv-2017-master drobles$ ls -a
.		..		.DS_Store	.git		LICENSE		README.md
veraw140-220:periodismo-datos-upv-2017-master drobles$ data
-bash: data: command not found
veraw140-220:periodismo-datos-upv-2017-master drobles$ cd readme
-bash: cd: readme: No such file or directory
veraw140-220:periodismo-datos-upv-2017-master drobles$ cd ../
veraw140-220:periodismo-datos-upv-2017-master drobles$ pwd
/Users/drobles/Dropbox/2017 CURSO PERIODISMO DE DATOS/periodismo-datos-upv-2017-master
veraw140-220:periodismo-datos-upv-2017-master drobles$ ls
periodismo-datos-upv-2017-master
veraw140-220:periodismo-datos-upv-2017-master drobles$ cd periodismo-datos-upv-2017-master
veraw140-220:periodismo-datos-upv-2017-master drobles$ pwd
/Users/drobles/Dropbox/2017 CURSO PERIODISMO DE DATOS/periodismo-datos-upv-2017-master/periodismo-datos-upv-2017-master
veraw140-220:periodismo-datos-upv-2017-master drobles$ mv periodismo-datos-upv-2017-master/ upv-pd
mv: rename periodismo-datos-upv-2017-master/ to upv-pd: No such file or directory
veraw140-220:periodismo-datos-upv-2017-master drobles$ mv periodismo-datos-upv-2017-master upv-pd
mv: rename periodismo-datos-upv-2017-master to upv-pd: No such file or directory
veraw140-220:periodismo-datos-upv-2017-master drobles$ pwd
/Users/drobles/Dropbox/2017 CURSO PERIODISMO DE DATOS/periodismo-datos-upv-2017-master/periodismo-datos-upv-2017-master
veraw140-220:periodismo-datos-upv-2017-master drobles$ pwd
/Users/drobles/Dropbox/2017 CURSO PERIODISMO DE DATOS/periodismo-datos-upv-2017-master/periodismo-datos-upv-2017-master
veraw140-220:periodismo-datos-upv-2017-master drobles$ mv periodismo-datos-upv-2017-master
usage: mv [-f | -i | -n] [-v] source target
       mv [-f | -i | -n] [-v] source ... directory
veraw140-220:periodismo-datos-upv-2017-master drobles$ rename periodismo-datos-upv-2017-master upv-pd
-bash: rename: command not found
veraw140-220:periodismo-datos-upv-2017-master drobles$ cd ..\
> pwd
-bash: cd: ..pwd: No such file or directory
veraw140-220:periodismo-datos-upv-2017-master drobles$ cd ../
veraw140-220:periodismo-datos-upv-2017-master drobles$ pwd
/Users/drobles/Dropbox/2017 CURSO PERIODISMO DE DATOS/periodismo-datos-upv-2017-master
veraw140-220:periodismo-datos-upv-2017-master drobles$ mv periodismo-datos-upv-2017-master upv-pd
veraw140-220:periodismo-datos-upv-2017-master drobles$ ls
upv-pd
veraw140-220:periodismo-datos-upv-2017-master drobles$ cd upv-pd
veraw140-220:upv-pd drobles$ ls
LICENSE		README.md
veraw140-220:upv-pd drobles$ mkdir otro-test
veraw140-220:upv-pd drobles$ touch otra-cosa/aburrimientototal.md
touch: otra-cosa/aburrimientototal.md: No such file or directory
veraw140-220:upv-pd drobles$ touch aburrimientotal.md
veraw140-220:upv-pd drobles$ more readme.me
readme.me: No such file or directory
veraw140-220:upv-pd drobles$ pwd
/Users/drobles/Dropbox/2017 CURSO PERIODISMO DE DATOS/periodismo-datos-upv-2017-master/upv-pd
veraw140-220:upv-pd drobles$ more readme
readme: No such file or directory
veraw140-220:upv-pd drobles$ more Readme.md
# Curso de Periodismo de Datos UPV 2017

## Docente
ADOLFO ANTÓN

https://twitter.com/adolflow

gh @flowsta

infotics.es

blog.infotics.es

Doctor Ciencias Información 2016 UCM

## Revisar
- https://html5up.net/
- https://www.startpage.com/
- Alberto Cairo, libro 2012 El País, para elegir gráficos. The Functional Art' (2012) Knight Chair at the University of Miami. Author of 'The Truthful Art' (2016), and 'The Functional Art' (2012) 
- #periodismodatos 
- Taller de periodismo de datos 2017 - La España vacía PROYECTOS
- Tableau
- http://pad.haroopress.com/user.html
  
## Antes de empezar
1 NAVEGADOR 

2 EDITOR DE TEXTO con capacidades Markdown
        Favorito Emacs (curva de aprendizaje alta)
        Notepad++
        Sublime https://www.sublimetext.com/
        
3 PROGRAMAS
        Consola (por defecto en Mac y Linux)
        Consola Windows CYGWIN

## Test

[UPV](http://www.upv.es "UPV")

###### Hola
veraw140-220:upv-pd drobles$ 
```

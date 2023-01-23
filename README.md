# Application-Web-Design
## Actividad 1
Nombre: Johann Eduards Tabares Villalobos

Matricula: 2972975

Carrera: Ing de Desarrollo de Software

Clase: Diseño de aplicaciones web

Maestro: Erik Ezequiel Carrillo Moo

# Como sirve Markdown

Markdown es un lenguaje de marcado sencillo que sirve para agregar formato, vínculos e imágenes con facilidad al texto simple. Se puede utilizar en los siguientes lugares: Comentarios de ticket (desde la interfaz del usuario)

# Tarea 1 opciones de etiquetado que ofrece Markdown. 

## Ejemplo 1 *cursiva*

*Todas las mañanas me levanto a las 10 am*

## Ejemplo 2 **negrita**

**Github es una buena herramienta**

## Ejemplo 3 Negrita y cursiva

___Texto en cursiva y negrita___

## Ejemplo 4 Tachado

~~Este texto está tachado.~~ este texto no esta tachado.

## Ejemplo 5 Listas

1. Lista numero 1
2. Lista numero 2
3. Lista numero 3

## Ejemplo 6 Código

```html
<html>
  <head>
  </head>
</html>
```  
# Parte 2 comandos utilizados en git 

## a) Verificar el estado de un repositorio local. 

git status -s

git status se utiliza para ver si los documentos esta en github si no lo estan marcan en rojo

luego de utilizar git add . y volvemos a utilizar git status y este marcara como verde que se han subido.

## b) Agregue archivos individuales o globalmente

git add . es para agregar los documentos para prosegir con el siguiente comando.

## c) Agregar comentarios a la confirmación. 

git commit -m "Intriduces mensaje para el repositorio"

este comando se utiliza para dar un mensaje del cambio que le hiciste al repositorio y no perderte.

## d) Cargue sus cambios en el repositorio remoto

git push -u origin master

Sirve para cargar nuestros cambios que hicimos
 
a lo largo de nuestro trabajo ya que es muy importante

subir para hacer copia de respalfo y no perder el progreso.

## e) Cree, explore y elimine sucursales.

 git checkout -b (name of branch)

 Este comando nos river para cambiar su nombre rapidamente solo colocando

 el comando que se menciona arriba sin tener que hacerlo desde github 

 es una ventaja muy util para proximos trabajos.

 ## f) Revertir un repositorio a una confirmación específica

  git log --oneline y git reset --hard

  git log es una herramienta en donde esta nos ayuda

  a poder explorar el historial de repositorio donde
  
  se encuentran los cambios, que hemos agregado,

  que se ha eliminado.

  git reset --hard 

  nos ayuda a restaurar el elemento que eliminamos resientemente

  para hacer este comando primero ejecutamos git log para ver el historial

  cuando hacemos este comando podemos ver un numero el cual este nos ayudara

  a restaurar con el comando git reset --hard (**numero**) y asi se restaura 

  el ultimo elemento que teniamos agregado.







---
lang: es
---

# literatura
Repaso de comandos de git y de github a raíz de una actividad de Juan Luis.

## Introducción

Aprovecho la actividad de gestión de ramas en un repositorio local para incorporar la forma de gestionarlo en la nube y probar ciertas opciones que nos faciliten las tareaas.


## Actividad

Las tareas que llevaremos a cabo son las siguientes:

1. Crear un repositorio en la nube.
1. Clonar el repositorio en nuestro equipo.
1. Prepararnos para trabajar.
1. Crear el archivo autores. Confirmar los cambios y subirlo a la nube.
1. Crear la rama cuentos, añadir un par de cuentos y confirmar los cambios.
1. Crear la rama novelas, añadir un par de novelas y confirmar los cambios.
1. Actualizar el repositorio en la nube.
1. Fusionar la rama cuentos y eliminarla.
1. Fusionar la rama novelas y eliminarla.
1. Actualizar los cambios en la nube.


## Creación del repositorio

Bastaría con entrar a [la web para crear un repositorio](https://github.com/new) y poner los datos que nos interesa en el formulario.

Con respecto a lo ya visto en clase, sólo agregaré que el README se crea con un encabezado de nivel 1 con el nombre del repositorio, seguido de un párrafo con lo que pongamos en el campo de la descripción.

## Clonar el repositorio

Estando en la carpeta en la que queremos que se guarde el repositorio ejecutamos el comando que ya conocemos.

```
git clone https://github.com/usuario/repositorio
```


## Prepararse para trabajar

Podríamos pensar en la clonación como copiar y pegar (aunque no sea así). Si estamos en la carpeta apuntes y copiamos en ella la carpeta ejemplos, tendremos la carpeta ejemplos dentro de apuntes, pero nosotros estaremos en la carpeta apuntes. Por lo tanto, si queremos modificar un ejemplo tendremos que entrar en ejemplos.

Al clonar el repositorio nos ha puesto una carpeta con el nombre y, dentro de ella, el contenido del mismo. Pero necesitamos que la consola entre en la carpeta.

Si queremos saber en qué carpeta está la consola ejecutamos estra instrucción.

```
cd
```

Si queremos cambiar a la carpeta del repositorio (que está dentro de la carpeta actual) haremos este comando:

```
cd nombreDelRepositorio
```


## Crear el archivo de autores, confirmar cambios y subir

Crearemos el archivo autores.txt. Aquí prefiero que cada uno lo haga como le parezca más fácil, porque los comandos de creación de archivos por consola difieren de una a otra. Lo importante es que este archivo esté en la carpeta del repositorio.

Los cambios se añaden como siempre.

```
git add .
```


Los cambios se confirman como siempre.

```
git commit -m "Tenemos a los autores."
```


Y la versión de la nube se actualiza como hemos hecho en clase.

```
git push
```
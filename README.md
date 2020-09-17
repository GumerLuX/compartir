# Compartir desde windows, linux y VirtualBox

## Creacion

Creamos el archivo notas desde windows y activamos el .gitignore
Creamos los scripts desde la consola y los subimos con VS.

```sh
  > touch install.sh disco.sh kernel.sh root.sh usuario.sh
  > Le damos permisos de ejecucion.
  > chmod +x install.sh disco.sh kernel.sh root.sh usuario.sh
```

Le damos a git en VS y creamos un comit crear "scriptd.sh"

En los tres puntos boton derecho -> commit -> confirmar

-> y ponemosel nombre del commint -> crear "scriptd.sh"

En los tres puntos boton derecho -> "pull""puss" -> sincronizar

Actualizamos el navegador y los vemos subidos.

# Editar desde Github y bajar cambios al repo local. (PC)

Hemos editado el archivo README.md

> Para actualizar el repo local utilizamos el comando git pull:
> `$ git pull`

Posible error es que no tengamos asignada una rama a nuestro repositorio local,
lo podemos solucionar caon este camando:

`git branch --set-upstream-to-origin-/master master`

haora si tiene que funcinar, hacemos:

`$ git pull`
`$ git log` -> para ver los cambios efectuados.

---

Si lo hacemos desde VS vamos directo a los tres puntos boton derecho del mousse:

> -> "pull""puss" -> sincronizar.

Se bajaran los cambias realizados.

---

Ahora editamos desde github,con una maquina de VirtualBox con Arclinux plasma.

> 1- Hemos entrado en el github y nos hemos identificado.

> 2- Abriremos una terminal y clonamos el git:

`git clone https://github.com/SinLuX90/compartir.git`

> 3- Nos descargamos el git y hacemos un init:

`cd compartir`  -> entramos en el directorio:

`git init`

# REQUERIMIENTOS

 - gedit >=2.15.2
 - Python >=2.6
 - PyGTK >=2.12
 - GTK+ >=2.10.14
 - PyEnchant (opcional, necesario para corrector ortográfico)
 - Poppler Python Bindings (opcional, necesario para visor PDF embebido)

# INSTALACION

- Descomprimir el archivo si se descargó de SourceForge.
- Crear el siguiente directorio:
    ~/.gnome2/gedit/plugins
    - cd ~
    - mkdir .gnome2
    - mkdir .gnome2/gedit
    - mkdir .gnome2/gedit/plugins
- Ir a la carpeta plugins:
    - cd .gnome2/gedit/plugins
- En la carpeta clonar el repositorio de GitHub
    - git clone https://github.com/lazcol/geditLatexPlugin.git
- Eso creará el árbol de directorios necesario
- Por último se debe mover el archivo 'GeditLaTeXPlugin.gedit-plugin' desde la carpeta clonada a la carpeta 'plugins'
    - mv GeditLaTeXPlugin/GeditLaTeXPlugin.gedit-plugin .GeditLaTeXPlugin.gedit-plugin
- Reiniciar gedit y activar el plugin en la configuración.

El árbol de directorio tiene que quedar así
~/.gnome2/gedit/plugins/.
                  │
                  ├─ /GeditLaTeXPlugin/
                  └─ GeditLaTeXPlugin.gedit-plugin

A modo de no perder el archivo, lo he dejado adentro del directorio GeditLaTeXPlugin.
Cuestión que hay que copiarlo para armar el directorio tal cual se encuentra diagramado.

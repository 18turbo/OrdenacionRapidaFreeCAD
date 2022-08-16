# OrdenacionRapida
En FreeCAD, ordena rápidamente grupos según el orden de selección

### Instalación detallada

1. Copia todo el contenido de este script (macro) a tu ordenador, en la carpeta "macros" de tu FreeCAD.
**NOTA:** Para saber la carpeta "macros" de tu FreeCAD, ve a **Editar --> Preferencias**. Luego pincha en la izquierda "General". Después pincha en la pestaña Macros y mira "Ruta de la macro".
2. Abre FreeCAD (si no lo has hecho). En el menú superior, pincha en **Macro --> Macros...**
3. En la ventana que aparece, pincha en el botón de la derecha "Crear"
4. Pon un nombre para la macro, por ejemplo: "Ordenación Rápida", y pincha en Aceptar.
5. Aparecerá una pestaña de FreeCAD en blanco.
6. Copia el contenido del fichero **Ordenación.FCMacro** y peǵalo a la ventana en blanco. Para hacerlo, abre el fichero con cualquier editor de texto, selecciona TODO, cópialo con CTRL-C y pégalo en el documento en blanco con CTRL-V
7. Pincha en **Archivo --> Guardar**
8. Cierra la pestaña.
9. Vuelve a ir  al menú superior **Macro --> Macros...**
10. Ahora, en el área de la izquierda de la ventana que aparece, selecciona el nombre que le pusiste a la macro.
11. Luego pincha en el botón de la derecha "Barra de herramientas".
12. En la nueva ventana, en la parte central, debes rellenar, como mínimo: el campo **Macro** (seleccionando en el desplegable el nombre de la macro que pusiste); el **Texto del menú**, donde poner un nombre; y **Pixmap**, donde habrá que seleccionar un icono. Usa si lo ves bien, el icono SVG suministrado en la macro.
13. Cuando termines de rellenar los campos anteriores, pincha el botón "Añadir". Esto hará que la macro aparezca en el área de la izquierda con el icono que hayas seleccionado.
14. Selecciona la pestaña superior "Barra de Herramientas". En la parte de la izquierda, abre el desplegable y selecciona "Macros" **(no macro, en singular)**.
15. En la parte inferior del desplegable, aparecerá la macro que hemos creado.
16. Ahora en la parte de la derecha, elige el banco de trabajo donde quieres que aparezca el icono para ejecutar la macro.
17. Cuando hayas seleccionado el banco, pincha en el botón NUEVO para crear una barra de herramientas nueva en ese banco de trabajo donde pasaremos la macro. Pon un nombre y dale a "Aceptar"
18. Selecciona la macro de la izquierda y pulsa la flecha a la derecha "-->" y verás que pasa la macro a la barra creada.
19. Pincha en "Cerrar" en todas las ventanas.
20. Aunque el proceso está hecho, es posible que no veas el icono de la barra hasta que cambies de banco de trabajo o reinicies FreeCAD.


### Actualización

Para actualizar una versión anterior a la actual:
* Copia el nuevo contenido y sustituye los ficheros que tienen el nombre igual por los nuevos.
* Abre FreeCAD
* Pincha en el menú superior **Macro --> Macros...**
* En la nueva ventana, selecciona la macro que quieras actualizar en la parte de la izquierda.
* En la parte de la derecha, pincha el botón **Editar**.
* Selecciona todo el código y bórralo. Para ello, normalmente puedes usar el atajo de teclado **CTRL - A**, y luego la tecla **SUPR**
* Abre el archivo nuevo con cualquier editor de textos, y copia todo el código, normalmente con el atajo de teclado **CTRL - C**
* Ve de nuevo a FreeCAD (donde habías borrado el código) y pega el contenido nuevo, normalmente con el atajo de teclado **CTRL - V**
* Guarda la macro, normalmente con el atajo de teclado **CTRL - S**
* Reinicia FreeCAD, o algún banco de trabajo para que los cambios tengan efecto.


### Funcionamiento

Selecciona los grupos por el orden que quieres ordenarlos con la tecla CTRL pulsada. Luego pulsa el icono de la macro para que los ordene.



### Notas

Solo funciona con grupos de FreeCAD que tengan padre.

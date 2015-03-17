# Introducion #

Modificaciones y optimizaciones a realizar


# Detalles #

| Usar dash en lugar de bash como shell del sistema (25% menos de memoria y mayor velocidad de carga) | Hecho | |
|:----------------------------------------------------------------------------------------------------|:------|:|
| Eliminar terminales virtuales no utilizadas (Ctrl+Alt+fn[1-6]) | Hecho |  |
| Activar DMA en hda y cd-rom | Hecho |  |
| Eliminar modulos lp y nfs | Hecho |  |
| Cargar terminal y teclado al arrancar | Hecho |  |
| Poner locales en español | Hecho |  |
| Poner teclado en español |  |  |
| Poner zona horaria en español | Hecho |  |
| Usar repositorio español | Hecho |  |
| Eliminar usuarios inutiles | Hecho |  |
|  Personalizar usuario principal (login) |  |  |
| Cambiar $HOME de /home/

&lt;user&gt;

 a /home (solo habra un unico usuario) | Hecho |  |
| Hacer script de instalacion con posibilidad de personalizacion (zona horaria, repositorios, usuarios...) |  |  |
| Arreglar scripts defectuosos con dash (issues y alguno mas) | Hecho | Estan plagados de bashicismos segun https://wiki.ubuntu.com/DashAsBinSh, cambiado #/bin/sh por #/bin/bash |
| Hacer un bootsplash personalizado |  |  |
| Dash como /bin/sh | Hecho | dpkg-reconfigure dash |
| Recompilar todos (o al menos los principales) paquetes para arquitectura i686 en lugar de la i386 de serie e incorporarlos al repositorio |  | Usar apt-build y despues subirlos |
| Desactivar IPv6 |  | http://ubuntuforums.org/showthread.php?t=87798, tambien hay que quitarlo del nucleo |
| Init en paralelo |  | Cambiar en /etc/init.d la linea "startup $i start" por "startup $i start &", aunque con tan pocos servicios y con dash quizas no haga falta o no funcione |
| Eliminar xfs en Etch | Hecho | dpkg-reconfigure -phigh xserver-xorg, usa /etc/X11/xorg.conf en lugar de /etc/X11/XF86cfg-4 |
| Poner barra de scroll en xterm |  | http://web.mit.edu/answers/xwindows/xwindows_scrollbar.html pero falla :-( |
| Usar ntpdate en lugar de ntp |  |  |
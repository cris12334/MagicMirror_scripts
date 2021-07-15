Download and install the latest Node.js version:

<div id="urvanov-syntax-highlighter-60f05db387067758977799" class="urvanov-syntax-highlighter-syntax crayon-theme-sublime-text urvanov-syntax-highlighter-font-sourcecodepro urvanov-syntax-highlighter-os-pc print-yes notranslate" data-settings=" minimize scroll-mouseover" style="margin-top: 12px; margin-bottom: 12px; margin-left: 12px; font-size: 15px !important; line-height: 25px !important; height: auto;">
		
	curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -



# SmartMirror_scripts
SmartMirror Scripts de instalación y configuración

Estos scripts se pueden utilizar para automatizar la instalación de actualizaciones de liberación. 

## raspberry.sh  es el script de instalación, actualizado desde el paquete central
 Ejecutar el script de instalación.

<div id="urvanov-syntax-highlighter-60f05db387067758977799" class="urvanov-syntax-highlighter-syntax crayon-theme-sublime-text urvanov-syntax-highlighter-font-sourcecodepro urvanov-syntax-highlighter-os-pc print-yes notranslate" data-settings=" minimize scroll-mouseover" style="margin-top: 12px; margin-bottom: 12px; margin-left: 12px; font-size: 15px !important; line-height: 25px !important; height: auto;">
		
	bash -c  "$(curl -sL https://raw.githubusercontent.com/cris12334/MagicMirror_scripts/master/raspberry.sh)"



There is a log file, magicmirror / install.log, created so that we can diagnose any problem
    
## upgrade-script.sh hará el git pull y npm install, y refrescar npm setup Para cualquier módulo que pueda necesitarlo.
Debe manejar todo el trabajo ...
y te da una prueba de prueba de todo eso ...

solo aplicando cambios si los solicitas

darle una oportunidad
Esto funciona también en Mac.
 
 <div id="urvanov-syntax-highlighter-60f05db387067758977799" class="urvanov-syntax-highlighter-syntax crayon-theme-sublime-text urvanov-syntax-highlighter-font-sourcecodepro urvanov-syntax-highlighter-os-pc print-yes notranslate" data-settings=" minimize scroll-mouseover" style="margin-top: 12px; margin-bottom: 12px; margin-left: 12px; font-size: 15px !important; line-height: 25px !important; height: auto;">
		
	bash -c  "$(curl -sL https://raw.githubusercontent.com/cris12334/MagicMirror_scripts/master/upgrade-script.sh)"



 

No se hacen cambios en el repositorio local o en la copia de trabajo.

Si quieres aplicar realmente los cambios.

  
   <div id="urvanov-syntax-highlighter-60f05db387067758977799" class="urvanov-syntax-highlighter-syntax crayon-theme-sublime-text urvanov-syntax-highlighter-font-sourcecodepro urvanov-syntax-highlighter-os-pc print-yes notranslate" data-settings=" minimize scroll-mouseover" style="margin-top: 12px; margin-bottom: 12px; margin-left: 12px; font-size: 15px !important; line-height: 25px !important; height: auto;">
		
	bash -c  "$(curl -sL https://raw.githubusercontent.com/cris12334/MagicMirror_scripts/master/upgrade-script.sh)" apply




Hay un archivo de registro (actualización.log) en la carpeta MagicMirror / installers ...
## La instalación tiene dos secciones de soporte adicional

### Apague el protector de pantalla y configure PM2 a AUTOSTART MM en la bota.
También he proporcionado aquellos por separado, en caso de que necesites ejecutar uno por separado, o cambié de opinión después de instalar

screensaveroff.sh



   <div id="urvanov-syntax-highlighter-60f05db387067758977799" class="urvanov-syntax-highlighter-syntax crayon-theme-sublime-text urvanov-syntax-highlighter-font-sourcecodepro urvanov-syntax-highlighter-os-pc print-yes notranslate" data-settings=" minimize scroll-mouseover" style="margin-top: 12px; margin-bottom: 12px; margin-left: 12px; font-size: 15px !important; line-height: 25px !important; height: auto;">
		
	bash -c "$(curl -sL https://raw.githubusercontent.com/cris12334/MagicMirror_scripts/master/screensaveroff.sh)"
    
    

Clasificación de FIXUP 2. SÍ
        


        
   <div id="urvanov-syntax-highlighter-60f05db387067758977799" class="urvanov-syntax-highlighter-syntax crayon-theme-sublime-text urvanov-syntax-highlighter-font-sourcecodepro urvanov-syntax-highlighter-os-pc print-yes notranslate" data-settings=" minimize scroll-mouseover" style="margin-top: 12px; margin-bottom: 12px; margin-left: 12px; font-size: 15px !important; line-height: 25px !important; height: auto;">
		
	bash -c "$(curl -sL https://raw.githubusercontent.com/cris12334/MagicMirror_scripts/master/fixuppm2.sh)"

# 15. Forense de navegadores

## 1. Fundamentos de un navegador web moderno
+ Protocolo HTTP
+ Historial
+ Cookies
+ Cachés del navegador
+ Ads & Adblockers
+ Contraseñas guardadas
+ Bookmarks
+ Descargas
+ Complementos / Plugins / Extensiones
+ Certificados digitales
+ Modo privado (y sus limitaciones, ver Forense de memoria RAM)
+ Modo depuración
+ Navegadores portables

## 2. Determinar navegadores usados
+ Prefetch
+ UserAssist
+ Buscar fechas en las localizaciones básicas de los navegadores

## 3. Navegador Chrome
+ Localización de ficheros:
  + Windows 7/8: %root%/Users/%userprofile%/AppData/Local/Google/Chrome/User Data/Default/
  + Linux: /home/%userprofile%/.config/google-chrome/Default/Application Cache/
  + Mac OSX: /Users/%userprofile%/Caches/Google/Chrome/Default/

http://jon.glass/blog/parses-chrome-stuff-with-python/

## 4. Navegador Firefox
+ Localización de ficheros:
  + Windows 7/8: %root%/Users/%userprofile%/AppData/Local/Mozilla/Firefox/ Profiles/
  + Linux: /home/%userprofile%/.mozilla/firefox/$PROFILE.default/
  + Mac OS X: /Users/%userprofile%/Library/Caches/Firefox/Profiles/ $PROFILE.default//
+ Uso de SQLite para guardar información

http://www.acquireforensics.com/services/tech/mozilla-firefox.html
http://www.dataforensics.org/mozilla-firefox-forensics/
https://www.foxtonforensics.com/browser-history-examiner/firefox-data

## 5. Navegador Internet Explorer
+ Localización de ficheros: 
  + IE (prior to version 10)
    + Windows XP: %root%/Documents and Settings/%userprofile%/Local Settings /Temporary Internet Files/Content.IE5
    + Windows Vista/7: %root%/Users/%userprofile%/AppData/Local/Microsoft/Windows /Temporary Internet Files/Content.IE5
  + Internet Explorer 10
    + IE 10: %root%/Users/%userprofile%/AppData/Local/Microsoft/Windows /History
+ Claves del registro de interés
+ Zonas de seguridad

## 6. Navegador Internet Edge
+ Localización de ficheros: 
  + BD: \Users\user_name\AppData\Local\Packages\Microsoft.MicrosoftEdge_xxxxx\AC\MicrosoftEdge\User\Default\DataStore\Data\nouser1\xxxxx\DBStore\spartan.edb
  + Caché: \Users\user_name\AppData\Local\Packages\Microsoft.MicrosoftEdge_xxxx\AC\#!001\MicrosoftEdge\Cache\
  + Historial: \Users\user_name\AppData\Local\Microsoft\Windows\WebCache\WebCacheV01.dat 
  + Descargas: BD ESE WebCacheV01.dat, en la tabla "iedownload"
+ Bases de datos ESE

https://www.linkedin.com/pulse/windows-10-microsoft-edge-browser-forensics-brent-muir/
https://bsmuir.kinja.com/windows-10-microsoft-edge-browser-forensics-1733533818
http://www.dataforensics.org/microsoft-edge-browser-forensics/

## 7. Navegador Safari
+ Localización de ficheros: 
  + Mac OSX: /Users/$USERNAME/Library/Safari/*
  + Windows 7/8: %root%/Users/%userprofile%/AppData/Roaming/Apple Computer/Safari/
       
## 8. Otros navegadores
+ Opera
+ Midori
+ Chromium
 
## Libros

## Formación

## Herramientas
+ BrowsingHistoryView - Extrae el historial : https://www.nirsoft.net/utils/browsing_history_view.html
+ MyLastSearch - Obtiene las búsquedas realizadas con los navegadores : https://www.nirsoft.net/utils/my_last_search.html
+ Browser History Viewer - Otra herramienta para revisar el historial: https://www.foxtonforensics.com/browser-history-viewer/
+ Pasco - Herramienta para el análisis de Internet Explorer : https://www.mcafee.com/hk/downloads/free-tools/pasco.aspx
+ Hindsight - Análisis de artefactos de Chrome/Chromium: https://github.com/obsidianforensics/hindsight
+ FoxAnalysis - Análisis de artegactos en Firefox : https://haxf4rall.com/2017/09/04/foxanalysis-firefox-internet-history-analysis-tool/
+ SQLiteBrowser - Herramienta para parsear BD SQLite : http://sqlitebrowser.org/ 
+ libesedb - Librería para gestionar BD ESE en Linux : https://github.com/libyal/libesedb/wiki/Building
+ ESEDatabaseView - Visor de BD ESE : https://www.nirsoft.net/utils/ese_database_view.html

## Ejercicios

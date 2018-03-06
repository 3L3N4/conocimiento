# 15. Forense de navegadores

## 1. Fundamentos de un navegador web moderno
+ Protocolo HTTP
+ Historial
+ Cookies
+ Cachés del navegador
+ Modo depuración
+ Descargas
+ Complementos / Plugins / Extensiones
+ Certificados digitales
+ Modo privado

## 2. Determinar navegadores usados
+ Prefetch
+ UserAssist
+ Buscar fechas en las localizaciones básicas de los navegadores

## 3. Navegador Chrome
+ Google Chrome
        Windows 7/8: %root%/Users/%userprofile%/AppData/Local/Google/Chrome/User Data/Default/Cache
        Linux: /home/%userprofile%/.config/google-chrome/Default/Application Cache/Cache/
        Mac OSX: /Users/%userprofile%/Caches/Google/Chrome/Default/Cache/
        
## 4. Navegador Firefox
+ Mozilla Firefox
        Windows 7/8: %root%/Users/%userprofile%/AppData/Local/Mozilla/Firefox/ Profiles/*.default/Cache
        Linux: /home/%userprofile%/.mozilla/firefox/$PROFILE.default/Cache
        Mac OS X: /Users/%userprofile%/Library/Caches/Firefox/Profiles/ $PROFILE.default/Cache/
+ Uso de SQLite para guardar información

## 5. Navegador Internet Explorer
+ IE (prior to version 10)
        Windows XP: %root%/Documents and Settings/%userprofile%/Local Settings /Temporary Internet Files/Content.IE5
        Windows Vista/7: %root%/Users/%userprofile%/AppData/Local/Microsoft/Windows /Temporary Internet Files/Content.IE5
+ Internet Explorer 10
        IE 10: %root%/Users/%userprofile%/AppData/Local/Microsoft/Windows /History
        
## 6. Navegador Safari
+ Safari
        Mac OSX: /Users/$USERNAME/Library/Safari/*
        Windows 7/8: %root%/Users/%userprofile%/AppData/Roaming/Apple Computer/Safari/
       
## 6. Otros navegadores
+ Opera
+ Midori
 

## Libros

## Formación

## Herramientas
+ BrowsingHistoryView - Extrae el historial :https://www.nirsoft.net/utils/browsing_history_view.html
+ MyLastSearch - Obtiene las búsquedas realizadas con los navegadores : https://www.nirsoft.net/utils/my_last_search.html
+ Pasco - Herramienta para el análisis de Internet Explorer : https://www.mcafee.com/hk/downloads/free-tools/pasco.aspx
## Ejercicios

# 11. Forense de memoria RAM

## 1. Fundamentos de arquitectura de computadores y SO
+ Fundamentos de arquitectura de computadores
+ Tipos de memoria: RAM, crash dumps, paginación, hibernación

## 2. Adquisición de memoria en Windows

## 3. Artefactos en la memoria (Windows)

## 4. Adquisición de memoria en Linux

## 5.  Artefactos en la memoria (Linux)

## 6. Adquisición de memoria en Mac

## 7. Artefactos en la memoria (Mac)

## 8. Adquisición de memoria en terminales móviles

## 9. Análisis de crash dumps
+ Uso de Windbg: https://msdn.microsoft.com/en-us/library/windows/desktop/ee416349(v=vs.85).aspx

## Libros / Recursos
+ "The art of memory forensics", Michal Hale, Andrew Case - Ed. Wiley
+ Windows Internals Book, Chapter 5: Memory Management - Ed. Microsoft Press

## Formación

## Herramientas
+ Volatility - Junto con Rekall, la herramienta de referencia de análisis de memoria: http://www.volatilityfoundation.org/
+ Rekall - Junto con Volatility, la herramienta de referencia de análisis de memoria: http://www.rekall-forensic.com/
+ Winpmem - Volcado de memoria en Windows: https://github.com/google/rekall/releases/tag/v1.5.1
+ DumpIt - Herramienta rápida y sencilla para el volcado de memoria en Windows : https://blog.comae.io/your-favorite-memory-toolkit-is-back-f97072d33d5c
+ Belkasoft Live RAM Capturer - Otra tool para volcar memoria de Windows : https://belkasoft.com/ram-capturer
+ FTK Imager Lite - Otra tool para volcar memoria de Windows (y hacer algo de triage de paso): https://accessdata.com/product-download 
+ LiME - Volcado de memoria en Linux & Android : https://github.com/504ensicsLabs/LiME 
+ osxPmem - Volcado de memoria en OSX : https://github.com/google/rekall/releases/tag/v1.5.1
+ VolUtility - Interface gráfico de Volatility : https://github.com/kevthehermit/VolUtility
+ Mandiant Redline - Herramienta de captura de RAM y datos de triage: https://www.fireeye.com/services/freeware/redline.html
+ Windows Debugger -  utilidad de Microsoft para el análisis de dumps de sistema : https://www.petri.com/crash-dump-analysis-how-to-install-the-windows-debugger

## Ejercicios
+ Repo con toneladas de ejercicios y retos forenses de memoria: https://github.com/volatilityfoundation/volatility/wiki/Memory-Samples
+ GrrCON 2015 memory forensics challenge: http://www.ghettoforensics.com/2016/05/grrcon-2015-memory-forensics-grabbing.html / https://volatility-labs.blogspot.com.es/2012/10/solving-grrcon-network-forensics.html
+ GrrCON 2015 memory forensics challenge: https://techanarchy.net/2016/10/solving-grrcon-2016-dfir-challenge/

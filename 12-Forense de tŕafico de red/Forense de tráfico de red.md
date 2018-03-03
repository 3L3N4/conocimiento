# 12. Forense de tráfico de red

## 1. Fundamentos de redes
Objetivo: Conocer los fundamentos básicos de redes de informáticas y de telecomunicaciones
* Tipos de redes (LAN, WLAN, WAN)
* Dispositivos para crear redes (switches, routers, puntos de acceso, hubs)
* Pila de protocolo TCP/IP completa
* Elementos básicos de una red (puestos de trabajo, servidores, electrónica de red, proxy)
 
## 2. Fundamentos de protocolos de aplicación
Objetivo: Conocer los protocolos de nivel de aplicación más empleados
* HTTP
* SMTP
* DNS
* HTTPS

## 3. Fundamentos de captura: Definición, Acceso, Almacenamiento, Gestión
Objetivo:
Dificultades a la hora de capturar el tráfico

## 4. Mecanismos de captura de tráfico (hardware, software)
Objetivo:

## 5. Análisis de paquetes
Objetivo:

## 6. Análisis de flujos
Objetivo:
NetFlow

## 7. Análisis de protocolos de nivel de aplicación
Objetivo:

## 8. Análisis estadístico
Objetivo:

## 9. Análisis de dispositivos de red (router, switches, puntos de acceso)
Objetivo:

## 10. Análisis de logs de proxy
Objetivo:

## 11. Análisis de logs de servidores de correo
Objetivo:

## 12. Análisis de logs de servidores de DNS
Objetivo:

## 13. Análisis de logs remotos (syslog)
Objetivo:

## 14. Canales encubiertos de comunicación 
Objetivo: Conocer qué mecanismos pueden ser usados para exfiltrar información de forma encubierta, así como las técnicas para su detección. 
* HTTP
* HTTPS
* DNS
* SMTP
* ICMP

## Libros: 
+ "Network Forensics Tracking Hackers Through Cyberspace" - Sherri Davidoff/Jonathan Ham, Ed Prentice Hall
+ "The Practice of Network Security Monitoring" - Richard Bejtlich, Ed. No Starch Press

## Distros: 
+ Security Onion -  Distro basada en Ubuntu orientada a la detección de intrusos y monitorización de red: https://securityonion.net/
+ SELKS - Distro basada en Debian orientada a la detección de intrusos: https://www.stamus-networks.com/open-source

## Herramientas
+ tcpdump - Herramienta de línea de comandos de Linux para la captura de tráfico: https://www.tcpdump.org/tcpdump_man.html
+ Wireshark - La herramienta gráfica más usada para el análisis de paquetes de red: https://www.wireshark.org/
+ tshark - Herramienta de Wireshark en línea de comandos para el análisis de tráfico, con las mismas capacidades pero scriptable: https://www.wireshark.org/docs/wsug_html_chunked/AppToolstshark.html
+ dumpcaps - Herramienta de Wireshark para la captura de tráfico: https://www.wireshark.org/docs/man-pages/dumpcap.html
+ trimpcap - Script para recortar las sesiones de una captura de tráfico para reducir el tamaño que ocupan:  https://www.netresec.com/?page=TrimPCAP
+ Xplico - Ideal para reconstruir páginas web de una captura de red :https://www.xplico.org/
+ NetworkMiner - Captura tráfico y también lo reconstruye :http://www.netresec.com/?page=NetworkMiner
+ Paessler PRTG - Herramienta de gestión de red que trabaja con NetFlow https://www.paessler.com/prtg
+ p0f - Ideal para identificar equipos y flujos de comunicaciones :http://lcamtuf.coredump.cx/p0f3/#
+ ntop-ng
+ passiveDNS
+ packetbeat
+ Bro
+ Snort
+ Suricata 


## Formación
+ ENISA Network Forensics Training
https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/network-forensics-handbook/view

## Ejercicios
+ Malware-Traffic-Analysis (malware con .pcaps)
https://www.malware-traffic-analysis.net/training-exercises.html
+ Network Forensic CTF - TufMups Undercover Operation 
https://betweentwodfirns.blogspot.com.es/2017/12/network-forensic-ctf-tufmups-undercover.html
+ Sharif University CTF 2016 : Network Forensics
https://github.com/ctfs/write-ups-2016/tree/master/su-ctf-2016/forensics/network-forensics-200
+ LMG Network Forensics Puzzle Contest
http://forensicscontest.com/puzzles
+ Network Forensics Workshop Deux: Long Live Packet Pillaging
https://github.com/BechtelCIRT/NFWorkshop16
+ DFRWS Forensic Challenge IoT Forensic Challenge (2017 - 2018)
http://www.dfrws.org/dfrws-forensic-challenge
+ Colección de dumps altamente recomendables de NETRESEC
http://www.netresec.com/?page=PcapFiles

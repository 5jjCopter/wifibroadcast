# Mavproxy y video fpv en 1080
1. Descargar imagen iso mavproxy que esta en este mismo directorio:https://github.com/5jjCopter/wifibroadcast-mavproxy/blob/master/imagen%20iso%20mavproxy y instalar en targeta sd.
la imagen contiene mavproxy y gstremer

2. De aqui:https://github.com/5jjCopter/instalar/blob/master/instalar-solo-video  ... instala solo-video que contiene video por gstremer y interfaces para poner wlan0 con ip fija.(Copiar contenio y pegar en consola de raspi)


3. Ejecuta en consola el scripts de este mismo directorio: https://github.com/5jjCopter/wifibroadcast-mavproxy/blob/master/arranque-mavproxy-inicio   ...llamado (arranque-mavproxy-inicio) para que mavproxy se ejecute al iniciar raspberry.

Con esto ya se ejecutara video y mavproxy en el arranque.
Podra conectar al misionPlaner o tower por wifi para ver telemetria y video a traves de raspberry pi.
La ip de raspberry por wifi es fija 192.168.1.122.

La raspberry conectara automaticamente a un punto de acceso o ruter con SSID:ruter y con comtraseña:2004123413252
Para que conecte a mision planner con windows el pc tiene que conectar al punto de aceso o ruter y hay que asignar manualmente la ip fija 192.168.1.150.

Para que conecte a tower con android  tiene que conectar al punto de aceso o ruter y hay que asignar manualmente la ip fija 192.168.1.80.

Conectara al mision planer o tower por udp en  puerto 14500 y  baudios 57600

Para ver video en pc teneis que tener instalado gstremer y descargaros el scripts video.bat y ejecutarlo en el pc.
Para ver video en mobil android con tower solo teneis que conectar por udp y poner en el plugin de video el puerto 9000.
Teneis aqui:http://ardupilot.org/dev/docs/raspberry-pi-via-mavlink.html   ... mas imformacion sobre Mavproxy y sud usos.
Espero que lo disfruteis.
Saludos de 5jjCopter.

 


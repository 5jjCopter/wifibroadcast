# wifibroadcast
1. Descargar imagen iso mavproxy que esta en este mismo directorio y instalar en targeta sd.
la imagen contiene mavproxy y gstremer

2. De aqui instala solo-video que contiene video por gstremer y interfaces para poner wlan0 con ip fija.
https://github.com/5jjCopter/instalar/blob/master/instalar-solo-video.
Para que video se ejecute en el arramque escriba en consola lo siguiente.
sudo systemctl daemon-reload
sudo systemctl enable video
sudo reboot


3. Ejecuta en consola el scripts de este mismo directorio llamado (arranque-mavproxy-inicio) para que mavproxy se ejecute al iniciar raspberry.

Con esto ya se ejecutara video y mavproxy en el arranque.
Podra conectar al misionPlaner o tower por wifi para ver telemetria y video a traves de raspberry pi.
 


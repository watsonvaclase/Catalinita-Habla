# Catalinita te ayuda a probar la capacidad de hablar de tu TJBot

![Catalinita](https://github.com/watsonvaclase/Propuestas/blob/master/Catalinita/Catalinita.png)
<br>

Si dudas de la capacidad de hablar de tu TJBot, Catalinita te saca de dudas. Ella verbalizará el texto que tú quieras.

Para poner en marcha el programa _Catalinita\_hablame.js_ sólo tienes que hacer cinco cosas:
1) Descargar el audio ![Noise.wav](https://github.com/watsonvaclase/Propuestas/blob/master/Catalinita/Noise.wav) y el programa ![Catalinita_hablame.js](https://github.com/watsonvaclase/Propuestas/blob/master/Catalinita/Catalinita_hablame.js) a la raspberrypi.
2) Ubicar los dos ficheros descargados (_Noise.wav_ y _Catalinita\_hablame.js_) en el directorio donde esté el programa _conversation.js_ del TJBot.
3) Asegurar que en ese directorio haya un subdirectorio llamado _node\_modules_. En caso negativo, ejecutar: <br>
_npm install_
4) Asegurar que en el mismo directorio exista y esté bien completado el fichero de credenciales _config.js_ 
5) Ejecutar: <br>
_sudo node Catalinita\_hablame.js "xxx"_ <br>
siendo _xxx_ el texto que quieras que Catalinita verbalice. <br>

(Si no oyes nada, pero no te sale ningún error por pantalla, prueba a conectar un altavoz con mini-jack usando un adaptador para el puerto usb. <br>
Si el altavoz distorsiona, prueba la misma solución.)<br>


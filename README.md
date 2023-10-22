# Proceso de subir firmware al Smart Sprinkler

## Smart Sprinkler - Full Pack
### Paso 1:
Descargar la herramienta Flash Download Tools.

https://www.espressif.com/en/support/download/other-tools

![](img/img_1.jpg)

### Paso 2:
Descomprimir y ejecutar como administrador la aplicación.

![](img/img_2.jpg)

Nota: Lo más probable es que salga un mensaje de seguridad de Windows, darle clic en mas información y luego ejecutar de todas formas.

### Paso 3:
Seleccionar el microcontrolador, en nuestro caso, buscar ESP32 y luego OK. Después debería abrirse una nueva ventana.

![](img/img_3.jpg)

![](/img/img_4.jpg)

### Paso 4:
Luego debemos colocar los siguientes parámetros en la herramienta y buscar el archivo firmware.bin, que es el firmware que vamos a subir al dispositivo.

![](img/img_5.jpg)

### Paso 5:
Conectamos el dispositivo a uno de los puertos USB de la computadora, después de unos segundos deberíamos buscar el puerto COM asignado. También debemos asegurarnos de que la velocidad de BAUD sea 921600.

![](img/img_6.jpg)

### Paso 6:
Finalmente, le damos START para iniciar la grabación del firmware al dispositivo.

![](img/img_7.jpg)

### Paso 7:
Si todo salió correctamente, deberías ver algo similar.

![](img/img_8.jpg)
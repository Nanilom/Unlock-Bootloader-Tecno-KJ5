# Unlock-Bootloader-Tecno-KJ5
Comandos para desbloquear bootloader Tecno spark 20 kj5


Habilite las herramientas del desarrollador y desbloquee el cargador
de arranque
1. Toque el menú "Configuración", luego debe tocar "Tecno Spark 20" junto a "Mi teléfono"

2. A continuación, desliza el dedo hacia abajo para encontrar "Número de compilación"

3. Toca la opción "Número de compilación" varias veces hasta que veas "Ahora eres desarrollador" en Tecno Spark 20.

4. Toque el menú "Configuración" nuevamente.

5. Toque "Opciones de desarrollador", luego active la opción "Depuración USB" y "Desbloqueo OEM".
Debido a algunas restricciones de Tecno, debe crear un "Tecno ID" y esperar 2 semanas antes de poder habilitar la opción
de "Desbloqueo OEM". Descargue el controlador USB e instálelo en la PC.

6. Conecte Tecno Spark 20 con la PC mediante un cable USB. Toque la opción "PERMITIR" en su teléfono para permitir la depuración USB.

7. Descargue el archivo Zip de las herramientas de la plataforma SDK.

8. Abra la carpeta platform-tools dentro de la carpeta SDK de Android en su PC después de extraer el archivo ZIP.

9. Dentro de la carpeta platform-tools, debe escribir "cmd" en la barra de direcciones y presionar el botón "enter" para abrir la ventana de comandos.

10. Ingrese el siguiente comando para verificar el dispositivo conectado:

adb reboot bootloader

fastboot flashing unlock

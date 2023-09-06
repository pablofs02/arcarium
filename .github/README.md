# Pasos a seguir
Por defecto está el teclado estadounidense. Cámbialo al español para que sea más fácil meter los comandos.

`loadkeys es`

Si quiere una letra más grande, use el siguiente comando.

`setfont /usr/share/kbd/consolefonts/latarcyrheb-sun32`

Si no tiene conexión cableada, conéctese a una red wifi.

`iwctl --passphrase [contraseña] station wlan0 connect [wifi]`

Bájese el archivo de instalación en la máquina local.

`curl https://raw.githubusercontent.com/pablofs02/arcus/Principal/arcus > arcus`

Dele permisos de ejecución.

`chmod +x arcus`

Y ejecute el instalador.

`./arcus`

# Información sobre instalador
Usar un sistema EFI de 128/256/512M y otro con todo el espacio libre disponible.

Use Type y seleccione "EFI System".

Use "Write" y escriba 'yes' y salga con 'Quit'.

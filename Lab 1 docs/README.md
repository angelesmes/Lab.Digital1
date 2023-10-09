# Instructivo de Instalación Linux para el Laboratorio de Electrónica Digital 1

- **Objetivo:** Este instructivo te guiará a través del proceso de instalación de Linux en Windows por Dual Boot.

- **Requisitos Previos:**
   - Tener un computador
   - Escoger si vas a utilizarlo en la máquina virtual o si se instalará en el disco duro del computador.

En este instructivo se hará la instalación en el disco duro del computador.

- **Instalación:**

Para instalar Linux en el PC, lo primero que debemos hacer es tener instalado tanto el ISO de Linux (puede ser cualquier versión) como el arrancador del sistema operativo por medio de USB (Rufus).

Ambos programas pueden ser descargados fácilmente desde el buscador web.

![image](https://github.com/angelesmes/Lab.Digital1/assets/143465169/7b72a1d1-b004-496f-aa2f-66438859c724)

![image](https://github.com/angelesmes/Lab.Digital1/assets/143465169/5c2f8a6a-9ce2-4131-abb5-e58b0021cea3)

Una vez descargados el ISO y el programa Rufus, es importante elaborar una partición en la memoria para poder contar con espacio suficiente para el nuevo sistema operativo.

![image](https://github.com/angelesmes/Lab.Digital1/assets/143465169/a29cac5d-8e05-4e56-98c2-ce3652273cb7)

Ya teniendo espacio para el sistema operativo, procedemos a arrancar el sistema operativo Linux desde la Bios del PC. Para llegar a la Bios se debe apagar el equipo y en la mayoría de casos presionar la tecla F2. Además debemos buscar el modo de arranque mediante la memoria USB flasheada con Rufus anteriormente.

![image](https://github.com/angelesmes/Lab.Digital1/assets/143465169/3acc68f8-bb9f-4c32-b61c-5e93dfc3198f)

Debemos instalar al Grub (programa utilizado para tener la posibilidad de escoger entre uno de los dos sistemas operativos) y también instalar Linux de forma directa. 

![image](https://github.com/angelesmes/Lab.Digital1/assets/143465169/4773cbef-ecd0-4b86-a2da-89eb75765788)

Ya teniendo el sistema operativo Linux, debemos configurarlo y realizar una repartición de memoria para almacenamiento, sistema operativo y RAM.

![image](https://github.com/angelesmes/Lab.Digital1/assets/143465169/4bf6674c-7e6b-431a-808a-4b987a66e314)

![image](https://github.com/angelesmes/Lab.Digital1/assets/143465169/e0e6f060-f5d9-4533-bf0d-3dfd46e9dd34)

La instalación puede terminar de forma satisfactoria, como lo podemos observar, sin embargo, pueden ocurrir algunos errores que se pueden presentar debido a conflictos de memoria entre particiones y seguridad en el arranque y son los siguientes:

El Grub no aparece para iniciar sesión en alguno de los dispositivos.

![image](https://github.com/angelesmes/Lab.Digital1/assets/143465169/f858fdd3-3208-463a-9a30-dcc257c140dd)

Para solucionar este error, debemos realizar un boot repair desde la consola de LInux con los siguientes códigos:

![image](https://github.com/angelesmes/Lab.Digital1/assets/143465169/37bf1cb4-8e2c-4b32-bf37-fbda74763fe5)

Una vez reparado el arranque, debería aparecer el Grub de forma satisfactoria para poder elegir entre iniciar sesión en Windows o en Linux. 

![image](https://github.com/angelesmes/Lab.Digital1/assets/143465169/d4c8dbce-2d94-4005-9494-9ab16e4ca3f4)

Otro error común que aparece al instalar Linu es el de arranque de seguridad, y sucede debido a que hay conflictos entre los arranques de los sistemas operativos, por este motivo solo uno de los dos Si puede funcionar. 

![image](https://github.com/angelesmes/Lab.Digital1/assets/143465169/9744e917-75a8-457c-bfc1-657df9b42782)

Esto es lo que aparece al intentar arrancar Linux con conflictos de arranque. 

Para solucionar este error, debemos ir al Bios del PC y presionar contol+s para activar el modo sata, de esta manera encontrar y elegir entre el arranque ACH, optane con raid o sin raid. Al cambiar el modo de arranque también podemos cambiar de sistema operativo de manera exitosa.

![image](https://github.com/angelesmes/Lab.Digital1/assets/143465169/756d0344-136f-4969-8cd6-6dc265b004f0)

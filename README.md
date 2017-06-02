# mo-heat-templates-bbb
![Ubuntu](https://img.shields.io/badge/Ubuntu-16.04-blue.svg?colorB=f98012)
![OpenStack](https://img.shields.io/badge/OpenStack-Kilo-blue.svg?colorB=557697)
![BigBlueButton](https://img.shields.io/badge/BBB-1.1-blue.svg?colorB=8892BF)
[![Software License](https://img.shields.io/badge/License-APACHE-black.svg?style=flat-square&colorB=585ac2)](LICENSE)

Plantilla de orquestación Heat para iniciar BigBlueButton y obtener su url y llave secreta. Para la configuración se utiliza parte del código de bbb-conf.
## Requerimientos
* Se debe utilizar una imagen de disco personalizada con BBB previamente instalado:
    * BBB 1.1
    * Ubuntu 16.04

## Parametros
* **key_name:** Nombre de llave de acceso
* **flavor:** Sabor de la máquina virtual
* **image:** Imagen de disco personalizada con BBB previamente instalado
* **public_net:** Red pública
* **private_net:** Red privada

## Salida
* La plantilla devuelve:
  * La url de BBB
  * La llave compartida de BBB.

# mo-heat-templates-bbb
Plantilla de orquestación Heat para iniciar BigBlueButton y obtener su url y llave secreta. Para la configuración se utiliza parte del código de bbb-conf.
## Requerimientos
* Se debe utilizar una imagen de disco personalizada con BBB previamente instalado.

## Parametros
* **key_name:** Nombre de llave de acceso
* **flavor:** Sabor de la máquina virtual
* **image:** Imagen de disco personalizada con BBB previamente instalado
* **private_net:** Red privada

## Salida
* La plantilla devuelve:
  * La url de BBB
  * La llave compartida de BBB.

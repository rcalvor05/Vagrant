# VAGRANT

## ¿Qué es Vagrant?

#### Vagrant es una herramienta creada para la construcción de desarrolo completos. Es facil de usar y su principal enfoque es la automatización, vagrant reduce tiempo al desarrollador ya que no tiene que configurar el entorno.

### ¿Qué resulve Vagrant?

Resuelve errores como que en una **maquina funciona y en otra no**, gracias a Vagrant puedes *usar* exactamente **el mismo entorno**, mismo sistema operativo, mismos paquetes, misma configuración. Todo esto se hace gracias al `Vagrantfile`

- **Anfitrion:**  Se trata de tu maquina física, el que ejecuta todo el software de virtualización.

- **Proveedor de virtualización:**  Se trata del programa que de verdad crea y ejecuta la maquina virtual, **Vagrant no virtualiza** nada por sí mismo, el automatiza la virtualización, es decir le da ordenes al proveedor de virtualización, por ejemplo `virtualbox` sería un **proveedor de virtualización**

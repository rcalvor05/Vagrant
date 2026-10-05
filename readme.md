# VAGRANT

## ¿Qué es Vagrant?

#### Vagrant es una herramienta creada para la construcción de entornos de desarrollo completos. Es fácil de usar y su principal enfoque es la automatización, Vagrant reduce tiempo al desarrollador ya que no tiene que configurar el entorno.

### ¿Qué resulve Vagrant?

Resuelve errores como que en una **maquina funciona y en otra no**, gracias a Vagrant puedes *usar* exactamente **el mismo entorno**, mismo sistema operativo, mismos paquetes, misma configuración. Todo esto se hace gracias al `Vagrantfile`

- **Anfitrión:**  Se trata de tu maquina física, el que ejecuta todo el software de virtualización.

- **Proveedor de virtualización:**  Se trata del programa que de verdad crea y ejecuta la maquina virtual, **Vagrant no virtualiza** nada por sí mismo, el automatiza la virtualización, es decir le da órdenes al proveedor de virtualización, por ejemplo `virtualbox` sería un **proveedor de virtualización**

- **Box:**  Imagen base empaquetada a partir de la cual se crea la máquina virtual, contiene un **sistema opeartivo** ya instalado y preparado para Vagrant. se descarga de un repositorio público `Vagrant Cloud/HashiCorp) con nombres como `ubuntu/jammy64`. **Se guarda en local**

- **Máquina virtual: ** Es lo que el proveedor crea a partir de la box, aplicando lo que indica el Vagrantfile (red,memoria,carpetas compartidas, etc). Se gestiona con `vagrant up`,`vagrant ssh`,`vagrant halt` y `vagrant destroy`

## Lenguaje del Vagrantfile
El Vagrantfile está escrito en **Ruby**. Usa un DSL ( lenguaje específico de dominio) basado en Ruby. No es necesario saber Ruby para usarlo, aunque se pueden emplear condiciones de Ruby si se necesita
  

# 2.Aprovionamiento
## ¿Qué es?
Es el mecanismo de **Vagrant** para configurar automáticamente la máquina después de crearla: instalar paquetes copiar archivos, arrancar servicios, el más básico es `shell`,que ejecuta un script


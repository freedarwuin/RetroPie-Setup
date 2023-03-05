Configuración de RetroPie
==============

Uso general
-------------

Shell script para configurar Raspberry Pi, Vero4K, ODroid-C1 o una PC con Ubuntu con muchos emuladores y juegos, utilizando EmulationStation como interfaz gráfica. Las imágenes prefabricadas de arranque para Raspberry Pi están disponibles para aquellos que desean un sistema listo para usar, que se pueden descargar desde la sección de lanzamientos de GitHub o a través de nuestro sitio web en https://retropie.org.uk.

Este script está diseñado para usarse en Raspberry Pi OS (anteriormente llamado Raspbian) en Raspberry Pi, OSMC en Vero4K o Ubuntu en ODroid-C1 o una PC.

Para ejecutar el script de configuración de RetroPie, asegúrese de que sus repositorios APT estén actualizados y que Git esté instalado:

```shell
sudo apt-get update
sudo apt-get dist-upgrade
sudo apt-get install git
```

Luego puede descargar el último script de configuración de RetroPie con:

```shell
cd
git clone --depth=1 https://github.com/RetroPie/RetroPie-Setup.git
```

El script se ejecuta con:

```shell
cd RetroPie-Setup
sudo ./retropie_setup.sh
```

Cuando ejecuta el script por primera vez, es posible que instale algunos paquetes adicionales necesarios.

Binarios y fuentes
--------------------

En Raspberry Pi, RetroPie Setup ofrece la posibilidad de instalar desde binarios o fuentes. Para otras plataformas compatibles, solo está disponible una instalación de origen. Se recomienda instalar desde binario en una Raspberry Pi, ya que construir todo desde la fuente puede llevar mucho tiempo.

Para obtener más información, visite el sitio en https://retropie.org.uk o el repositorio en https://github.com/RetroPie/RetroPie-Setup.

Documentos
----

Puede encontrar información útil sobre varios componentes y respuestas a preguntas frecuentes en [RetroPie Docs] (https://retropie.org.uk/docs/). Si cree que falta algo, lo invitamos a enviar una solicitud de extracción al [repositorio RetroPie-Docs] (https://github.com/RetroPie/RetroPie-Docs).


Gracias
------

Este script simplemente simplifica el uso de las grandes obras de muchas otras personas que disfrutan del espíritu del retrogaming. ¡Muchas gracias a ellos!

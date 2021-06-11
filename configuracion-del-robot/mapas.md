# Mapas

El mapa es visible en la interfaz del robot y es la base de la capacidad del robot de navegar por sus alrededores de forma segura y eficiente. El mapa ilustra el área física en la que opera el robot.

{% hint style="warning" %}
El robot debe tener un mapa para cada área en la que opera \(diferentes pisos, por ejemplo\). Es importante crear mapas robustos y confiables para que el robot funcione de manera efectiva y segura.
{% endhint %}

En la sección `Maps`, creas o editas los mapas que usan los robots para navegar. Todos los mapas deben pertenecer a un sitio, que es el contenedor general de uno o más mapas utilizados en la misma instalación.

![Mapas de un sitio](../.gitbook/assets/image%20%283%29.png)

## Creación del Mapa

Para crear un mapa, primero ingrese un nombre para el mapa y seleccione el sitio al que debe pertenecer el mapa. Cuando presiona el botón `Create map`, se le dirige a la sección de dibujo y edición del mapa, donde encontrará las herramientas para dibujar el mapa y agregar varias características.

![Creaci&#xF3;n de mapa](../.gitbook/assets/image%20%284%29.png)

### Herramientas de Mapeo

La funcionalidad de mapeo incorporada hace posible dibujar un mapa conduciendo manualmente el robot por la instalación usando el joystick mientras el robot usa los sensores láser para mapear el área.

#### Métodos de mapeo

Existen dos métodos de mapeo: Hector y Cartographer.

* Hector mapea en forma de rama.
* Cartographer mapea circularmente.

Para más información, consulte los siguientes enlaces:

{% embed url="http://wiki.ros.org/hector\_mapping" %}

{% embed url="https://github.com/cartographer-project/cartographer" %}

También es posible cargar un mapa desde su computadora en formato PNG. Por ejemplo, si hay dibujos CAD de la instalación disponibles, es posible usarlos en lugar de mapear el área con el robot, pero también puede cargar mapas creados previamente con el robot y descargados a su PC.

{% hint style="warning" %}
Cuando descarga un mapa, solo se guardan los datos del mapa registrados, es decir, las características agregadas, como posiciones y zonas, no se guardan con el archivo de mapa. Si desea guardar un mapa con todos los detalles, debe exportar todo el sitio al que pertenece el mapa.
{% endhint %}

## Edición del Mapa

Una vez creado el mapa, es importante limpiar el resultado final con el editor de mapas.

![](../.gitbook/assets/image%20%281%29.png)

Consulte la [guía de referencia de los robots MiR](%20https://www.mobile-industrial-robots.com/media/5188/mir_robot_reference_guide_sw260_rev19_en.pdf) para más información.


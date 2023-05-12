# Regulacion_Chaleco
Este proyecto es un sistema de control de temperatura para un chaleco con dos zonas. Usa sensores y ventiladores para regular y mantener la temperatura deseada, con LEDs para indicar el estado de los ventiladores.

Este proyecto consiste en un sistema de control de temperatura para un chaleco, diseñado para mantener una temperatura confortable en dos zonas: la parte frontal y posterior. 

El sistema está basado en Arduino, con sensores de temperatura DHT11 ubicados en la parte frontal y posterior del chaleco. Estos sensores detectan continuamente la temperatura en ambas zonas. Los datos de los sensores son procesados por el microcontrolador Arduino, que decide si es necesario enfriar o calentar cada zona del chaleco.

Para regular la temperatura, el sistema cuenta con ventiladores en la parte frontal y posterior. Si la temperatura detectada por los sensores excede la temperatura deseada, los ventiladores se activan para enfriar la zona. En el caso contrario, si la temperatura está por debajo de la deseada, los ventiladores se apagan. 

Además, el chaleco cuenta con LEDs que indican el estado de los ventiladores: encendidos o apagados. Esto proporciona una retroalimentación visual rápida para el usuario.

El sistema también cuenta con dos botones que permiten al usuario ajustar la temperatura deseada. Un botón aumenta la temperatura deseada y el otro la disminuye, con un rango que va desde los 21 hasta los 26 grados Celsius.

El sistema está diseñado para mantener la temperatura deseada de forma constante y cómoda, independientemente de las condiciones ambientales. Además, puede ser usado en diferentes contextos, desde actividades al aire libre hasta entornos de trabajo.

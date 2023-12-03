# Ajustador de señal DDS (AD9833)
El modulo AD9833 es capaz de general señales para ser usadas para diversas aplicaciones, sin embargo, esta señal siempre es continua, es por esta razon que implemente este circuito, el cual consistene en llevar la señal a valores negativos, ademas de aumentar la ganancia de la señal de salida.

## Diagrama de bloques

![](https://i.imgur.com/EWl5Cgk.png)

El bloque de **POWER** esta porque con eso se genera un voltage negativo de **-5V** para el amplificador operacional, en este caso el **LM358**

## PCB
Todo el circuito esta en una cara asi que sera facil soldar.

![](https://i.imgur.com/hRr3kva.png)

Los archivos de fabricacion los puedes descargar [aqui](https://github.com/picli3/signal-adjustment-ad9833/releases/download/v1.0.0/v1.0.0.zip)

Mas información [maykolrey.com](https://maykolrey.com)
[licencia](./LICENSE)


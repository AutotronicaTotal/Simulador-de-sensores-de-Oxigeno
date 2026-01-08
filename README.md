Este repositorio contiene los codigos realizados por Miguel Cruz para desarrollar prototipos y proyectos del area automotriz.

El IDE utilizado es Arduino en la version 1.8.19.

Se agregaran los siguientes elementos para poder terminar el proyecto:

a) Diagrama del simulador de sensor de oxigeno

b) Codigo de Arduino

c) Libreria del DAC

Es importante ajustar el voltaje de salida del MT3608 a un valor minimo de 5 voltios antes de conector los componentes, pretar atención y leer las instrucciones en el diagrama.

Este simulador esta hecho para generar la señal del sensor de oxigeno de tipo planar de 4 cables.

Las señales que genera son las siguientes y se agrega el color que indica la señal generada.

1. Mezcla ideal - Led en color verde
2. Mezcla rica - Led en color rojo
3. Mezcla probre - Led en color azul
4. Sensor envejecido - Led en ccolor amarillo
5. Sensor postcatalizador - Led en color violeta

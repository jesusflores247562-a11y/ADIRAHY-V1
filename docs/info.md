<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works
Un decodificador que convierte entradas binarias (4 bits) en señales para un display de 7 segmentos de cátodo común (activado con 1 lógico).

## How to test

Conecta las 4 entradas  (A, B, C, D) a un interruptor DIP o a salidas lógicas (como un microcontrolador o generador).
Configura las entradas en '0000' (todas en bajo) y verifica que el display muestre el número '0'.
Ve cambiando las combinaciones binarias de 0000 a 1111 (0 a 15 en decimal) para observar la respuesta. Por ejemplo, al ingresar '0101' (5 en decimal), se deben encender los segmentos a, c, d, f, g para formar el dígito '5'.


## External hardware

1 x Display de 7 segmentos de cátodo común (Common Cathode)
1 x Circuito integrado decodificador (ej. 74LS48, CD4511 o FPGA/CPLD programada)
4 x Interruptores DIP o botones (para las 4 entradas de datos)
7 x Resistencias de 220 o 330 ohms (para limitar la corriente de los segmentos a, b, c, d, e, f, g)
1 x Protoboard y cables de conexión, fuente de alimentación de 5V.

UNIVERSIDAD DE LAS FUERZAS ARMADAS - ESPE

![](https://github.com/BraddJCJ/Informe5_Jerez_Sangoquiza_Zambrano/blob/master/img/Logo_ESPE.png)

¨Práctica de Laboratorio N°7 Características de la Onda Senoidal¨ - 
¨Fundamentos de Circuitos Eléctricos¨  
Integrantes: Jerez Bradd; Sangoquiza Andrés; Flores de Valgas Jonathan.  
NRC: 8702   
Fecha: 2020 - 08 - 19  

1.- PLANTEAMIENTO DEL PROBLEMA:

¿Hay alguna diferencia entre una función en fase con otra desfasada?¿Esta diferencia, es significativa en el análisis de un circuito con corriente alterna?¿Existe alguna importancia en la implementación de un sistema en corriente alterna?

2.- OBJETIVOS:

* General: 

Determinar exprimentalmente las características de señales senoidales.


* Específico:

1.- Identificar cada  uno de los elementos de la senoide.

2.- Simular el comportamiento senoidal de un circuito.

3.- Resolver la importancia en la implementación de un circuito CA en vez de uno CD. 


3.- MARCO TEORICO:

Una senoide adquiere este nombre, puesto que su trayectoria es la de una señal en forma de las funciones seno o coseno.
Este tipo de corriente es conocida por ser tipo ¨corriente alterna¨, lo que que significa que habrán alteraciones de signo en cada uno de sus intervalos.
Cabe mencionar, que el beneficio más grande de una senoide, recae sobre su distribución y aplicación, dado que son sencillas de generar y transmitir.
Por lo tanto, para una distribución de energía a una casa, pueblo o ciudad se aplica un sistema de corriente alterna.
 
Una tensión senoidal, está expresada de la siguiente forma:
![](https://github.com/BraddJCJ/Informe-7/blob/master/Img/Tension_Senoidal.png)

Además, la repetición de una senoide en un intervalo de tiempo, se la conoce como Período, con unidades en segundos [s]. En otras palabras, el periodo es el tiempo que tarda la función en dar un ciclo completo.

![](https://github.com/BraddJCJ/Informe-7/blob/master/Img/Periodo.png)![](https://github.com/BraddJCJ/Informe-7/blob/master/Img/Graf.Periodo.png)

Por otra parte, la frecuencia cíclica es el recíproco del periodo, donde sus unidades están expresadas en Hertz [Hz].

![](https://github.com/BraddJCJ/Informe-7/blob/master/Img/frecuenciaciclic.png)

Es importante tener en cuenta, que una función senoidal puede estar desfasada o en fase.
Decimos que está en fase, cuando la senoide corta por el origen de un plano, esto quiere decir, que la señal senoidal no está adelantada ni atrasada en función del tiempo.
Por el contrario, se dice que está en desface, cuando la función no corta por el origen de un plano, lo que quiere decir que la función está adelantada.

En esta gráfica, la tensión v2 se adelanta a la tensión v1 con un ángulo de desface  ¨fi¨.

![](https://github.com/BraddJCJ/Informe-7/blob/master/Img/faseydesface.png)



4.- DIAGRAMAS:

![](https://github.com/BraddJCJ/Informe-7/blob/master/Img/dig7.png)

5.- LISTA DE COMPONENTES:

![](https://github.com/BraddJCJ/Informe-7/blob/master/Img/Materiales.png)

 
6.- CONCLUSIONES:

-Es mejor diseñar un sistema de corriente alterna en vez de uno de corriente continua, puesto que facilita el análisis matemático detallado, además de la manipulación para un circuito dsitribuido a un área más extenza para su uso.

-El comportamiento de una senoide en fase o desface, permite concluir el flujo de corriente en función del tiempo, el cual, puede ser muy útil al momento de implementar un circuito eléctrico.

-Cada senoide consta de mínimo un argumento y una amplitud, puesto que esto permite identificar la frecuencia, el período y los picos máximos de amplitud de corriente o tensión.

7.- RECOMENDACIONES:

-Se recomienda tener en cuenta la posición de la senoide con respecto al tiempo para evitar errores al momento de determinar si la función está en fase o desface.

-Es necesario identificar las unidades para un correcto análisis, puesto que una alteración en las magnitudes puede perjudicar el significado gráfico de la senoide.

-Es factible realizar una relación en la practica, puesto que el simulador nos permite generar valores que pueden ser teoricos.

8.- CRONOGRAMA:

![](https://github.com/BraddJCJ/Informe-7/blob/master/Img/Cronograma.png)
 
9.- BIBLIOGRAFIA
 
- Sadiku Matthew N. (2006). Fundamentos de Circuitos Eléctricos. McGraw-Hill Interamericana. México D. F.
-  Richard C. Dorf y James A. Svoboda. (2006). Introduccion Circuitos Electronicos. 6ta Ed. John Willey & Sons, Inc. Mexico D.F.


 10.-ANEXOS:
 
 Analisis de Rsultados:
 
 Implemente el circuito que se representa a continuación:
 
 ![](https://github.com/BraddJCJ/Informe-7/blob/master/Img/img.1.png)
 
 - Ajuste el generador de funciones, para que proporcione una señal de 20 Vpp a una frecuencia de 2.5 KHz.
 - Conecte el osciloscopio al resistor de carga Rl. Observe la señal que aparece en el osciloscopio.
 
 ![](https://github.com/BraddJCJ/Informe-7/blob/master/Img/simulaci%C3%B3n.1.png)
 
 - Responda las sisguientes preguntas:
 ¿Cuántas divisiones por cuadro abarca la amplitud pico de la señal de salida?
 
Nosotros ubicamos la señal a 1 [V] para cada cuadro, al haber hecho una relacion co  10 [V] y obtener un resultado de 3.45 [V] en nuestro osciloscopio, el valor de voltaje en 20 Vpp en el osciloscopio es 6.90 [V] que representa alrededor de 6.9 cuadros.

¿En que valor esta posicionada la perilla VOLTS/DIV?

1 [Volts/Div]

¿Cuántas divisiones por cuadro abarca un ciclo completo de la señal de salida?

Al estar nuestra perrilla de Time/Div en 0.2 esta abarcara 3.3 cuadros para un ciclo en la señal de salida.

![](https://github.com/BraddJCJ/Informe-7/blob/master/Img/Ciclo%20por%20cuadro.png)

¿En que valor esta posicionada la perilla TIME/DIV?

0.2 [Time/Div]

-¿Cuál es la amplitud de voltaje y el periodo de la señal que aparece en la pantalla del osciloscopio?

Amplitud del voltaje: 6.9 [V]

Periodo: 665 [uS]

![](https://github.com/BraddJCJ/Informe-7/blob/master/Img/periodo.png)

- Determine la frecuencia natural [Hz] y la frecuencia angular [rad/s] de la señal de salida:

f: 1250 [Hz] -> 2500 [Hz]

w: 2πf= 2500π [rad/s]  -> 5000π [rad/s]

-Con el multímetro mida el voltaje en Rl: 2.43 [V]  ->  4.87 [V]

-Compare el voltaje en el punto anterior y el obtenido con el multímetro digital.

![](https://github.com/BraddJCJ/Informe-7/blob/master/Img/Sim.general.png)

¿Coinciden?

No coinciden.

¿Por qué?
 Porque en primer lugar el valor delmultimetro es un valor eficaz Vrms el cual es el voltaje del osciloscopio dividido para la raiz de 2.

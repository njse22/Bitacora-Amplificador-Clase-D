### BITACORA AMPLIFICADOR CLASE D

# Justificación del proyecto

El siguiente proyecto fue creado para la clase de señales y sistemas de la [Universidad ICESI](https://www.icesi.edu.co/)

__________________________________________________________________________________________________________________________

# Fase Uno del proyecto: Modulador

Para la primera face del proyecto se requirió implementar un modulador PWM, para esto se hizo una investigación (todas las fuentes se encuentran 
en las referencias del proyecto al final de la bitacora) sobre como funciona la modulación para un amplificador clase D. 

 # *Amplificadores operacionales* 
Se encontro que el funcionamiento de los moduladores PWM se pueden implementar con un modulador operacional el cual 
dadas dos señales de entrada 
genera con una multiplicación una señal de salida, para nuestra suerte ya contabamos con un amplificador operacional 
(de algun otro proyecto el 
cual no tengo presente), este era un JRC 4585; conectando un Analog Discovery el cual generaba dos señales, una señal 
triangular con una amplitud
de 4V con una frecuencia de 10Hz y una señal senoidal con una amplitud de 1V y una frecuencia de 1Hz (señal modulada y 
moduladora respectivamente)
conectadas a las entradas del amplificador operacional producian la señal mostrada en la Figura 1.

+---------------------+
| insertar Figura 1.  |
+---------------------+

como se puede ver en la figura esta señal no presenta una modulación correcta esto devido a una posible caracteristica 
interna de JRC 4585, después de  

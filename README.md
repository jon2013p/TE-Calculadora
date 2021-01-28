# TE-Calculadora

El presente proyecto es una aplicación nativa para Android desarrollada desde la herramienta Android Studio y basado en su totalidad en el lenguaje Java. 

Integrantes:
- Chantal Alejandra Morales Rojas
- Jonathan Israel Vásquez Vivas

Para la construcción de esta aplicación se siguieron ciertos pasos. 

Interfaz
* Se crearon dos inputtext que servirán en la inserción de los datos que serán calculados. Estos Input están limitados al uso de números para así evitar errores en la ejecución de las operaciones.
* Se colocó un TextView para la presentación de la respuesta. Se hizo un par de cambios en color y tamaño del texto.
* Se colocan 7 botones que lanzarán las respectivas funciones de cálculo configuradas.

MainActivity
* Se declaran las variables a utilizar en las funciones. Se declaran 7 variables para los botones, 3 para los input y textview y una variable double para el valor de porcentaje.
* Se crean las funciones de operación, una para cada botón, en las cuales se reciben como parámetros los valores introducidos en los input y se retorna el valor calculado de acuerdo a la naturaleza de la función.
* Finalmente, se asigna la función correspondiente a cada botón, para que de acuerdo al evento de interacción con el botón, el valor que se presentará en el textView cambie. 

Se realizan las pruebas respectivas y se configura para que los valores entregados por las funciones sean de tipo double y logren mostrar decimales.

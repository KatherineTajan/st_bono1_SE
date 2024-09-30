# Predicción de Energía Eléctrica de Microturbinas de Gas

Las turbinas de gas desempeñan un papel importante en los sistemas modernos de generación de energía y calor, cumpliendo diversas funciones como satisfacer la demanda pico, proporcionar respaldo a las fuentes de energía renovable y permitir la generación descentralizada de energía con pérdidas mínimas de transporte y conversión [Bielski et al., 2024)](https://dl.acm.org/doi/pdf/10.1145/3632775.3661967).

En este contexto, se presenta un conjunto de datos detallado que captura el comportamiento de una microturbina de gas comercial diseñada para hogares residenciales, que genera aproximadamente 3 kW de potencia eléctrica, para analizar y modelar su rendimiento.

Este conjunto de datos, compuesto por 71,225 instancias, registra la potencia eléctrica de salida en respuesta a señales de control de entrada a lo largo del tiempo. Su objetivo principal es permitir el aprendizaje del comportamiento temporal entrada-salida de la turbina utilizando técnicas de aprendizaje automático.

El dataset incluye ocho series temporales distintas, cada una representando un experimento único con diferentes condiciones de operación. Estas series se dividen en dos categorías principales: cuatro series rectangulares que muestran cambios instantáneos en la señal de control, y cuatro series continuas con cambios graduales. Esta diversidad en los datos permite un análisis completo de las dinámicas de la turbina, incluyendo los retrasos en la respuesta de salida y las transiciones entre estados estacionarios.

Se realizará un análisis exploratorio de datos, seguido de la implementación de varios modelos de pronóstico. Específicamente, se aplicarán técnicas de suavización exponencial de primer y segundo orden, incluyendo una variante con actualización del factor de descuento, así como el modelo Holt-Winters.

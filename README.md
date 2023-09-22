# Sensor Rotary Encoder KY-040

El sensor Rotary Encoder KY-040 es un dispositivo electromecánico utilizado para medir la rotación y la dirección de rotación de un eje. En este documento, exploraremos qué es un Rotary Encoder, para qué sirve, su composición interna, una conclusión general y un caso aplicable utilizando la Raspberry Pi Pico (Pi Pico) como plataforma de desarrollo.

## ¿Qué es un Rotary Encoder?

Un Rotary Encoder es un tipo de sensor que se utiliza para convertir el movimiento rotativo de un eje en una señal eléctrica que puede ser interpretada por un microcontrolador o un ordenador. Estos sensores son comunes en aplicaciones que requieren control de posición, como controladores de volumen, sistemas de navegación, impresoras 3D y más.

## Composición Interna

El Rotary Encoder KY-040 está compuesto por tres partes principales:

1. **Disco Codificador:** Este disco generalmente tiene un patrón de código binario en su superficie que se altera cuando se gira. El disco está conectado al eje que se está midiendo.

2. **Sensor Óptico:** El sensor óptico está ubicado cerca del disco codificador y utiliza una fuente de luz y un fotodetector para leer las interrupciones en el patrón del disco. Estas interrupciones se traducen en pulsos eléctricos.

3. **Electrónica de Decodificación:** La electrónica de decodificación procesa los pulsos generados por el sensor óptico y determina la dirección y cantidad de rotación.

## Conclusión General

Los Rotary Encoders son una solución efectiva y precisa para medir la rotación en aplicaciones diversas. Proporcionan retroalimentación en tiempo real sobre la posición del eje y son ampliamente utilizados en proyectos de electrónica y robótica.

## Caso Aplicable: Uso del Rotary Encoder KY-040 con la Raspberry Pi Pico

Un caso aplicable interesante sería utilizar el Rotary Encoder KY-040 junto con la Raspberry Pi Pico para controlar el brillo de una luz LED. A continuación, se presenta una breve descripción de cómo se podría implementar esto:

1. Conexión del Rotary Encoder KY-040 a la Raspberry Pi Pico.
   - Asegúrate de conectar correctamente los pines del sensor al Pi Pico.

2. Escritura de un programa en MicroPython.
   - Escribe un programa en MicroPython que lea los pulsos del Rotary Encoder y ajuste el brillo de una luz LED conectada al Pi Pico en función de la rotación del encoder.

3. Prueba y ajuste.
   - Carga el programa en el Pi Pico y prueba el sistema. Deberías poder controlar el brillo de la luz LED girando el encoder.

Este es solo un ejemplo de cómo se puede utilizar el Rotary Encoder KY-040. Las aplicaciones son variadas y dependen de la creatividad del desarrollador.

¡Espero que este documento te haya proporcionado una comprensión básica del Rotary Encoder KY-040 y cómo se puede aplicar con la Raspberry Pi Pico! Si tienes más preguntas o necesitas más detalles, no dudes en preguntar.

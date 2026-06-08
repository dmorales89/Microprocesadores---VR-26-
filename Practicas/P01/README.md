# Práctica 01 

## Objetivo: Configurar una salida digital del PIC16F887 para controlar el manejo de salidas digitales, parpadeo de 4 LEDs


## Material utilizado

- PIC16F887
- Protoboard
- 8 LEDs
- 8 Resistencias de 330 Ω
- Fuente de alimentación
- Programador PIC
- Cristal de Cuarzo de 8 MHz
- Resistencia de 1 kΩ
- Boton
---

## Circuito 

A continuación se muestra el circuito implementado en protoboard y su simulación en Proteus.

<br>

<div align="center">

<img src="circuito_p01.jpeg" width="350">

<br>

*Figura 1. Circuito armado en protoboard.*

</div>

<br><br>

<div align="center">

<img src="proteus_p01.jpeg" width="650">

<br>

*Figura 2. Simulación del circuito en Proteus.*

</div>

<br>

---


## Desarrollo

La práctica se dividió en tres partes para familiarizarse con el manejo de salidas digitales del microcontrolador PIC16F887 mediante el uso de LEDs.

### Parte 1: Encendido y apagado de LEDs

Se programó el microcontrolador para mantener encendidos 4 LEDs durante un intervalo de tiempo determinado y posteriormente apagarlos de manera simultánea. Este proceso se ejecutó de forma continua dentro de un ciclo repetitivo, generando un patrón periódico de encendido y apagado.

### Parte 2: Contador hexadecimal

Se implementó un contador hexadecimal utilizando los LEDs como indicadores visuales. Los estados de encendido y apagado de los LEDs representaban los valores binarios correspondientes a cada número hexadecimal, permitiendo observar la secuencia de conteo de manera visual.

### Parte 3: Caminata de LEDs

Se desarrolló una secuencia de desplazamiento utilizando 8 LEDs, donde cada LED se encendía y apagaba de forma consecutiva. Este efecto, conocido como "caminata de LEDs", generó un patrón visual de movimiento a lo largo de la hilera de LEDs, repitiéndose continuamente durante la ejecución del programa.

Mediante esta práctica se reforzaron los conceptos básicos de configuración de puertos digitales, control de salidas y generación de secuencias mediante programación en el PIC16F887.

---

## Código fuente

```c
// Pegar aquí el código utilizado

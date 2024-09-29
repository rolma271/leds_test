# Trabajo Práctico N°2 - Testing de Software en Sistemas Embebidos 

Este proyecto corresponde al Trabajo Práctico N°2 de la materia "Testing de Software en Sistemas Embebidos" en la Carrera de Especialización de Sistemas Embebidos UBA. El objetivo es desarrollar una capa de abstracción de hardware (HAL) para el control de un puerto de LEDs y realizar pruebas unitarias que validen el correcto funcionamiento de cada una de sus funcionalidades.

## Autor
> Marco Rolón Radcenco

## Estructura del Proyecto
El proyecto está estructurado con los siguientes archivos:

- leds.h: Archivo de cabecera con las funciones declaradas para el manejo del puerto de LEDs.
- leds.c: Implementación del HAL para el puerto de LEDs.
- test_leds.c: Archivo de pruebas unitarias que utiliza el framework de testing Unity para validar las funcionalidades del HAL.

## Tests

Tests implementados:

```
1 - Inicialización del puerto: Apaga todos los LEDs al iniciar.
2 - ncender un LED individual.
3 - Apagar un LED individual.
4 - Encender y apagar múltiples LEDs.
5 - Apagar todos los LEDs de una sola vez.
6 - Encender todos los LEDs de una sola vez.
7 - Consultar si un LED está encendido.
8 - Consultar si un LED está apagado.
9 - Verificar la creación de un puerto nulo.
10 - Pruebas dentro de los límites de LEDs.
11 - Pruebas fuera de los límites de LEDs.
```
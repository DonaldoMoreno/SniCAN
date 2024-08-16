# SniCAN 

## Descripción

Este proyecto consiste en el desarrollo de un sistema embebido que incluye tanto hardware como software. El objetivo del proyecto es crear un dispositivo autónomo capaz de adquirir los mensaje de un bus de CAN utilizando un microcontrolador IMXRT1060IEC, 
y una interfaz gráfica para la configuración y monitoreo.

## Características

- **Microcontrolador:** IMXRT1060IEC
- **Sensores y periféricos:** [Lista de sensores y periféricos, por ejemplo, MPU6050, OLED Display]
- **Software:**
  - **Firmware:** Implementado en C/C++ con uso de yocto zephyr.
  - **Interfaz gráfica:** Implementada en QT con Python.
- **Interfaz de usuario:** Interfaz gráfica (GUI) y línea de comandos (CLI) para configuración y monitoreo.
- **Conectividad:** CAN bus.
  
## Estructura del Repositorio

```plaintext
/SniCAN
├── /docs
├── /hardware
│   ├── /schematics
│   ├── /bom
│   ├── /fabricacion
│   ├── /simulaciones
│   ├── /documentacion
│   └── /mecanico
├── /firmware*
├── /software*
├── /simulaciones*
└── /tools*

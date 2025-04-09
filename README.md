# Proyecto Reloj_con_mas_clases

Este proyecto implementa un sistema de simulaciÃ³n de un reloj digital en Java, dividido en mÃºltiples clases para representar sus distintos componentes. Permite visualizar el avance del tiempo en segundos, minutos o incluso horas, utilizando estructuras de control como `for`, `while` y `do-while`.

## Estructura del Proyecto

```
Reloj_con_mas_clases/
â”‚
â”œâ”€â”€ componentes/
â”‚   â”œâ”€â”€ Esfera.java
â”‚   â”œâ”€â”€ Manecilla.java
â”‚   â”œâ”€â”€ Mecanismo.java
â”‚   â””â”€â”€ Reloj.java
â”‚
â”œâ”€â”€ herramientas/
â”‚   â”œâ”€â”€ CrearReloj.java
â”‚   â”œâ”€â”€ Simulador.java
â”‚   â””â”€â”€ Validador.java
â”‚
â”œâ”€â”€ interfaz/
â”‚   â”œâ”€â”€ Consola.java
â”‚   â””â”€â”€ Menu.java
â”‚
â”œâ”€â”€ Main.java
â””â”€â”€ README.md
```

## Funcionalidades

- **Esfera**: Muestra la hora actual en consola.
- **Manecilla**: Representa una unidad de tiempo (horas, minutos o segundos) y se encarga de su incremento cÃ­clico.
- **Mecanismo**: Controla el avance del tiempo segundo a segundo.
- **Reloj**: Mantiene el estado de las manecillas y gestiona el avance de tiempo correctamente.
- **Simulador**: Ejecuta simulaciones del reloj avanzando en tiempo real o acelerado.
- **Validador**: Recoge y valida entradas del usuario desde la consola.
- **MenÃº de Usuario**: Permite seleccionar entre distintas simulaciones:
  - SimulaciÃ³n de 15 segundos (`for`)
  - SimulaciÃ³n de 15 minutos (`while`)
  - SimulaciÃ³n de 15 horas (`do-while`)

## Requisitos

- **Java JDK 8 o superior**
- **IDE recomendado**: NetBeans, IntelliJ IDEA o Eclipse

## CompilaciÃ³n y EjecuciÃ³n

1. Clona el repositorio:

```bash
git clone https://github.com/tu-usuario/Reloj_con_mas_clases.git
cd Reloj_con_mas_clases
```

2. Compila el proyecto:

```bash
javac Reloj_con_mas_clases/**/*.java
```

3. Ejecuta el programa:

```bash
java Reloj_con_mas_clases.Main
```

## CrÃ©ditos

Proyecto desarrollado por HÃ©ctor Santiago GonzÃ¡lez Baltierra  
No. de cuenta: 322604322  

Este proyecto es de cÃ³digo abierto bajo la licencia MIT.

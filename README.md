# Simulador de Algoritmos de Planificación de Procesos

Este proyecto es un simulador web interactivo que implementa diferentes algoritmos de planificación de procesos comúnmente utilizados en sistemas operativos. La aplicación permite visualizar y comparar el comportamiento de varios algoritmos de planificación.

## Algoritmos Implementados

- **FCFS (First Come, First Served)**: Algoritmo no apropiativo que ejecuta los procesos en el orden en que llegan.
- **SJF (Shortest Job First)**: Algoritmo no apropiativo que selecciona el proceso con el menor tiempo de ráfaga.
- **SRTF (Shortest Remaining Time First)**: Versión apropiativa de SJF que selecciona el proceso con el menor tiempo restante.
- **RR (Round Robin)**: Algoritmo apropiativo que asigna un quantum de tiempo a cada proceso de forma circular.

## Características

- Interfaz gráfica intuitiva para ingresar procesos
- Visualización mediante diagrama de Gantt
- Cálculo de métricas importantes:
  - Tiempo de retorno promedio
  - Tiempo de espera promedio
  - Tiempo perdido promedio
  - Penalidad promedio
  - Tiempo de respuesta promedio
- Capacidad para agregar y eliminar procesos dinámicamente
- Representación visual de estados de procesos (ejecución, espera, bloqueado)

## Cómo Usar

1. Abra el archivo `Selector.html` en su navegador web
2. Seleccione el algoritmo de planificación que desea simular
3. En la interfaz del algoritmo:
   - Ingrese el nombre del proceso
   - Especifique el tiempo de llegada
   - Indique el tiempo de ráfaga
   - Para Round Robin, establezca el quantum de tiempo
4. Presione "Agregar" para incluir el proceso
5. Una vez ingresados todos los procesos, presione "Calcular"
6. Observe los resultados en el diagrama de Gantt y la tabla de métricas

## Estructura del Proyecto

- `Selector.html`: Página principal para seleccionar el algoritmo
- `FCFS.html`: Implementación del algoritmo First Come, First Served
- `SJF.html`: Implementación del algoritmo Shortest Job First
- `SRTF.html`: Implementación del algoritmo Shortest Remaining Time First
- `RR2.html`: Implementación del algoritmo Round Robin

## Equipo de Desarrollo

- Daniel Felipe Velandia Jerez – 20191020140
- Johan Sebastian Fontecha Soler – 20191578026
- Yeison Alexander Farfán Peralta – 20201020138
- Daniel Andres Marquez Torres - 20222020238

## Tecnologías Utilizadas

- HTML5
- CSS3
- JavaScript (ES6+)

## Requisitos del Sistema

- Navegador web moderno con soporte para HTML5
- No requiere instalación adicional
- No requiere conexión a internet

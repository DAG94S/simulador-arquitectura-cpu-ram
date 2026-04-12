# Simulador de Arquitectura: CPU, Caché, Buses y RAM

Este simulador educativo permite visualizar de forma interactiva la interacción entre la CPU, los buses de datos/direcciones, la memoria caché y la RAM de 64 Bytes. Está diseñado específicamente para enseñar conceptos fundamentales de arquitectura de computadores.

## Características Principales

- **Alineación por Potencias de 2:** Visualización del *Padding* (relleno) automático por hardware.
- **Buses Reales:** Animación de flujos de Control, Direcciones (Unidireccional) y Datos (Bidireccional).
- **Algoritmos de Asignación:**
  - First-Fit (Primer Ajuste)
  - Best-Fit (Mejor Ajuste)
  - Worst-Fit (Peor Ajuste)
- **Caché L1:** Implementación de política de reemplazo y visualización de Hit/Miss.
- **Análisis de Fragmentación:** Cálculo en tiempo real de fragmentación interna y externa.

## Uso

1. **Escritura:** Define el tamaño del proceso y el algoritmo para observar cómo se aloja en RAM.
2. **Lectura:** Ingresa una dirección para ver cómo la CPU solicita la palabra y la almacena en caché.
3. **Interacción:** Haz clic en cualquier bloque ocupado de la RAM para finalizar ese proceso y liberar el espacio.

## Tecnologías

- HTML5 / CSS3 (Tailwind CSS)
- JavaScript (Vanilla)

---
Desarrollado por Diego García (DAG94S).

# 🖨️ Prácticas de Impresión 3D

## 📌 Descripción
Este repositorio documenta el proceso técnico, las pruebas y los resultados obtenidos durante las prácticas de **impresión 3D (FDM)**. Se integran imágenes detalladas de la fase de manufactura aditiva en tiempo real y la evaluación de las piezas finalizadas para analizar parámetros como adhesión a la cama, nivelado y acabado superficial.

---

## 🎯 Objetivos

- **Comprender el funcionamiento FDM:** Analizar el comportamiento del extrusor, la temperatura del *hotend* y la cama caliente.
- **Calibración y nivelación:** Ajustar la altura del eje Z (*Z-offset*) y la distancia de la boquilla (*nozzle*) para asegurar una primera capa homogénea.
- **Monitoreo en tiempo real:** Supervisar la deposición del filamento (PLA/PETG) para detectar desprendimientos o delaminación.
- **Análisis de calidad y resolución de problemas:** Evaluar defectos comunes como subextrusión, *stringing* (hilos) o problemas de adherencia en el soporte de la pieza.
- **Optimización de parámetros en Slicer:** Ajustar grosor de capa, porcentaje de relleno (*infill*) y velocidades de impresión.

---

## 🧰 Especificaciones Técnicas de la Práctica

| Parámetro | Detalle |
| :--- | :--- |
| **Tecnología** | Modelado por Deposición Fundida (FDM) |
| **Material** | Filamento PLA Rojo (1.75 mm) |
| **Componentes de Impresora** | Extrusor Directo / *Hotend* con sensor de nivelado automático |
| **Superficie de Impresión** | Cama microperforada de vidrio / PEI |

---

## 📸 Evidencias del Proceso de Impresión

### 1. Monitoreo del Proceso de Extrusión
En esta etapa se observa el cabezal de impresión aplicando las primeras capas del modelo (*raft* / bordes de adherencia). La luz del sensor de nivelación confirma el control de altura constante sobre la cama caliente.

![Proceso de Impresión 3D](imagenes/proceso_impresion.jpg)

### 2. Resultado Final de la Pieza
Pieza terminada correspondiente a un diseño con relieve (emblema/zorro sobre base decorativa). 

* **Observaciones técnicas:**
  * Se aprecia la textura del trazado de la primera capa y el patrón de relleno (*infill*).
  * Presencia de leves hilos finos (*stringing*), solucionables mediante el ajuste de retrazado (*retraction distance/speed*) en el software laminador.

![Resultado de Pieza Impresa](imagenes/pieza_final.jpg)

---


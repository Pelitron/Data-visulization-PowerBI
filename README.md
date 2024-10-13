# Dashboard para Fábrica PIMA (Subcontratista Renault)

Este dashboard está diseñado para monitorizar el rendimiento de la fábrica en tres áreas clave: Rendimiento de Operarios (RO), Eficiencia General de los Equipos (OEE) y Calidad. El objetivo es mantener estas métricas dentro de los límites establecidos: RO > 80%, OEE > 75% y Calidad < 2500 ppm.
Está optimizado para un monitor de 13 a 15 pulgadas.

## Estructura del Dashboard:

### El dashboard se divide en tres pestañas, una para cada métrica:

- Pestaña Rendimiento de Operarios (RO):
Muestra el rendimiento individual de cada operario.
Permite identificar a los operarios con bajo rendimiento para tomar medidas correctivas.

- Pestaña Eficiencia General de los Equipos (OEE):
Muestra el OEE general de la fábrica y de cada equipo individual.
Permite identificar las áreas donde se puede mejorar la eficiencia.

- Pestaña Calidad:
Muestra el número de piezas defectuosas por millón de piezas producidas (ppm).
Permite identificar las causas de los defectos y tomar medidas para reducirlos.
Cálculo de las Métricas:

### Rendimiento de Operarios (RO):

El RO se calcula como la relación entre la producción real de un operario y su producción esperada, expresada en porcentaje.

 
RO = (Producción Real / Producción Esperada) * 100
Use code with caution
Producción Real: Número de piezas producidas por el operario en un período de tiempo determinado.
Producción Esperada: Número de piezas que se espera que el operario produzca en el mismo período, según los estándares de producción.

### Eficiencia General de los Equipos (OEE):

El OEE se calcula como el producto de tres factores: Disponibilidad, Rendimiento y Calidad.

 
OEE = Disponibilidad * Rendimiento * Calidad

Disponibilidad: Porcentaje del tiempo que el equipo está disponible para producir, teniendo en cuenta las paradas planificadas y no planificadas.

Rendimiento: Relación entre la velocidad real de producción y la velocidad teórica máxima, expresada en porcentaje.

Calidad: Porcentaje de piezas producidas que cumplen con los estándares de calidad.

### Calidad:

La calidad se mide en partes por millón (ppm) y se calcula como el número de piezas defectuosas dividido por el número total de piezas producidas, multiplicado por un millón.

 
Calidad (ppm) = (Número de Piezas Defectuosas / Número Total de Piezas Producidas) * 1000000

# Sistema automatizado de presupuestos para herrería

## Descripción

Previamente, la elaboración de presupuestos se realizaba en múltiples planillas de Excel, lo que dificultaba el seguimiento de los trabajos aceptados y requería realizar tareas manuales repetitivas. 

Para optimizar este proceso, se desarrolló un sistema en Google Sheets con Apps Script que centraliza la información y automatiza las principales tareas.

El sistema permite generar presupuestos, asignar IDs automáticos, unificar los trabajos aceptados en una base global y asi poder registrar ingresos y egresos, calcular costos y hacer seguimiento de cada trabajo.

## Funcionamiento
  
- Generación automática de presupuestos a partir de una plantilla.
- Asignación automática de un ID para cada presupuesto.
- Cálculo automático de materiales, insumos, mano de obra, márgenes y total del presupuesto.
- Cambio de estado del presupuesto (aceptado o cancelado).
- Registro automático de los presupuestos aceptados en una base de datos global.
- Los ID de los presupuestos aceptados pasan a estar disponibles para seleccionarlos desde la planilla de Movimientos.
- Registro de ingresos y egresos asociados a cada trabajo.
- Seguimiento de costos, rentabilidad y resultado de cada trabajo.

## Capturas del proyecto

### Plantilla de presupuesto
![Plantilla de presupuesto](imagenes/plantilla-presupuesto.png)

### Registro de presupuestos
![Registro de presupuestos](imagenes/registro-presupuestos.png)

### Movimientos
![Movimientos](imagenes/movimientos.png)

### Resultado por trabajo
![Resultado por trabajo](imagenes/resultado-trabajo.png)


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
![Plantilla de presupuesto](imagenes/01-plantilla-presupuesto.png)

- Plantilla utilizada para crear nuevos presupuestos. Incluye fórmulas, listas desplegables y campos predefinidos para agilizar la carga de información.

### Cálculos del presupuestos
![Cálculos del presupuestos](imagenes/02-calculo-presupuesto.png)

- Calculos de materiales, insumos, mano de obra, gestión y costo total del presupuesto.

### Presupuesto generado
![Presupuesto generado](imagenes/03-presupuestos-generados.png)

- Cada presupuesto se crea a partir de la plantilla y recibe un ID único.

### Cambio de estado
![Cambio de estado](imagenes/04-cambio-estado.png)

- El estado del presupuesto puede actualizarse mediante una lista desplegable.

### Base global
![Base global](imagenes/05-base-presupuestos-global.png)

- Los datos de los presupuestos aceptados pasan a una base global centralizando la información.

### Registro de Movimientos
![Registro de Movimientoso](imagenes/06-planilla-movimientos.png)

- Los ID de los presupuestos aceptados quedan disponibles en una lista desplegable para registrar los ingresos y egresos asociados a cada trabajo.

### Vista para el cliente
![Vista para el cliente](imagenes/07-vista-cliente.png)

- Vista previa del presupuesto para compartir con el cliente.

### Trabajos extra
![Trabajos extra](imagenes/08-trabajos-extra.png)

- El sistema permite registrar ingresos y egresos de trabajos extra mensuales que no están asociados a ningun ID de presupuesto.

### Resultado por trabajo
![Resultado por trabajo](imagenes/09-resultado-por-trabajo.png)

### Resumen mensual
![Resumen mensual](imagenes/10-resumen-mensual.png)



 


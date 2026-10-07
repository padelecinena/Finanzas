# Control de Gastos — MVP

MVP local para clasificación y control de gastos personales.

## Cómo abrirlo

No necesita servidor ni instalación: abre `index.html` en Chrome, Edge, Safari o Firefox.

## Qué incluye

- Dashboard de ingresos, gasto registrado, gasto base y margen.
- Movimientos con búsqueda y filtros.
- Corrección manual de categorías.
- Motor de reglas por nombre de comercio.
- Reglas iniciales basadas en las clasificaciones definidas durante el proyecto.
- Presupuesto mensual editable.
- Persistencia mediante `localStorage` del navegador.
- Importación CSV sencilla.

## CSV

La importación acepta columnas:

`fecha,comercio,importe,cuenta`

También acepta `concepto` en lugar de `comercio` y separador `;`.

## Próxima versión recomendada

1. Importación directa de PDFs bancarios.
2. Normalización avanzada de comercios.
3. Detección automática de transferencias, pagos de tarjeta y devoluciones.
4. Recurrencia y prorrateo trimestral.
5. Eventos (cumpleaños, viajes, celebraciones).
6. Presupuesto base vs flexible vs extraordinario.
7. PostgreSQL para sincronizar datos entre dispositivos.
8. Despliegue web y autenticación.

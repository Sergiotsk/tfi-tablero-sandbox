# Formato provisorio del informe de pagos

Ejemplo para el sandbox del tablero. Lo usamos hasta que la facultad confirme el formato real
(consulta T04).

Archivo CSV, una fila por pago:

| Columna | Ejemplo | Descripción |
|---|---|---|
| `id_postulacion` | `2026-2C-0001` | ID que el aspirante presenta al pagar |
| `fecha` | `2026-10-09` | Día del pago |
| `importe` | `15000.00` | Importe cobrado |

Las filas cuyo `id_postulacion` no coincide con una Postulación pendiente aparecen en el resumen
como "sin coincidencia".

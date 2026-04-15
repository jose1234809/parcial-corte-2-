# Parcial 2 - Cafetería U. Sabana

## Autor
- Jose Daniel Escobar Huertado

## Paso a Paso Realizado

1.  Archivos sucios:
   - `parcial_2_productos_sucios.csv`
   - `parcial_2_clientes_sucios.csv`
   - `parcial_2_proveedores_sucios.csv`

2. Cargué los CSV en DataFrames de Pandas.
3. Limpié y normalicé los datos:
   - productos: separé `producto` y `categoria`, convertí `precio` y `stock` a numéricos, formateé fechas.
   - clientes: separé `nombre` y `tipo`, completé correos y teléfonos faltantes, eliminé la columna `edad` como dato derivado.
   - proveedores: separé `empresa` y `ciudad`, completé valores faltantes de contacto, teléfono y correo.

4. Guardé los DataFrames limpios en:
   - `parcial_2_productos_limpios.csv`
   - `parcial_2_clientes_limpios.csv`
   - `parcial_2_proveedores_limpios.csv`

5. Creé la base de datos SQLite `parcial_2_cafeteria.db` y exporté los 3 DataFrames como tablas.
6. Creé la tabla `ventas` con llaves foráneas y realicé operaciones SQL:
   - INSERT de 5 registros.
   - SELECT con INNER JOIN para mostrar cliente, producto y total de venta.
   - UPDATE de `id_venta = 1`.
   - DELETE de `id_venta = 3`.

## Archivos generados
- `parcial_2_productos_sucios.csv`
- `parcial_2_clientes_sucios.csv`
- `parcial_2_proveedores_sucios.csv`
- `parcial_2_productos_limpios.csv`
- `parcial_2_clientes_limpios.csv`
- `parcial_2_proveedores_limpios.csv`
- `parcial_2_cafeteria.db`
```

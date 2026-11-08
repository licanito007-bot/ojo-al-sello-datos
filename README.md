# Ojo al Sello: base de alertas alimentarias

Base pública que usa la app **Ojo al Sello** para mostrar el historial sanitario de una marca o producto.

- `alertas.json`: alertas alimentarias oficiales (retiros de lotes por Listeria, toxinas, botulismo, etc.) con fecha, marca, producto, lote, motivo, medida y fuentes.
- Las alertas vienen de comunicados oficiales de la autoridad sanitaria de Chile (Minsal y Seremis) y de la prensa que los cita. Cada registro enlaza a sus fuentes.
- Cada alerta corresponde a un lote puntual que la autoridad mandó retirar; no implica que otros lotes o productos de la marca tengan el problema.
- `rial.json`: eventos de inocuidad alimentaria en Chile (consumo humano) de la Red de Información y Alertas Alimentarias (RIAL) de ACHIPIA, desde 2013, por tipo de producto. Tomado de la base pública del Portal RIAL (www.achipia.gob.cl). No trae marcas ni lotes.

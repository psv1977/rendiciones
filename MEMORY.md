# Estado del proyecto

## Proposito vigente

Construir una aplicacion web interna e independiente de MaintLab para registrar gastos de IMANSL, conservar sus respaldos privados y exportar los registros filtrados a Excel o PDF para revision interna o entrega al contador.

## Decisiones vigentes

- Tecnologia objetivo: Python 3.13, Django 5.2 LTS, PostgreSQL y aplicacion server-rendered.
- Interfaz y documentacion en espanol; codigo tecnico en ingles.
- Los documentos admitidos seran imagenes y PDF. Los archivos reales nunca se versionan y requeriran autorizacion para descargarse.
- Las exportaciones deben respetar los filtros aplicados, incluidos fecha, proveedor, categoria, tipo de documento y estado de revision.
- No existe eliminacion fisica ordinaria: los registros se anulan o archivan y conservan trazabilidad.
- El MVP no incluye SPA, DRF, OCR, SII, integraciones bancarias, Transbank, pagos, facturacion electronica, IA ni integracion con MaintLab.
- La lectura de varias boletas incluidas en una hoja A4 es una capacidad futura por especificar; no se implementa en el MVP.
- No se deben subir datos reales, documentos reales, RUT, montos ni secretos al repositorio.

## Estado actual

- Solo existe la gobernanza inicial del repositorio.
- Aun no se crea el proyecto Django, no se instalan dependencias, no se generan migraciones y no existen especificaciones de funcionalidad.
- La primera especificacion prevista corresponde a gastos base en `spec/features/001-core-expenses/`.

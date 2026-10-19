# Gobernanza del repositorio

- Este repositorio es independiente de MaintLab; no compartir codigo, configuracion ni integraciones.
- La aplicacion organiza gastos de IMANSL y respaldos privados para revision interna o del contador; no reemplaza la contabilidad ni determina aceptacion tributaria.
- Usar Python 3.13, Django 5.2 LTS, PostgreSQL y renderizado en servidor. No usar SPA ni DRF en el MVP.
- La interfaz y la documentacion se escriben en espanol; el codigo tecnico se escribe en ingles.
- No incorporar al repositorio datos reales, documentos reales, RUT, montos ni secretos.
- Los adjuntos reales son privados y solo se descargan tras autenticacion y autorizacion.
- No realizar eliminacion fisica ordinaria de gastos o respaldos: anular o archivar con trazabilidad.
- El MVP excluye OCR, SII, bancos, Transbank, pagos, facturacion electronica, IA e integraciones con MaintLab.
- No instalar dependencias, crear el proyecto Django, generar migraciones ni hacer commits sin una instruccion explicita.

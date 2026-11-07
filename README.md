# Buscador de Licitaciones – INNOVATEK

Prototipo del Proyecto de implementación de IA. Asistente de IA que ayuda a encontrar contratos y documentos de licitaciones, sus vigencias y la licitación relacionada. Todos los documentos son **ficticios**.

**App en línea:** https://innovatek-buscador-64588.azurewebsites.net

**Documentación completa:** ver el archivo `documentacion_innovatek_FINAL.md` (problema, solución, pruebas e IA responsable).

## Cómo funciona
- Página web (Node.js + Express) con chat conectado a un agente de Microsoft Foundry.
- El agente usa el modelo `gpt-4.1-mini` y la herramienta Búsqueda de archivos sobre 10 PDFs.
- Se publica en Azure App Service; se conecta a Foundry con identidad administrada (sin llaves).

## Funciones de la página
- Chat con fuentes visibles, preguntas sugeridas y panel de documentos.
- Botón "Marcar para revisión" y lista de pendientes de revisión humana.
- Exportar la conversación en Markdown.
- Aviso de IA, modo claro/oscuro y diseño para celular.

El archivo `.env` no se sube al repositorio.

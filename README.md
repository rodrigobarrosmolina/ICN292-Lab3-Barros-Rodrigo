# ICN292-Lab3-Barros-Rodrigo


## Laboratorio 3 — Flujo de Triage de Devoluciones en n8n

- **Alumno:** Rodrigo Barros
- **RUT:** 22.228.674-3 (S = 674)
- **Fecha:** 23 de septiembre de 2026
- **Asignatura:** ICN-292 Sistemas de Información para la Gestión

## Parámetros
- S = 674
- U = 54.000
- D = 21

## Archivos
- `ICN292-Lab3-Informe.pdf` — Informe completo
- `ICN292-Lab3-Informe.docx` — Informe en Word
- `Triage-Devoluciones.json` — Workflow principal de triage
- `Emisor.json` — Workflow emisor de solicitudes
- `Resumen-Programado.json` — Workflow de resumen diario

## Cómo reproducir
1. Importar los archivos .json en n8n (Settings → Import workflow)
2. En el workflow de Triage, abrir el Webhook y usar la URL de test
3. Enviar solicitudes via POST con el workflow Emisor o desde Hoppscotch
4. Ejecutar el workflow de Resumen para ver las métricas consolidadas

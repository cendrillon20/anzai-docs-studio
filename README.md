# 🦊 Anzai Docs Studio

Editor web de documentos con cuatro temas: Día, Noche, Noche neón arcoíris y Día arcoíris.

## Probar

Abre `index.html` en Chrome o Edge. No requiere instalación ni servidor para la interfaz inicial.

## Funciones actuales

- Editor de texto enriquecido y barra de formato.
- Cuatro temas con persistencia local.
- Guardado automático en el navegador.
- Importación de TXT y HTML como texto.
- Exportación a PDF mediante el diálogo de impresión del navegador.
- Panel de Anzai con modelo Qwen2.5-0.5B-Instruct opcional, ejecutado localmente en el navegador mediante Transformers.js y WebGPU. La descarga inicial requiere internet y puede consumir memoria considerable.

## Pendiente

- Analizador real de documentos PDF/DOCX.
- Backend opcional para IA de mayor capacidad y compatibilidad con dispositivos sin WebGPU.
- Perfiles de estilo y reproducción de estructura documental.
- Redacción extensa por secciones y control de 100 páginas reales.
- Guardado en servidor, historial de versiones y exportación avanzada.

**Nota:** Esta versión es un prototipo funcional de interfaz, no un generador automático de PDF de 100 páginas.

## Publicación

Se incluye un workflow de GitHub Pages. La URL prevista es `https://cendrillon20.github.io/anzai-docs-studio/`. Comprueba el estado en Actions y Settings → Pages; la publicación requiere que GitHub Pages esté habilitado y el despliegue termine correctamente.

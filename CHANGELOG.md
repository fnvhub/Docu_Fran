# DocuFran — Historial de versiones

## v1.2.2 — 2026-05-10
### Correcciones
- Versión leída automáticamente desde CHANGELOG, sin tocar index.html
- CSV: 378 filas con nombre de archivo en columna Tipo corregidas
- El nombre del archivo ya no aparece como etiqueta de tipo en las tarjetas

## v1.2.1 — 2026-05-10
### Correcciones
- Nombre del documento más prominente en las tarjetas

## v1.2.0 — 2026-05-10
### Novedades
- Fichas y Fichas nuevas como filtros separados en grupo Producto
- Nuevo filtro Ayuda de visita y Presentación en Producto
- Nuevo grupo Tipo doc: Rellenable, Lista asistentes, Hoja de pedido, Sin duplicado
- Nuevo grupo Persona: Fran, Xavier, Maria Vinales, Alvaro Huercano
- Nuevo grupo Año: 2022, 2023, 2024, 2025, 2026
- Filtro Sin duplicado para ver solo originales
- Descripciones inteligentes generadas para todos los documentos del CSV

## v1.1.1 — 2026-05-10
### Correcciones
- Lectura correcta de columnas Grupo y Tipo del CSV (BOM y comillas en cabecera)
- Filtros muestran ahora el recuento real de documentos por grupo

## v1.1 — 2026-05-10
### Novedades
- Filtros desplegables por grupos: Producto, Terapéutico, Comercial, Formación, Clientes, Gestión
- Selección múltiple de filtros — combina "embarazo" + "fichas" + "2024" a la vez
- Filtros de exclusión — oculta Download, SEPA, Pedidos, Backup con un toque
- Barra de filtros activos — ves qué tienes activado y los quitas con un toque
- Favoritos — estrella en cada documento, botón ⭐ en cabecera para ver solo favoritos
- Búsqueda con tolerancia a errores — "ergifilus" encuentra "ergyphilus"
- Búsqueda multi-palabra — "ficha omega embarazo" busca los tres términos
- Script PowerShell v2 — genera CSV enriquecido con Grupo y Tipo automáticos
- Etiquetas personales mejoradas — se muestran en verde en la tarjeta

## v1.0 — 2026-05-10
### Lanzamiento inicial
- Búsqueda full-text con sinónimos
- Filtros en dos filas: Gestión y Terapéutico
- Modo claro/oscuro
- Modal de documento con ruta, acciones y editor de etiquetas
- CSV configurable desde ajustes
- PWA instalable (manifest + service worker)
- Optimizada para móvil y tablet horizontal

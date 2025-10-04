## Descripción del proyecto

**SaludPro** es un proyecto académico de **gestión de inventarios** para una cadena de farmacias, la cual se construira como una **API REST** (Spring Boot + MongoDB) que centraliza la administración de **franquicia, sucursales, productos y movimientos** (entradas/salidas). La solución aplica reglas de negocio (no permitir stock negativo), registra historial de movimientos y ofrece consultas útiles como el **producto con mayor stock por sucursal**, además de reportes básicos (PDF/Excel) y alertas por **stock mínimo** o **vencimiento**.

### Objetivo
Unificar y automatizar el control de inventarios en SaludPro para reducir errores operativos, mejorar la disponibilidad de medicamentos y habilitar decisiones con datos en tiempo real.

### Funcionalidades clave
- CRUD de franquicia/sucursales y productos.
- Movimientos de inventario con validaciones (entradas/salidas, sin stock negativo).
- Historial de transacciones y reporte de **top stock** por sucursal.
- Reportes exportables (PDF/Excel).
- Alertas por umbrales de stock y fechas de vencimiento (job programado).

### Arquitectura (alto nivel)
- **Backend:** Spring Boot (API REST)  
- **Base de datos:** MongoDB Atlas  
- **Despliegue:** Railway/Render (free tier)  
- **Docs de API:** Swagger/Postman

### Gestión del trabajo
Metodología **Kanban** en Trello con **historias de usuario** (ID, descripción y criterios de aceptación). Evidencia de colaboración del equipo a través de **ramas**, **Pull Requests** y **reviews**.

### Entregables del primer corte
Contextualización y problema, alcance, objetivos, **EDT**, stakeholders, riesgos, **presupuesto**, diagramas de flujo e historias de usuario; más la estructura del repositorio para documentación, imágenes y tablas.  
**Meta:** despliegue de la API antes del **14/dic/2025** y video demo.


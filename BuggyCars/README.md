# 🚗 Buggy Cars Rating - QA Testing

## 📝 Resumen del Proyecto
Este documento detalla la ejecución y reporte de pruebas manuales exploratorias y funcionales realizadas sobre la aplicación web Buggy Cars Rating. El objetivo principal fue validar la lógica de negocio, los límites de entrada y la robustez de los formularios web de la plataforma.

## 🛠️ Entorno y Herramientas
* **Gestión de Incidencias (Issue Tracking):** Jira Software (Tablero Kanban)
* **Captura de Evidencia:** FlamesHot
* **Tipos de Pruebas:** Funcionales, Casos Límite (Edge Cases) y Pruebas Negativas.
* **Reportes de rendimiento:** LightHouse

## 🐛 Reporte de Bugs Destacados

A continuación se detallan los defectos críticos encontrados. Cada reporte incluye evidencia técnica capturada interceptando las peticiones HTTP y los logs de consola.

| ID | Módulo | Descripción del Bug | Severidad | Evidencia Técnica | Estado en Jira |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **BUG-01** | Perfil | a pagina de actualizar perfil permite actualizar el perfil de un usuario con caracteres especiales (!”#$%/) | Alta | [🔗 Ver Reporte en JIRA](https://ivesdev21.atlassian.net/browse/KAN-1?atlOrigin=eyJpIjoiYzUyMjAxMzRhYzIzNDYyM2FmNjNiNTM2NTRjZmQxYTAiLCJwIjoiaiJ9) | In Progress |
| **BUG-02** | Registro | El usuario puede modificar los datos “nombre” y “apellido” dejando en blanco los campos permitiendo al usuario validar los cambios | Critica | [🔗 Ver Reporte en JIRA](https://ivesdev21.atlassian.net/browse/KAN-4?atlOrigin=eyJpIjoiNWNkODAzMGU3ZGIxNGExZjg3OTY4N2VhOTA1MDhjZmMiLCJwIjoiaiJ9) | Ready for QA |

---
*Perfil de LinkedIn:* [Ives Acosta](https://www.linkedin.com/in/ives-acosta)


## ⚡ Análisis de Rendimiento y Accesibilidad
Además de las pruebas manuales, se ejecutó una auditoría automatizada utilizando Google Lighthouse para evaluar la salud general de la aplicación web.





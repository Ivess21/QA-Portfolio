# QA Portfolio | Ives Agustín Acosta

QA Tester Jr. en formación | Estudiante de Ingeniería en Sistemas (UTN FRC)
📍 Córdoba, Argentina · 🔗 [LinkedIn](https://www.linkedin.com/in/ives-acosta/?isSelfProfile=true) · ✉️ [ivesdev21@gmail.com]

## Sobre mí

Estudiante de Ingeniería en Sistemas de Información (UTN FRC) y QA Tester Jr. en formación, con foco en testing funcional y exploratorio y en seguridad del software. Vivo en Río Segundo, Córdoba, Argentina.

**Qué hago en testing:** diseño casos de prueba, ejecuto pruebas funcionales y exploratorias, y reporto defectos con pasos reproducibles y evidencia (Jam.dev). Practico flujos de trabajo ágiles en Jira sobre aplicaciones web.

**Entornos:** trabajo a diario con Windows y Linux (Debian), lo que me permite reproducir fallas en distintos sistemas operativos y moverme con comodidad en la terminal.

**Seguridad:** participo en el grupo de estudio y academia de ciberseguridad de la UTN FRC, donde practico fundamentos de pentesting y laboratorios de PortSwigger (Web Security Academy). Esto me da una mirada de riesgo al momento de probar.

**Experiencia previa:** trabajé en servicio técnico y logística (Estructuras Vega, 2025) y llevo mi propio emprendimiento de reparación (HardReset, desde 2025). Ahí desarrollé diagnóstico de fallas, documentación de incidencias y trato directo con clientes, habilidades que aplico al análisis y reporte de defectos.

**Idiomas:** inglés B2 (lectura técnica y comunicación escrita) y portugués básico.

**Qué busco:** mi primera posición como QA Tester Jr. en un equipo donde pueda aportar rigor analítico, aprender procesos reales y crecer hacia automatización y seguridad.


## Proyectos

### 1. BuggyCars (aplicación web de práctica)
- **Tipo de testing:** [funcional, exploratorio, regresión…]
- **Qué hice:** [X casos de prueba, Y bugs reportados, Z flujos cubiertos]
- **Herramientas:** Jira, Flameshot.
- **Entregables:**
  - [Plan y casos de prueba](link)
  - [Reportes de bugs](link)
  - [Tablero Jira](https://ivesdev21.atlassian.net/jira/software/projects/KAN/boards/1?filter=&groupBy=none&atlOrigin=eyJpIjoiYzUxNmRlNmY0NmJhNDEzZGJjOTFkODM3YTU4YTUxZTEiLCJwIjoiaiJ9)
  
### 2. Secret Sauce
# Sauce Demo | Automatización E2E con Cypress

![Estado](https://img.shields.io/badge/estado-en%20pausa-yellow)
![Cypress](https://img.shields.io/badge/Cypress-16.x-17202C)

Suite de pruebas end-to-end automatizadas con Cypress sobre [Sauce Demo](https://www.saucedemo.com), un e-commerce de demostración creado por Sauce Labs para practicar testing. El objetivo es validar los flujos principales de forma repetible y detectar regresiones.

## ⏸️ Estado del proyecto: en pausa

- **Última actualización:** 05-11-2026
- **Motivo de la pausa:** [ej. priorizar otro proyecto de práctica]
- **Cómo retomarlo:** ver la sección [Próximos pasos](#próximos-pasos)

## Alcance


| Módulo | Estado | Notas |
|--------|--------|-------|
| Login (usuarios válidos e inválidos) | [x] / [ ] | [ej. data-driven con fixture] |
| Inventario (listado, ordenamiento) | [x] / [ ] | |
| Carrito (agregar y quitar productos) | [x] / [ ] | |
| Checkout (flujo completo y validaciones) | [x] / [ ] | |
| Logout | [x] / [ ] | |
| Usuarios especiales (`problem_user`, `performance_glitch_user`) | [ ] | Pendiente |

**Fuera de alcance:** performance bajo carga, seguridad, accesibilidad y diseño responsive.

## Stack

- Cypress versión: 16.2.0
- Node.js versión: v24.22.1
- JavaScript
- Entorno de desarrollo: Debian GNU/Linux 13, Chrome

## Estructura

```
cypress/
├── e2e/
│   └── [nombre-del-archivo].cy.js    ← tests agrupados por módulo
├── fixtures/
│   └── usuarios.json                 ← datos de prueba (data-driven)
└── support/
cypress.config.js
package.json
```

## Cómo ejecutarlo

Requisitos: Node.js 20.x, 22.x o 24.x o superior y las dependencias de sistema de Cypress para Linux.

```bash
git clone [URL-del-repo]
cd [nombre-de-la-carpeta]
npm install
npx cypress install      # descarga el binario si npm lo bloqueó
npx cypress open         # modo interactivo
npx cypress run          # modo headless
```

### Usuarios de prueba

Son los que el propio sitio publica en su pantalla de login. No son datos reales.

| Usuario | Comportamiento esperado |
|---------|-------------------------|
| `standard_user` | Acceso normal |
| `locked_out_user` | Acceso bloqueado |
| `problem_user` | Presenta defectos visuales y funcionales |
| `performance_glitch_user` | Respuestas lentas |

## Resultados de la última ejecución

- **Fecha:** 05-11-2026
- **Navegador:** 157.0.8103.38
- **Evidencia:** [captura o video de la ejecución](link)

## Problemas conocidos

- Al instalar Cypress con npm, el script de descarga del binario puede quedar bloqueado. Se resuelve con `npx cypress install`.

## Próximos pasos

1. Cubrir `problem_user` y `performance_glitch_user`.
2. Validar subtotal, impuestos y total en el resumen del checkout.
3. [Refactorizar con comandos personalizados o Page Object Model.]
4. [Integrar la ejecución en GitHub Actions.]

## Qué aprendí


## Autor

**Ives Agustín Acosta** · Estudiante de Ingeniería en Sistemas (UTN FRC) · QA Tester Jr. en formación
🔗 [LinkedIn]([tu-url]) · 📂 [Portfolio QA](https://github.com/Ivess21/QA-Portfolio)



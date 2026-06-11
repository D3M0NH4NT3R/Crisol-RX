# Crisol-RX

**Gestor portable de vulnerabilidades para pentesters** — por [D3M0NH4NT3R](https://github.com/D3M0NH4NT3R)

🌐 **Web del proyecto:** https://d3m0nh4nt3r.github.io/crisol-rx/

⤓ **Descarga:** [última versión](https://github.com/D3M0NH4NT3R/crisol-rx/releases/latest) (Windows · Linux · macOS)

## ¿Qué es?

Una herramienta para gestionar hallazgos de pentesting sin fricción: binario único en Go, sin instalación, sin dependencias y 100% portable — la base de datos viaja junto al ejecutable.

- 🗂️ Workspaces por cliente/engagement, organizables en carpetas con color
- 🐛 Vulnerabilidades con ID propio, severidad, CVSS, CWE, estado, impacto y remediación
- 📸 Pruebas de concepto con imagen y descripción por captura
- 📊 Panel global con gráficos, filtros y agrupación por activo
- 🔄 Ciclo de retest: el cliente marca remediada → solo el autor confirma resuelta
- 📄 Informes HTML autocontenidos con tabla resumen y gráfica
- 👥 Tres roles: Admin, Pentester y Cliente, con permisos por workspace
- ⧉ Duplicar vulnerabilidades entre proyectos
- 🛡️ Seguridad: bcrypt, sesiones con token hasheado, anti DNS-rebinding, rate-limit, CSP
- 🧳 Export/import de workspaces (con PoC incluidas) entre instalaciones
- 🌗 Interfaz moderna con modo claro/oscuro

## Uso rápido

1. Descarga el binario de tu sistema desde [Releases](https://github.com/D3M0NH4NT3R/crisol-rx/releases/latest)
2. Ejecútalo (`chmod +x crisol-*` en macOS/Linux) — se abre en `http://127.0.0.1:8723`
3. Entra como `admin` con la contraseña que muestra la consola en el primer arranque

La configuración (`crisol.json`, junto al binario) permite exponerlo en tu LAN, poner el nombre de tu empresa junto al logo y más.

## Licencia

Software propietario © 2026 D3M0NH4NT3R. Uso permitido para fines éticos y autorizados de seguridad ofensiva. Queda prohibida la eliminación del crédito del autor y la redistribución modificada.

# 🛡️ ISO 27001 Incident Management Report: SQL Injection

Este proyecto documenta la detección, análisis y explotación de una vulnerabilidad de **SQL Injection** en una aplicación web (DVWA), bajo el marco de la normativa **ISO 27001** y el cumplimiento del **RGPD**.

## 🌐 Disponibilidad de Idiomas | Languages | Langues
Este informe técnico ha sido redactado en múltiples idiomas para facilitar su revisión en entornos internacionales:

- [🇪🇸 **Español** (Original)](./incident-report_es.pdf)
- [🇬🇧 **English**](./incident-report_en.pdf)
- [🇫🇷 **Français**](./incident-report_fr.pdf)

---

## 📝 Resumen del Incidente
El reporte detalla el descubrimiento de una validación insuficiente de entradas en el módulo de ID de usuario, permitiendo la inyección de comandos SQL. Se analiza no solo la ejecución técnica del ataque, sino también el **incumplimiento de controles de seguridad** y las **implicaciones legales** para la organización.

## ⚖️ Compliance & Marco Legal
A diferencia de un análisis puramente técnico, este informe vincula la vulnerabilidad con el marco normativo vigente:
- **ISO 27001:** Análisis de fallos en el control de acceso y seguridad en el desarrollo de software.
- **RGPD / LOPDGDD:** Identificación de brechas de seguridad que afectan a los Artículos 5, 25, 32 y 33 (Confidencialidad e Integridad de los datos).

## 🚀 Puntos Clave del Análisis
- **Resolución de Conflictos Técnicos:** Configuración de permisos de DB y ajustes en `config.inc.php`.
- **Proceso de Explotación:** Demostración de acceso no autorizado a información sensible mediante cadenas de inyección manual.
- **Plan de Remediación:** Propuesta de implementación de *Prepared Statements*, manejo seguro de errores y principio de mínimo privilegio (evitando el uso de `root`).

## 🛠️ Tecnologías Utilizadas
- **Entorno:** Kali Linux / Apache / MySQL.
- **Plataforma:** Damn Vulnerable Web Application (DVWA).
- **Metodología:** Gestión de incidentes basada en estándares ISO.


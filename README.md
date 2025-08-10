# 🛡️ Guía Operativa Ética de Inteligencia Cibernética

Este repositorio proporciona una metodología integral para la **recolección, análisis y difusión de información de inteligencia** de forma ética y legal, siguiendo el **Ciclo de Inteligencia** y estándares internacionales como **NIST**, **MITRE ATT&CK** y el **Código de Admiralty**.

---

## 🎯 Objetivo
Dotar a **analistas de inteligencia**, **equipos SOC/CERT**, y **unidades de investigación** de un marco metodológico estandarizado para ejecutar operaciones de inteligencia de manera **eficaz, legal y trazable**.

---

## 📜 Principios Éticos
- **Cumplimiento Legal**: Respetar leyes nacionales e internacionales.
- **Protección de la Privacidad**: No recolectar datos privados sin autorización o mandato judicial.
- **Uso Responsable de Fuentes**: Trabajar únicamente con **fuentes abiertas (OSINT)** o datos autorizados.
- **Trazabilidad Total**: Mantener un registro completo de fuentes, acciones y resultados.
- **Verificación y Contraste**: Validar toda la información antes de su difusión.
- **Proporcionalidad**: Recopilar solo la información necesaria para el objetivo definido.

---

## 🔄 Estructura de la Guía

1. **Fundamentos**
   - Definición del ciclo de inteligencia.
   - Conceptos clave: OSINT, SIGINT, HUMINT, CYBINT.
   - Marcos de referencia: [MITRE ATT&CK](https://attack.mitre.org/), [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework).

2. **Metodología**
   - **Dirección**: Definir requisitos de inteligencia (PIRs).
   - **Obtención**: Recopilar datos mediante técnicas pasivas y activas.
   - **Elaboración**: Correlacionar, validar y extraer conclusiones.
   - **Difusión**: Presentar productos de inteligencia adaptados al receptor.
   - **Evaluación**: Retroalimentar el ciclo para mejorar futuras operaciones.

3. **Herramientas y Recursos**
   ### Recolección Pasiva (No interactúa con el objetivo)
   - [ipinfo.io](https://ipinfo.io/) – Información de IP, ASN, geolocalización.
   - [Shodan](https://www.shodan.io/) – Escaneo y mapeo de dispositivos conectados.
   - [Censys](https://search.censys.io/) – Análisis de infraestructura expuesta.
   - [URLScan.io](https://urlscan.io/) – Análisis de sitios web y dominios.
   - [AbuseIPDB](https://www.abuseipdb.com/) – Verificación de reputación IP.
   - [VirusTotal](https://www.virustotal.com/) – Análisis de archivos y URLs.
   - [HaveIBeenPwned](https://haveibeenpwned.com/) – Verificación de filtraciones de credenciales.

   ### Recolección Activa (Interacción controlada con el objetivo)
   - **Nmap** – Escaneo de puertos y servicios. [Guía](https://nmap.org/book/man.html)
   - **Amass** – Enumeración de subdominios. [GitHub](https://github.com/owasp-amass/amass)
   - **WhatWeb** – Detección de tecnologías web.
   - **theHarvester** – Recolección de correos, dominios y hosts públicos.
   - **Metasploit Framework** – Pruebas de intrusión controladas. [Documentación](https://docs.rapid7.com/metasploit/)

4. **Validación de Información**
   - Aplicar el [Admiralty Code](https://en.wikipedia.org/wiki/Admiralty_code) para evaluar fiabilidad y credibilidad.
   - Correlacionar múltiples fuentes antes de emitir conclusiones.

5. **Ejemplos Prácticos**
   - **Caso 1 – Investigación de IP sospechosa**: Uso de ipinfo + Shodan para identificar servicios y posibles vectores de ataque.
   - **Caso 2 – Monitoreo de dominio malicioso**: URLScan + VirusTotal + MITRE para mapear técnicas y TTPs.
   - **Caso 3 – Evaluación de infraestructura expuesta**: Censys + Nmap para generar informe ejecutivo con riesgos.

---

## 🗂️ Procedimiento de Uso
1. Revisar **Fundamentos** para entender el marco ético y metodológico.
2. Definir claramente los **PIRs** (Preguntas de Inteligencia Prioritarias).
3. Seleccionar las **herramientas y fuentes** adecuadas (pasivas o activas).
4. **Registrar y documentar** cada hallazgo con fecha, fuente y método.
5. Validar datos con **múltiples fuentes** y el **Admiralty Code**.
6. Generar un **producto de inteligencia** claro (informe, dashboard, alerta).
7. Retroalimentar el proceso para mejorar operaciones futuras.

---

## 📌 Referencias y Estándares Clave
- [MITRE ATT&CK](https://attack.mitre.org/) – Clasificación de tácticas, técnicas y procedimientos (TTPs).
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework) – Marco de gestión de riesgos de ciberseguridad.
- [ISO/IEC 27001](https://www.iso.org/isoiec-27001-information-security.html) – Gestión de seguridad de la información.
- [Admiralty Code](https://en.wikipedia.org/wiki/Admiralty_code) – Evaluación de la fiabilidad de fuentes.
- [OSINT Framework](https://osintframework.com/) – Directorio de herramientas OSINT.

---

## 🚨 Aviso
> Toda actividad debe ser realizada **en entornos autorizados** y respetando la legislación vigente. El uso indebido de estas técnicas puede derivar en responsabilidades legales.

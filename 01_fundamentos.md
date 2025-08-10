# 📊 Definiciones Básicas de Inteligencia con Ejemplos Prácticos

## 🔍 ¿Qué es Inteligencia?
La **inteligencia** es un **proceso continuo y cíclico** que transforma datos sin procesar en **información procesada, contextualizada y útil** para respaldar la **toma de decisiones**.

**Fases clave del ciclo:**
1. **Dirección:** Definición de objetivos y requerimientos prioritarios de inteligencia (PIRs).  
   - *Ejemplo:* El CISO de una empresa financiera solicita conocer si hay indicios de una campaña de phishing dirigida a sus clientes en la última semana.  
2. **Obtención:** Recolección de datos desde fuentes internas, externas y abiertas (OSINT, HUMINT, SIGINT, etc.).  
   - *Ejemplo:* Uso de Shodan para detectar servidores expuestos, o búsqueda en foros clandestinos para identificar filtraciones de credenciales.  
3. **Elaboración:** Procesamiento, validación, correlación y análisis de datos.  
   - *Ejemplo:* Comparar las direcciones IP encontradas con bases de datos de amenazas como AlienVault OTX para confirmar si están asociadas a campañas activas.  
4. **Difusión:** Presentación de inteligencia procesada en formatos accionables para decisores.  
   - *Ejemplo:* Crear un informe ejecutivo con mapas de amenazas y recomendaciones para bloquear indicadores en el firewall.

---

## 🧩 Tipos de Inteligencia (según uso) con Ejemplos
- **Básica:** Información de carácter histórico y descriptivo.  
  - *Ejemplo:* Catálogo de todos los grupos APT activos contra el sector financiero en los últimos 5 años.  
- **Actual o Corriente:** Describe la situación presente.  
  - *Ejemplo:* Monitoreo de un ataque DDoS en curso contra los servidores web de la empresa.  
- **Estimativa:** Proyección futura de amenazas.  
  - *Ejemplo:* Evaluar que, debido a elecciones nacionales, aumentarán los intentos de spear phishing contra autoridades.  
- **Targeting:** Focalizada en un objetivo o activo concreto.  
  - *Ejemplo:* Identificar la infraestructura C2 de un ransomware específico que afecta a hospitales.  
- **Alerta:** Aviso urgente ante amenaza latente.  
  - *Ejemplo:* Notificación de CISA sobre vulnerabilidad crítica en un firewall utilizado por la organización.

---

## 🛡️ Niveles de Inteligencia con Ejemplos
- **Táctico:** Indicadores técnicos (IoC/IoA).  
  - *Ejemplo:* Lista de hashes SHA256 de malware detectados en la red la última semana.  
- **Operacional:** Campañas y actores.  
  - *Ejemplo:* Informe sobre la campaña “APT28” detallando sus TTPs y objetivos en América Latina.  
- **Estratégico:** Impacto en negocio y decisiones de alto nivel.  
  - *Ejemplo:* Estudio de cómo un ataque de ransomware podría interrumpir la cadena de suministro y generar pérdidas estimadas de 2M USD.

---

## 👥 Roles en el Ciclo de Inteligencia con Ejemplos
- **Dirección:** Establece la misión.  
  - *Ejemplo:* Un jefe de operaciones ordena monitorear redes sociales para detectar campañas de desinformación contra la marca.  
- **Obtención:** Recolección de datos.  
  - *Ejemplo:* Uso de APIs de Threat Intelligence para extraer datos en tiempo real de IoCs.  
- **Elaboración:** Análisis y correlación.  
  - *Ejemplo:* Vincular un dominio sospechoso detectado en logs con un actor identificado por MITRE ATT&CK.  
- **Difusión:** Comunicación.  
  - *Ejemplo:* Enviar un dashboard en tiempo real con mapas y métricas a la sala de control de seguridad (SOC).

---

## ✅ Buenas Prácticas
- Mantener trazabilidad de fuentes y métodos (*cadena de custodia digital*).  
- Actualizar inteligencia al menos diariamente en casos críticos.  
- Usar estándares de intercambio como **STIX/TAXII** y MITRE ATT&CK para categorizar TTPs.  
- Implementar alertas automáticas conectadas a SIEM/SOAR para respuesta rápida.  

---

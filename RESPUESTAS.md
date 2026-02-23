# RESPUESTAS — Reflexión y Resumen (Plantilla genérica)

> **Actividad / ID:**  2.a..e
> **Unidad / Tema:**  Unidad 2: Análisis de incidentes
> **Alumno/a:**  Adrián Sánchez Torrejón
> **Fecha:**  23/02/2026

---

## 1) Reflexión crítica (preguntas)
Responde con **lenguaje técnico** y **argumentos** (no solo opiniones). Si procede, usa ejemplos, riesgos y decisiones justificadas.

### 1.1) ¿Qué te han parecido los temas tratados en la unidad?
- Me han parecido bastante interesantes, OSINT es una herramienta que la gente debería conocer sus capacidades, ya que muchas veces no es consciente de cuantos datos suyos son públicos en internet. 

### 1.2) ¿Qué ha sido más útil para tu futuro puesto de trabajo? ¿Por qué?
- Creo que lo más útil han sido las presentaciones, esto se debe a que te puedes formar de temas específicos por tu propia cuenta, pero es mucho más difícil la experiencia que te da todas las presentaciones que hemos hecho con la retroalimentación activa que hemos recibido.

### 1.3) ¿Qué partes ya conocías y cuáles han sido nuevas para ti?
- La verdad es que desconocía en general todo lo relacionado con esta asignatura, por lo que en esta es una de las que más aprendo al ser un terreno que tenía menos explorado.

### 1.4) ¿Qué concepto/idea te ha llamado más la atención y por qué?
- La taxonomía en general, es interesante es esfuerzo que se realiza para clasificar los incidentes de manera que alguien con menos conocimiento de informática pueda entender la situación y dar información a veces clave para el incidente.

### 1.5) ¿Qué parte recortarías o simplificarías si hubiera menos tiempo? Justifica.
- La implementación del SIEM, aunque podría decirse que fue útil siento que este tema debería haberse dado en bastionado, ya que se acerca más a su asignatura este tema.

### 1.6) ¿Qué tema has echado en falta o ampliarías? Justifica.
- En vez de hacernos implementar un SIEM hubiera preferido que tener una ya montada y ver más casos de uso para este y sus implementaciones. Me parece que este es de cierta manera el punto más importante del SIEM ya que en este se daba su reglamento a la hora de vigilar el tráfico, pero solo hemos podido ver su uso superficial.

### 1.7) ¿Qué aplicarías “mañana” en un entorno real con recursos limitados?
- Dependerá sobre todo del tipo de empleo que consiga, si estuviera más relacionado con la formación de los trabajadores les enseñaría las habilidades del OSINT, pero si estuviera más centrado en el bastionado de una red intentaría instalar un SIEM, aunque seguramente uno más fácil de instalar.

### 1.8) ¿Qué duda, riesgo o punto crítico te queda abierto tras la unidad?
- Por lo comentado anteriormente el SIEM queda para mí como una unidad que hemos visto solo teóricamente, pero no hemos hecho ningún ejercicio práctico que me parezca realmente útil para la práctica.


## 2) Resumen esquematizado (obligatorio)

### 2.1) Mapa/índice de la unidad (visión global)
- Identificación y Clasificación: Taxonomía y tipos de incidentes (2.1.1).

- Detección y Monitorización: Ecosistema del SOC, SIEM y su evolución (2.2.1 - 2.2.4).

- Investigación Avanzada: Uso de fuentes abiertas (OSINT) (2.3.1).

- Gestión Operativa: Documentación, seguimiento y lecciones aprendidas (2.4.1).

- Comunicación: Elaboración de informes técnicos de seguridad (2.5).

### 2.2) Conceptos clave (lista breve)
- Taxonomía: Clasificación normalizada de incidentes para facilitar la comunicación y el análisis estadístico.

- SIEM (Security Information and Event Management): Plataforma de centralización de logs y correlación de eventos en tiempo real.

- SOAR (Security Orchestration, Automation and Response): Capa tecnológica que permite automatizar respuestas mediante playbooks.

- Caso de Uso: Escenario específico de detección definido por fuentes, lógica y respuesta.

- OSINT (Open Source Intelligence): Inteligencia derivada de la recopilación y análisis de datos públicos.

### 2.3) Procesos / procedimientos (pasos o checklist)
- Ciclo de Investigación OSINT

| Fase | Acción Técnica | Herramientas / Técnicas |
| --- | --- | --- |
| **1. OpSec** | Anonimización y creación de identidades sintéticas. | **Sock Puppets**, VPN, Navegadores aislados. |
| **2. Recolección** | Obtención de datos públicos, históricos y metadatos. | **Google Dorks**, Wayback Machine, FOCA. |
| **3. Infraestructura** | Mapeo de activos, servicios y puertos expuestos. | **Shodan**, Censys, WHOIS History. |
| **4. Enriquecimiento** | Contraste de IoCs y validación de reputación. | **VirusTotal**, AlienVault, AbuseIPDB. |
| **5. Correlación** | Vinculación de nodos y visualización de la red. | **Maltego**, SpiderFoot, Análisis de grafos. |
| **6. Resolución** | Atribución (si aplica) y generación de informe. | Línea temporal, Capturas con hash (SHA-256). |

### 2.4) Herramientas / técnicas (si aplica)
- Detección: SIEM (Elastic, Splunk), IDS/IPS, EDR.

- Investigación OSINT: Google Dorks, Whois, Shodan, Maltego, Wayback Machine.

- Gestión de Incidentes: RTIR (Request Tracker for Incident Response), TheHive.

- Análisis de Amenazas: MISP (Malware Information Sharing Platform), MITRE ATT&CK, VirusTotal.
### 2.5) Buenas prácticas y errores típicos
- Buena Práctica: Implementación gradual del SIEM (Fase piloto -> Escalado -> Mejora).

- Buena Práctica: Mantener una línea temporal (timeline) estricta durante el incidente.

- Error Típico: Intentar automatizar procesos (SOAR) que no están previamente documentados o maduros.

- Error Típico: "Fatiga de alertas" por no ajustar correctamente los umbrales de los casos de uso.

### 2.6) Glosario mínimo (términos y definiciones cortas)
- 


## 3) (Opcional) Evidencias y recursos usados
Enlaza aquí evidencias (capturas, logs, configuraciones, salidas de comandos, etc.) si forman parte de tu trabajo.

### Evidencia 1
- Archivo: `evidencias/01_...`
- Qué demuestra:
- Qué he aprendido:

### Evidencia 2
- Archivo: `evidencias/02_...`
- Qué demuestra:
- Qué he aprendido:


## 4) Conclusión (cierre)
- Esta ha sido una Unidad con temas bastante importantes, pero siento que en la parte práctica nos hemos quedado detrás haciendo ejercicios que no nos beneficiaban tanto como los de la Unidad anterior, espero que si sobra tiempo al final del curso podamos volver a revisar los puntos que hayamos mencionado la clase en general como más laxos para poder terminar lo más preparado posible.

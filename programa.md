# Programa autodidacta de IA con Claude

Versión 1.0 · 12 de noviembre de 2026 · Luis Alberto Flores

## Veredicto: es factible, con tres límites

Con Claude como tutor se puede cubrir, como estimación, cerca del 55% del Máster de IA de BIG school completo y cerca del 77% de los bloques que sirven a mi cargo. Además, 5 de las 20 semanas son contenido que el máster no tiene: fundamentos, gobierno y regulación chilena, evaluación de sistemas de IA y un proyecto final defendible. El resultado es un diplomado aplicado, no un magíster ni un equivalente del máster.

Lo que **sí** se replica:

- La explicación de cada tema, adaptada a mi nivel y a casos de banca.
- La práctica guiada, con entregables revisados con rúbrica.
- Los exámenes por bloque y un examen final.
- La búsqueda de novedades: el tutor busca en la web, porque estas herramientas cambian cada mes.

Lo que **no** se replica:

- **El título.** No hay certificado. Para el CV se suman cursos gratuitos con certificado (academia de Anthropic, Microsoft Learn).
- **La práctica en herramientas de terceros.** n8n, Make, Lovable o Copilot Studio se usan con cuentas propias.
- **La comunidad y el networking.** Lo más cercano son comunidades abiertas de n8n o de Claude.

El riesgo real no es el contenido, es la constancia. Por eso hay ritmo semanal, bitácora y recordatorio programado.

### Cobertura estimada por bloque

Estimación propia, no una medición: pondera cada bloque del máster por sus lecciones publicadas (432 en total) y le asigna el nivel de cobertura que logra esta malla. Rango razonable: 50% a 60% del total, y 70% a 85% sin audiovisual ni marketing.

| Bloque de BIG school | Lecciones | Cobertura estimada |
| --- | --- | --- |
| Fundamentos y asistentes | 57 | 85% |
| Ofimática con IA | 30 | 80% |
| Agentes | 81 | 80% |
| Automatizaciones (Make, Botpress, n8n) | 61 | 60% |
| IA audiovisual | 86 | 5% |
| Legal | 5 | 100% |
| Implementación en empresa (incluye Power Automate) | 34 | 85% |
| Marketing con IA | 63 | 25% |
| Cierre | 15 | 60% |

### Antes de partir

- [ ] Confirmar la política interna del banco sobre uso de IA con herramientas personales
- [ ] Pedir a TI un entorno de prueba de Copilot Studio y saber qué conectores de Power Automate quedarán habilitados
- [ ] Activar la memoria en Claude y en ChatGPT

## Malla curricular: 20 semanas, unas 5 horas por semana

Unas 100 horas en total. Agentes y automatización son el núcleo y ocupan 8 de las 20 semanas. n8n tiene dos semanas y Power Automate otras dos: una con Microsoft 365 y otra integrada con Copilot Studio. Audiovisual queda como módulo opcional fuera de la carga.

| Sem. | Bloque | Contenido | Entregable |
| --- | --- | --- | --- |
| 1 | Fundamentos I | Diagnóstico. Cómo funciona un LLM. Asistentes comparados y prompting avanzado | Mapa de brechas y resultados de aprendizaje por bloque |
| 2 | Fundamentos II | Machine learning y datos para gestores: entrenamiento e inferencia, sobreajuste, métricas, sesgo, cuándo no usar IA generativa | Tres casos del banco: qué técnica corresponde a cada uno y por qué |
| 3 | Gobierno y seguridad | Datos personales, proyecto de ley de IA, normas CMF, política interna, clasificación de datos, inyección de prompts | Checklist de uso responsable, que se aplica a todo entregable posterior |
| 4 | Ofimática con IA | Copilot en Microsoft 365 y Google Workspace | Tres flujos documentados. Examen de bloque 1 |
| 5 | Agentes I | Herramientas, MCP, memoria y planificación. ChatGPT, Genspark y Perplexity comparados | Comparación de agentes en una misma tarea |
| 6 | Agentes II | Claude con carpetas y conectores, Claude Code, diseño de skills | Skill "tutor-ia" y auditoría de un skill propio |
| 7 | Agentes III | Agentes de programación en la práctica: Codex y Antigravity frente a Claude Code | La misma tarea resuelta en dos herramientas, con comparación |
| 8 | Agentes IV | Agentes autónomos con OpenClaw. Flujos con varios agentes, permisos y límites | Flujo con agente autónomo en el computador personal, con revisión de riesgos |
| 9 | Evaluación de IA | Casos de prueba, métricas, pruebas de regresión, revisión humana | Set de 10 casos de prueba para uno de mis agentes. Examen de bloque 2 |
| 10 | Automatización I | APIs, webhooks y JSON. Make | Flujo de punta a punta en Make |
| 11 | Automatización II | n8n I: nodos, credenciales, disparadores, webhooks, manejo de errores | Flujo en n8n con datos ficticios y su revisión de riesgos |
| 12 | Automatización III | n8n II con IA: agentes, memoria, consulta a documentos. Chatbot con Botpress | Flujo de n8n con agente de IA que resume minutas ficticias |
| 13 | Automatización IV | Power Automate I con Microsoft 365: flujos con Outlook, Teams, SharePoint, Excel y Forms; aprobaciones | Flujo de aprobación o seguimiento útil para el trabajo. Tema del proyecto final elegido. Examen de bloque 3 |
| 14 | Empresa I | API de Claude con Python y RAG | Notebook RAG sobre normativa pública, con su evaluación |
| 15 | Empresa II | Copilot Studio: agentes, fuentes de conocimiento, temas | Agente prototipo en entorno de prueba |
| 16 | Empresa III | Power Automate II: acciones para el agente de Copilot Studio, gobierno de flujos. Modelos locales solo en concepto | Agente que ejecuta una acción. Avance del proyecto final. Examen de bloque 4 |
| 17 | Prototipado y marketing | Lovable o Replit. Marketing con IA: segmentación y análisis de mercado | Prototipo de una campaña evaluada con IA |
| 18 | Estrategia | Caso de negocio, costos por uso, adopción, casos reales de banca, mercado laboral | Business case de una iniciativa |
| 19 | Proyecto final I | Construcción y pruebas | Prototipo funcionando y ficha pre-FUID |
| 20 | Proyecto final II | Defensa ante una persona, examen final oral y escrito | Presentación, examen final y portafolio |

La regulación cambia seguido: el tutor verifica el día de la clase la vigencia de la Ley 21.719, el estado del proyecto de ley de IA y las normas de la CMF. Si la licencia de Microsoft 365 llega antes de la semana 13, Power Automate I se puede adelantar. Si no llega, las semanas 13, 15 y 16 se hacen con equivalentes en n8n y Claude, y la parte de Microsoft se estudia en Microsoft Learn.

## Metodología y evaluación

Cada semana sigue el mismo ciclo de unas 5 horas, en un chat llamado "Semana N – Tema". El tutor enseña y da retroalimentación, pero no pone la nota: eso lo hace un evaluador separado.

1. **Clase (1 h).** El tutor mide lo que ya sé, explica con preguntas y casos de banca, y busca en la web lo que haya cambiado.
2. **Práctica guiada (2 h).** Ejercicios paso a paso en la herramienta real. El tutor da pistas, no la solución.
3. **Entregable (1,5 h).** Lo hago yo, con evidencia de que funciona y su revisión de riesgos, y lo guardo en `portafolio/semana-NN/`.
4. **Quiz y cierre (30 min).** Seis preguntas: 3 de la semana, 2 de semanas anteriores y 1 de aplicación a un caso nuevo. El tutor entrega el bloque de bitácora.
5. **Nota.** El entregable se corrige en un chat fuera de los proyectos, con otro modelo y sin contexto, usando `tutor/prompt-evaluador.md`.

### Rúbrica de entregables (escala de 1 a 7)

| Criterio | Peso | Nota 3 | Nota 5 | Nota 7 |
| --- | --- | --- | --- | --- |
| Dominio conceptual | 30% | Repite definiciones | Explica por qué funciona y sus límites | Predice cuándo falla y propone una alternativa |
| Ejecución práctica | 30% | No funciona o no hay evidencia | Funciona en el caso base, con evidencia | Funciona en casos límite y trae sus pruebas |
| Riesgo y gobierno | 20% | No identifica datos ni riesgos | Clasifica los datos y nombra controles | Controles aplicados y verificados |
| Aplicabilidad al banco | 20% | Caso genérico | Dolor real, con beneficiario claro | Con métrica y camino de implementación |

La aplicabilidad se evalúa solo en entregables de caso; cuando no aplica, su peso se reparte entre los otros tres criterios. Sin evidencia de funcionamiento, la nota de ejecución no pasa de 4,0.

**Aprobación:** nota 5,0 en cada bloque, puesta por el evaluador externo. Bajo eso, el tutor arma un repaso de 1 hora antes de avanzar. Exámenes de bloque en las semanas 4, 9, 13 y 16, con una parte oral a libro cerrado, por voz. El examen final de la semana 20 suma la defensa del proyecto ante una persona del banco.

**Bitácora de errores del tutor:** cada error del tutor se anota, para calibrar cuánto confiar en él.

**Certificados opcionales para el CV:** cursos gratuitos de la academia de Anthropic y rutas de Microsoft Learn sobre Copilot Studio. El tutor verifica nombre y catálogo vigentes en las semanas 6 y 15.

## Proyecto final

Una solución de IA para un dolor real de la Gerencia, implementable dentro del ecosistema corporativo y presentada como ficha pre-FUID. Tres opciones, para elegir en la semana 13 y mostrar avance en la 16:

- **Agente de demanda en Copilot Studio.** Responde dudas sobre el proceso de fichas y V°B°, usando documentos internos aprobados.
- **Flujo de minutas automatizado.** Transcribe, resume y registra acuerdos de mesas de demanda con Power Automate.
- **Asistente de propuesta de valor.** RAG sobre normativa CMF pública y benchmark para un segmento, como pensionados.

Entregables: prototipo funcionando con datos ficticios, ficha pre-FUID, análisis de riesgos y datos personales, set de 10 casos de prueba y presentación de 5 láminas. Se construye en las semanas 19 y 20 y se defiende ante una persona del banco. La nota la pone el evaluador externo.

Nunca se usan datos reales de clientes en herramientas personales. Lo que toque datos del banco se prueba solo en el entorno corporativo y con autorización.

## Herramientas, cuentas y límites

Los planes y precios cambian seguido; el tutor los verifica cada semana.

| Herramienta | Semana | Cómo acceder | Ojo con |
| --- | --- | --- | --- |
| Claude | Todas | Plan actual | Activar la memoria |
| ChatGPT | Todas | Plan actual | Activar la memoria del proyecto |
| Gemini, Perplexity, Genspark | 1 y 5 | Planes gratuitos | Funciones avanzadas pueden ser de pago |
| Microsoft 365 Copilot | 4 | Cuenta corporativa, cuando llegue la licencia | Confirmar con TI qué incluye |
| Codex, Antigravity y OpenClaw | 7 y 8 | Cuentas personales, en el computador personal | No instalarlos en el equipo del banco ni darles acceso a cuentas reales |
| Make | 10 | Plan gratuito | No conectar cuentas ni datos del banco |
| n8n y Botpress | 11 y 12 | n8n en prueba en la nube o instalado en el computador personal; Botpress con plan gratuito | No conectar cuentas ni datos del banco |
| Power Automate | 13 y 16 | Licencia corporativa de Microsoft 365 | Confirmar con TI qué conectores quedan habilitados |
| API de Claude | 14 | Créditos de API del curso de LLM | Costo por uso: bajo con Haiku |
| Copilot Studio | 15 y 16 | Licencia corporativa. No admite cuentas personales | Pedir entorno de prueba antes de la semana 1 |
| Lovable o Replit | 17 | Planes gratuitos | Límite de créditos diarios |
| Magnific | Opcional | Conectado a Claude | Fuera de la carga de 5 horas |

**Referencia:** [Plan de estudios Máster IA – BIG school](https://thebigschool.com/wp-content/uploads/2025/08/Plan_Estudios_Master_IA_BIG_school.pdf), revisado el 12 de noviembre de 2026.

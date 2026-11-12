# Prompt del evaluador externo

Usar en un **chat nuevo, fuera de los proyectos**, en la herramienta que no se usó como tutor esa semana. Pegar el prompt, la rúbrica y la consigna, y adjuntar el entregable con su evidencia.

```text
Actúa como evaluador externo de un diplomado de IA aplicada a banca. No conoces al estudiante ni lo que se le enseñó. Evalúa el entregable adjunto solo con la rúbrica que pego abajo. Pon nota de 1 a 7 por criterio y cita la evidencia que la respalda. Señala qué afirmaciones no puedes verificar. Termina con las 3 observaciones que haría un comité exigente. No suavices el juicio.

Rúbrica (escala de 1 a 7):
- Dominio conceptual (30%). Nota 3: repite definiciones. Nota 5: explica por qué funciona y sus límites. Nota 7: predice cuándo falla y propone una alternativa.
- Ejecución práctica (30%). Nota 3: no funciona o no hay evidencia. Nota 5: funciona en el caso base, con evidencia. Nota 7: funciona en casos límite y trae sus pruebas.
- Riesgo y gobierno (20%). Nota 3: no identifica datos ni riesgos. Nota 5: clasifica los datos y nombra controles. Nota 7: controles aplicados y verificados.
- Aplicabilidad al banco (20%). Nota 3: caso genérico. Nota 5: dolor real, con beneficiario claro. Nota 7: con métrica y camino de implementación.

Reglas: la aplicabilidad se evalúa solo en entregables de caso; si no aplica, su peso se reparte entre los otros tres criterios. Sin evidencia de funcionamiento, la ejecución no pasa de 4,0.

Consigna del entregable:
[Pegar aquí la consigna de la semana, copiada de programa.md]
```

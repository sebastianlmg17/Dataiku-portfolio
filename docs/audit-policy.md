# Auditoría tras CADA PASO

Cada acción concreta constituye un paso: lectura que sustenta una decisión, modificación, verificación, commit, publicación o cambio de metadatos. Registrar su auditoría antes de continuar al paso dependiente. Auditar también el cierre de cada etapa y realizar auditoría final del conjunto.

Cada registro debe incluir fecha, autor, alcance y autorización, estado previo, archivos o referencias afectados, evidencia reproducible (comprobación, salida no sensible o SHA), resultado, observaciones, pendientes y siguiente acción permitida. No publicar secretos ni datos de cuenta como evidencia.

Resultados permitidos:
- **aprobado**: controles del alcance pasan y evidencia suficiente.
- **aprobado con observaciones**: controles pasan con limitaciones explícitas que no impiden el paso autorizado; indicar pendientes.
- **bloqueado**: falla un control necesario, falta autorización o evidencia imprescindible; detener el trabajo dependiente y registrar qué lo desbloquea.

El dictamen del auditor no equivale a autorización humana. Pedir al usuario cualquier decisión nueva relevante. No avanzar una etapa ni activar operativa por un dictamen documental. Conservar registros anteriores; añadir correcciones identificadas si se detecta un error.

Plantilla:
```
## Paso N — Acción / fecha
Autor y alcance:
Autorización:
Estado previo:
Cambios / referencias:
Pruebas y evidencia:
Resultado: aprobado / aprobado con observaciones / bloqueado
Observaciones y pendientes:
Siguiente acción permitida:
```

# Protección de credenciales y datos sensibles

El repositorio es público. Publicar únicamente documentación y artefactos revisados para difusión pública. Credenciales, tokens, claves, cookies, saldos, posiciones, identificadores de cuenta, extractos y exportaciones del broker deben permanecer fuera del repositorio, en almacenamiento privado con acceso limitado. Usar variables de entorno o un gestor de secretos; los ejemplos contienen solo valores ficticios.

.gitignore es prevención parcial: no protege archivos ya rastreados, el historial ni inclusiones forzadas. Antes de cada commit y push revisar archivos rastreados, diff y contenido por secretos y datos personales. Revisar también salidas de notebooks, logs, capturas, metadatos y modelos. Datos de mercado quedan privados por defecto hasta comprobar licencia y autorización de publicación. No usar git add -f para eludir estas reglas.

Ante exposición: detener la publicación, revocar o rotar la credencial con el propietario, documentar el incidente sin reproducir el secreto y pedir decisión sobre la remediación. No borrar ni reescribir historial por iniciativa propia. La conservación histórica requerida no implica que sus contenidos antiguos estén exhaustivamente libres de información sensible.

El escaneo de patrones tiene falsos negativos y no constituye certificación. Una revisión exhaustiva del historial completo queda pendiente; cualquier hallazgo requiere tratamiento explícito.

<p align="center">
  <img src="assets/stream-assistant-logo.png" alt="Logo de Stream Assistant" width="156">
</p>

<h1 align="center">Stream Assistant</h1>
<p align="center"><strong>Tu centro de control para directos de Twitch.</strong><br>Chat, alertas, texto a voz local y controles de OBS para Windows.</p>
<p align="center"><a href="https://github.com/kanheltw/Stream-Assistant-Releases/releases/tag/v0.5.8"><strong>Descargar Beta 1.8</strong></a> | <a href="https://github.com/kanheltw/Stream-Assistant-feedback/issues/new">Reportar un problema o proponer mejoras</a></p>

> **Beta pública de prueba.** Algunas funciones dependen de permisos de Twitch, de OBS y de la configuración local.

## Instalación

1. Descarga [Stream-Assistant-v0.5.0-beta.1.8-Windows.zip](https://github.com/kanheltw/Stream-Assistant-Releases/releases/download/v0.5.8/Stream-Assistant-v0.5.0-beta.1.8-Windows.zip).
2. Extrae el ZIP completo. Se creará la carpeta `Stream Assistant Beta 1.8`.
3. Abre `Stream Assistant Beta 1.8/Stream Assistant/Stream Assistant.exe`.

En la carpeta exterior encontrarás `MANUAL-DE-USO.txt` en español, inglés y francés, y la carpeta `Licencias`. No necesitas instalar Python para abrir la aplicación ni para usar las voces de Windows.

## Actualizaciones

En **Configuración → Actualizaciones** puedes activar la actualización automática. La app comprobará las versiones al abrirse, descargará la nueva versión y la aplicará al cerrarse. Si prefieres decidir cada vez, desactívala y usa **Buscar actualización ahora**. También puedes descargar el ZIP e instalar la versión manualmente.

La Beta 1.8 incluye el archivo `Stream.Assistant.exe` que necesita el actualizador de las betas anteriores. La app verifica su huella SHA-256 publicada por GitHub. Si Windows bloquea la ejecución, consulta el aviso siguiente.

## Funciones

- Chat de Twitch, actividad, alertas y fuentes Navegador independientes para OBS.
- Paneles personalizables, **Momentos** y resumen del directo.
- Controles de OBS, reglas por escena y comprobaciones antes de emitir.
- Cola de alertas, recompensas creadas en Stream Assistant y control LAN opcional.
- Texto a voz local con voces de Windows; Piper y sus modelos son opcionales y se instalan por separado.
- Interfaz en español, inglés y francés.

## Aviso de Windows

Stream Assistant todavía no está firmado. Smart App Control puede bloquear un programa nuevo o poco conocido. Si aparece ese bloqueo, no hay una excepción sencilla para ese archivo; consulta la información de Microsoft antes de cambiar la protección de tu equipo. La distribución actual sigue en fase beta.

## Licencia y privacidad

Stream Assistant se distribuye bajo una [licencia de uso propietaria y gratuita](LICENCIA-DE-USO.txt); el código fuente de esta versión no es público. El ZIP incluye la licencia y los avisos de terceros. Cada componente conserva sus propias condiciones.

El texto para TTS se procesa localmente. Los ajustes y registros se guardan en `%LOCALAPPDATA%\Stream Assistant`. No publiques tokens, contraseñas, enlaces LAN privados ni datos personales en reportes.

## Soporte

Usa [Stream Assistant Feedback](https://github.com/kanheltw/Stream-Assistant-feedback/issues/new) para reportar errores o proponer mejoras. Indica la versión, los pasos para reproducir el problema y el resultado esperado.

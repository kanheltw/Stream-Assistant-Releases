<p align="center">
  <img src="assets/stream-assistant-logo.png" alt="Logo de Stream Assistant" width="156">
</p>

<h1 align="center">Stream Assistant</h1>
<p align="center"><strong>Tu centro de control para directos de Twitch.</strong><br>Chat, alertas, texto a voz local y controles de OBS para Windows.</p>
<p align="center"><a href="https://github.com/kanheltw/Stream-Assistant-Releases/releases/tag/v0.5.0-beta.2"><strong>Descargar Beta 2</strong></a> | <a href="https://github.com/kanheltw/Stream-Assistant-feedback/issues/new">Reportar un problema o enviar sugerencias</a></p>

> **Beta pública de prueba.** Algunas funciones dependen de los permisos de Twitch, OBS y las capacidades de voz de Windows. Lee las limitaciones antes de instalar.

## Aviso de Windows Smart App Control

Windows puede bloquear esta beta con Smart App Control porque Stream Assistant es un programa nuevo y todavía no es conocido por Windows. Estoy trabajando para resolverlo y más adelante quiero firmar la aplicación. Si Windows la bloquea, puedes decidir desactivar Smart App Control por tu cuenta para intentar abrirla; es opcional, reduce la protección del equipo y puede ser difícil de revertir. Hazlo solo si confías en el archivo y entiendes el riesgo.

## Descarga

1. Abre la [página de la Beta 2](https://github.com/kanheltw/Stream-Assistant-Releases/releases/tag/v0.5.0-beta.2).
2. Descarga `Stream-Assistant-v0.5.0-beta.2-Windows.zip` y extrae su contenido.
3. Ejecuta `Stream Assistant.exe` en Windows 10/11.

No hace falta instalar Python para ejecutar la aplicación o usar voces de Windows.

## Novedades de Beta 2

- Corregido el icono de Stream Assistant en la ventana y la barra de tareas de Windows.

## Funciones

- Chat en directo y alertas de Twitch en paneles personalizables.
- Texto a voz local: voces compatibles de Windows o motores Piper instalados por separado.
- Integración opcional con OBS mediante WebSocket.
- Interfaz en español, inglés y francés.

## Voces

**Voces de Windows:** en el panel TTS, elige una voz disponible. Usa **Instalar más voces de Microsoft…** para abrir la configuración de Windows; después de instalar una, pulsa **Actualizar lista de voces**. La disponibilidad depende de Windows y de las voces que exponga a aplicaciones de escritorio.

**Piper (opcional):** la aplicación no incluye Piper ni sus modelos. El README incluido en el ZIP explica cómo instalar Piper y añadir modelos. Revisa las licencias y requisitos de cada modelo antes de usarlo o redistribuirlo.

## Licencia y privacidad

Stream Assistant se distribuye bajo una **licencia de uso propietaria y gratuita**; no es software de código abierto. Lee la [licencia de uso](LICENCIA-DE-USO.txt) antes de descargar. El ZIP incluye también las licencias y avisos de terceros, disponibles como [archivo de licencias](https://github.com/kanheltw/Stream-Assistant-Releases/releases/download/v0.5.0-beta.2/THIRD-PARTY-LICENSES.zip) y [avisos](THIRD-PARTY-NOTICES.txt). Cada componente conserva sus propias condiciones.

El texto para TTS se procesa localmente. Consulta el README incluido para información de Twitch, credenciales, registros y configuración de OBS. No publiques tokens, contraseñas ni enlaces privados en reportes.

## Soporte

Usa [Stream Assistant Feedback](https://github.com/kanheltw/Stream-Assistant-feedback/issues/new) para reportar errores o proponer mejoras. Indica la versión y los pasos para reproducir el problema; elimina antes cualquier dato privado.

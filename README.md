# Plan de vida — primera versión Android

Proyecto Android nativo en Kotlin + Jetpack Compose.

## Obtener el APK sin instalar Android Studio
Este proyecto incluye un flujo de GitHub Actions para compilar el APK en la nube:
1. Crea un repositorio en GitHub y sube el contenido de esta carpeta.
2. Abre la pestaña **Actions** del repositorio.
3. Ejecuta **Construir APK de Plan de vida** (o espera a que termine el flujo tras subir a `main`).
4. Cuando termine, abre la ejecución y descarga el artefacto **Plan-de-vida-APK**.
5. Descomprime el artefacto y abre `app-debug.apk` en tu Android. Es posible que Android te pida autorizar la instalación desde esa fuente.

## Compilar localmente
También puedes abrir la carpeta en Android Studio, sincronizar Gradle y ejecutar `:app:assembleDebug`.

## Qué incluye
- Normas diarias, semanales y mensuales con las abreviaturas de la planilla.
- Puntuación de calidad de 0 a 10 por norma.
- Posibilidad de dejar una norma sin evaluar.
- Navegación entre fechas para las revisiones diarias.
- Media de la revisión actual.
- Guardado local en el dispositivo, sin cuenta ni notificaciones.

## Estado
Es un proyecto fuente inicial. El APK todavía debe compilarse mediante Android Studio o el flujo de GitHub Actions. El historial ampliado y la cuadrícula mensual completa quedan como siguientes mejoras.

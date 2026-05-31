# Practica de Vulnerabilidades Android

Actividad completada usando el archivo `android_security_game.html`, un laboratorio gamificado de vulnerabilidades y defensas en aplicaciones Android.

## Entrega generada

- `Practica_Vulnerabilidades_Android_Evidencias.docx`: documento final con caratula, resumen y capturas de evidencia.
- `Practica_Vulnerabilidades_Android_Evidencias.pdf`: version PDF del documento final.
- `evidencias/`: carpeta con las capturas usadas en el documento.

## Resultado final

- Desafios completados: `12/12`
- Respuestas correctas: `12/12`
- Puntaje final: `1000 XP`
- Rango obtenido: `Red Teamer`
- Logros desbloqueados: `8/8`

## Vulnerabilidades revisadas

1. Almacenamiento Inseguro
2. Intent Injection
3. SSL Pinning Bypass
4. Permisos Excesivos
5. Tapjacking
6. Backup Inseguro
7. WebView Injection
8. Root Detection Bypass
9. Logging Sensible
10. Broadcast Inseguro
11. Criptografia Debil
12. Reverse Engineering

## Defensas revisadas

- Android Keystore y EncryptedSharedPreferences
- `android:exported="false"`, permisos custom y validacion de Intents
- Network Security Config y OkHttp CertificatePinner
- Principio de minimo privilegio y permisos en runtime
- `filterTouchesWhenObscured` y validacion de overlays
- `allowBackup="false"`, reglas de exclusion y `dataExtractionRules`
- WebView con allowlist, Safe Browsing y `@JavascriptInterface`
- Play Integrity API, RootBeer y controles anti-Frida
- `BuildConfig.DEBUG`, ProGuard/R8 y eliminacion de logs sensibles
- LocalBroadcastManager, permisos custom e Intents explicitos
- AES-256-GCM con IV aleatorio y claves en Android Keystore
- ProGuard/R8, NDK, secretos en servidor y verificacion de firma

## Como abrir la actividad

Abre `android_security_game.html` en un navegador moderno. Desde el laboratorio se puede seleccionar cada desafio, responder el quiz, revisar la explicacion y consultar el glosario de herramientas.

## Autor

Gabriel Paz 221087

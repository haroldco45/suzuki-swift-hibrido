# Suzuki Swift Híbrido — app de ventas (PWA)

App estilo Toyota para presentar y vender el Suzuki Swift Híbrido (GL y GLX) desde el celular.

**En vivo:** https://haroldco45.github.io/suzuki-swift-hibrido/

## Qué trae
- Portada con rango de precios ($65.990.000 a $77.990.000)
- Selector de versión GL / GLX con lo que suma cada una
- Cómo funciona el sistema híbrido SHVS
- Tabla de seguridad GL vs GLX
- 4 videos de prueba y reseña (YouTube, carga liviana)
- Ficha técnica completa lado a lado
- Simulador de cuota (precio, cuota inicial, plazo y tasa editable) que envía la simulación por WhatsApp
- Formulario de prueba de manejo que abre WhatsApp con el mensaje listo (no guarda datos; aviso Ley 1581 de 2012)
- Instalable como app (manifest + service worker)

## Cambiar el asesor
En `index.html`, bloque `CONFIG` al inicio del script:
```js
const CONFIG = { whatsapp: '573202592906', asesor: 'Suzuki Autos' };
```

## Publicar en GitHub Pages
1. Crear el repo `suzuki-swift-hibrido` en la cuenta `haroldco45`.
2. Subir todos los archivos de esta carpeta a la raíz.
3. Settings → Pages → Branch `main`, carpeta `/ (root)`.

Fuente de datos: ficha técnica oficial del Suzuki Swift Híbrido (noviembre de 2024). Precios de referencia.

Desarrollada por Vibras Positivas HM — Derechos de Autor Reservados

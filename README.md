# Club Laguna Azul

Página web móvil para agendar, confirmar o reprogramar visitas al **Club Laguna Azul**: Panamericana Sur KM 553, pasando SENASA, Trujillo, Perú.

> Un día diferente, momentos para compartir en familia.

## Contenido

```
index.html          Página principal (HTML, CSS, JavaScript y fotos incluidas en un solo archivo)
```

## Funciones

- Formularios para **agendar**, **confirmar** y **reprogramar** la visita. Al enviarlos, se abre WhatsApp con el mensaje ya redactado.
- Validaciones: campos obligatorios, celular de 9 dígitos, máximo 5 personas por grupo y no se aceptan fechas pasadas.
- La reprogramación debe pedirse con un mínimo de **24 horas** de anticipación.
- Secciones: instalaciones, condiciones de visita, normas de la piscina y ubicación.
- No guarda datos personales; no tiene base de datos, registro de usuarios ni pagos.

## Configuración

Al final de `index.html`, en el bloque `CONFIGURACIÓN`:

```js
var WHATSAPP_CLUB = "51980543038";                               // Número con código de país 51
var MAPS_URL = "https://maps.app.goo.gl/cN4FnyyKuhbxEfLHA";      // Ubicación en Google Maps
```

## Publicación en Vercel

1. Sube este repositorio a GitHub.
2. En vercel.com elige **Add New → Project**, importa el repositorio y pulsa **Deploy**. En Framework Preset deja **Other**.
3. Cada cambio que subas a GitHub se publica automáticamente.

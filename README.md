# Caramelo Tours · Fase 1 · El plano

Entrega de la Fase 1 para revisar en Visual Studio Code.

## Qué hay en esta carpeta

```
caramelo-fase1/
├── README.md                    (este archivo)
├── docs/
│   ├── 01-fase1-el-plano.md     documento de la fase: marca, público, competencia, estructura, pendientes
│   └── estructura-sitio.png     diagrama: 1 home, 3 landings, 3 campañas de Meta
└── web/
    ├── index.html               home de escritorio (boceto con video y movimiento)
    ├── venezuela.html           landing de Venezuela: la lista de precios mejorada (todos los destinos)
    ├── movil.html               vista celular (boceto, 390 px de ancho)
    └── assets/
        ├── img/                 logo y fotos
        └── video/               clips del mar (540 px de ancho, sin audio)
```

## Cómo verlo en VS Code

1. Abre la carpeta `caramelo-fase1` en VS Code (Archivo, Abrir carpeta).
2. Instala la extensión **Live Server** (Ritwick Dey).
3. Clic derecho en `web/index.html` y elige **Open with Live Server**.
4. Para el documento, abre `docs/01-fase1-el-plano.md` y pulsa `Ctrl+Shift+V` (vista previa de Markdown).

La home enlaza a `venezuela.html` (tarjetas de destino y botones). Internacional y Vuelos y traslados abren WhatsApp directo.

Sin extensión: también puedes abrir `web/index.html` con doble clic en el navegador. Los videos funcionan igual.

## Qué es y qué no es

- Es un **boceto de diseño** para corregir, no el sitio final. No tiene backend, pagos, buscador de vuelos real ni panel de administración.
- Las pestañas del buscador, el juego "¿Qué plan de mar te toca hoy?" y el carrusel de testimonios funcionan con un poco de JavaScript dentro de `index.html`.
- Los precios de `venezuela.html` salen de tu lista de octubre 2026 (en REF, por persona): confirma que siguen vigentes. Los banners de cada destino son recortes de la lista, en baja resolución, hasta que lleguen las imágenes HD.
- Los textos entre corchetes ([PRECIO], [N]+, [Testimonio real]) son marcadores: no hay datos inventados.
- Los videos y fotos son los que enviaste, en baja resolución. Para la versión final hacen falta los originales.
- Antes de publicar videos o fotos donde se vean personas, confirmar que autorizaron su aparición.

## Datos de contacto usados (tomados de tu lista de precios)

- WhatsApp: +58 424 251 1630
- Instagram y TikTok: @caramelotoursoficial
- Correo: caramelotour22@gmail.com

## Siguiente paso

Fase 2, "Lo primero que ven": hero, propuesta de valor y alternativas para prueba A/B. Los pendientes están al final de `docs/01-fase1-el-plano.md`.

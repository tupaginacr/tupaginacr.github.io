# Registro de cambios – tupágina.cr

Aquí se anota cada cambio de la página, para saber qué se hizo y cuándo.

## Datos de la marca

- **Nombre:** tupágina.cr
- **Logo:** monograma "KA" en cuadro azul marino + frase "tu página" ("tu" y la "A" en turquesa)
- **Archivos del logo (carpeta `img`):**
  - `logo-ka-tupagina.svg` → para fondos claros (barra de navegación)
  - `logo-ka-tupagina-blanco.svg` → para fondos oscuros (pie de página)
  - `icono-ka.svg` → ícono cuadrado (pestaña del navegador y redes sociales)

## Colores

| Uso | Color | Código |
|---|---|---|
| Textos y fondos oscuros | Azul marino oscuro | `#0E2340` |
| Botones y detalles sobre fondo oscuro | Turquesa del logo | `#7FD1C6` |
| Títulos pequeños, checks e íconos sobre fondo claro | Turquesa oscuro | `#1F7A70` |
| Fondo general | Blanco azulado | `#F5F8FB` |
| Botón de WhatsApp | Verde WhatsApp | `#25D366` |

Los colores se cambian en `index.html`, dentro de `:root { ... }` al inicio del `<style>`.

## Historial

### 2026-11-07
- Se creó la página con Bootstrap 5: inicio, servicios, planes y precios, proceso, portafolio, sobre mí, preguntas frecuentes y contacto.
- Planes: Emprende $180, Pyme $380, Empresa $690 (pago único). Extras: mantenimiento desde $35/mes, página adicional $40, rediseño desde $250.
- Se eligió el nombre **tupágina.cr** y el logo **KA · tu página**.
- Se aplicó la paleta final (azul marino oscuro + turquesa). Se quitó el naranja.
- Botón flotante verde de WhatsApp a la derecha, con el texto "¿Hablamos?" en computadora y efecto de latido.
- El formulario de contacto arma el mensaje y lo abre en WhatsApp (no necesita servidor).

### 2026-11-07 (segunda actualización)
- Precios en **colones** con el monto aproximado en dólares (tipo de cambio de referencia usado: ~₡455 por dólar):
  - Emprende **₡85.000** (aprox. $185) · Pyme **₡175.000** (aprox. $385) · Empresa **₡315.000** (aprox. $690) — pago único
  - Mantenimiento desde **₡16.000/mes** (aprox. $35) · Página adicional **₡18.000** (aprox. $40) · Rediseño desde **₡115.000** (aprox. $250)
- "Sobre mí" pasó a **"Nosotros"**: se habla como empresa (sin nombre personal ni mención de estudiante). Se agregaron 4 valores: acompañamiento, manual de uso, respuesta rápida, sitios seguros.
- Todos los textos pasaron a primera persona plural ("creamos", "le enviamos", "escríbanos").
- Se agregó **"Manual de uso"** en los tres planes y en el paso 4 del proceso.
- Nueva pregunta frecuente: "¿Qué pasa después de que entregan mi página?". Título de preguntas: "Lo que más nos preguntan".
- El mensaje de WhatsApp del formulario ahora empieza con "Hola tupágina.cr".
- Pie de página: "tupágina.cr · Diseño y desarrollo web".
- Dirección de contacto: "San José, Costa Rica".

> Si el tipo de cambio cambia mucho, actualizar los montos "aprox. $" en la sección de planes.

### 2026-11-07 (tercera actualización)
- Correo del negocio: **contacto.tupaginacr@gmail.com** (sección de contacto). Reemplaza al correo personal.

### 2026-11-07 (cuarta actualización)
- Servicios ampliados a 9: Diseño de sitios web, Landing pages, Tiendas en línea, Rediseño de sitios web, Optimización SEO, Mantenimiento de sitios web, Diseño de logos, Diseño gráfico, Diseño responsive.
- Pie de página nuevo con 4 columnas: logo + ubicación + correo + botón "Contáctenos"; lista de servicios; enlaces rápidos; redes sociales (Facebook e Instagram).
- Los íconos de Facebook e Instagram tienen `href="#"` hasta que se creen las cuentas.

### 2026-11-07 (quinta actualización)
- Se quitó "+ IVA" de los precios (sección de planes). Volver a agregarlo solo después de inscribirse en Hacienda.

### 2026-11-07 (sexta actualización) — Portafolio
- El portafolio ahora se llama **"Diseños de muestra"** y tiene 3 **proyectos conceptuales** (marcas ficticias), cada uno con su propia página dentro de la carpeta `proyectos/`:
  - `proyectos/grano-de-oro/` → **Grano de Oro**, tostaduría de café (rediseño del trabajo de Café Britt del curso, sin marca ni fotos de Britt). Paleta: espresso `#2B1A12`, oro `#D4A933`, crema `#F7F0E5`, verde cafetal `#3E5B3A`. Letras: Playfair Display + Inter.
  - `proyectos/selva-y-mar/` → **Selva y Mar Tours**, tours en Manuel Antonio (rediseño del Trabajo 5, sin enlaces, redes ni WhatsApp reales del parque). Paleta: océano `#0B4F5C`, turquesa `#5FC4C0`, atardecer `#F6A54C`, arena `#F6EEDF`. Letras: Outfit + Inter.
  - `proyectos/luz-de-lavanda/` → **Luz de Lavanda**, velas y jabones artesanales (rediseño de Tema Libre). Paleta: lavanda `#7D6AA8`, ciruela `#3D2F52`, salvia `#9FB08A`, rubor `#ECC9C7`. Letras: Cormorant Garamond + Nunito Sans.
- Las imágenes de los 3 proyectos son **ilustraciones propias en SVG** (no se usaron fotos de internet ni de marcas reales).
- Cada proyecto muestra arriba el aviso "Proyecto conceptual · Marca ficticia" y en el pie "Diseño y desarrollo: tupágina.cr".
- Miniaturas del portafolio en `img/portafolio-*.jpg`.
- Se quitaron del portafolio: Instante Studio, Sitio responsive y Sistema web.

### 2026-11-07 (séptima actualización) — Fotos de Grano de Oro
- Se agregaron fotos creadas con IA (Gemini) en `proyectos/grano-de-oro/img/`:
  - `portada.jpg` → fondo de la portada (taza de café), con capa oscura para que el texto se lea.
  - `historia.jpg` → manos de caficultor con granos maduros, en la sección "Nuestra historia".
  - `bolsa.jpg` → una sola bolsa café oscuro (foto original en alta calidad) usada para los 4 cafés. El nombre de cada café se escribe con HTML encima de la etiqueta, y cada uno lleva una franja de color abajo (café, verde, caramelo, vino). Se descartó la versión con bolsas recoloreadas porque se veía artificial y borrosa.
- Se actualizó la miniatura del portafolio (`img/portafolio-grano-de-oro.jpg`).

### 2026-11-07 (octava actualización) — Fotos de Luz de Lavanda
- Fotos creadas con IA (Gemini) en `proyectos/luz-de-lavanda/img/`:
  - `portada.jpg` → foto de la portada (velas y jabones), con marco lila y tarjeta "Hecho a mano".
  - `vela-lavanda.jpg`, `vela-eucalipto.jpg`, `jabon-rosas.jpg`, `jabon-miel.jpg`, `difusor.jpg`, `jabon-aloe.jpg` → recortadas de una sola imagen con 8 productos.
  - `proceso.jpg` → artesana vertiendo cera, arriba de "Nuestro proceso".
  - `personalizados.jpg` → mesa de evento, junto al texto de pedidos personalizados.
- La imagen del tazón de cerámica no se usó (no corresponde a la marca).
- Se actualizó la miniatura del portafolio.

### 2026-11-07 (novena actualización) — Fotos TEMPORALES de Selva y Mar
- ⚠️ Se usaron **temporalmente** las fotos del proyecto original del curso (Trabajo 5), en `proyectos/selva-y-mar/img/`. Son fotos tomadas de internet y **no se conoce su licencia**: hay que reemplazarlas por fotos libres de derechos o propias antes de publicar el sitio.
  - `portada.jpg` (playa con la roca), `tour-caminata.jpg`, `tour-miradores.jpg`, `tour-privado.jpg`, `tour-traslados.jpg`, `playa-manuel-antonio.jpg`, `playa-espadilla.jpg`, `playa-biesanz.jpg`.
- Para que los tours coincidan con las fotos disponibles, se cambiaron: "Kayak en el manglar" → **Miradores y Punta Catedral** ($55) y "Atardecer en catamarán" → **Traslados privados** (desde $40). También en los formularios y el pie de página.
- La portada ahora es una foto con capa azul oscura para que se lea el texto.

### 2026-11-07 (décima actualización) — Vista previa al compartir
- Se agregaron etiquetas Open Graph y Twitter en `index.html` y en los 3 proyectos, para que al pegar el enlace en WhatsApp, Facebook o LinkedIn aparezca una tarjeta con imagen, título y descripción.
- Imagen para compartir: `img/compartir.jpg` (1200 × 630): logo, "Páginas web que generan confianza", botón "Cotice sin compromiso".
- Los proyectos usan su miniatura del portafolio como imagen al compartir.
- Las direcciones usan `https://tupaginacr.github.io/` (el hosting planeado).

### 2026-11-07 (undécima actualización) — Cotizador interactivo
- Nueva sección **Cotizador** (después de los planes) y enlace "Cotizador" en el menú y el pie de página.
- El cliente elige: tipo de sitio, páginas adicionales, extras y mantenimiento. Ve el total en colones, el aproximado en dólares y el tiempo de entrega. Con el botón "Enviar mi cotización" se abre WhatsApp con el detalle.
- Precios del cotizador (se cambian en el objeto `PRECIOS` del script, al final de `index.html`):
  - Landing page ₡85.000 (1 semana) · Sitio Pyme ₡175.000 (2–3 semanas) · Sitio Empresa ₡315.000 (3–4 semanas)
  - Página adicional ₡18.000
  - Catálogo con pedidos por WhatsApp ₡45.000 · Diseño de logo ₡35.000 · 5 artes para redes ₡20.000 · Blog ₡25.000 (incluido en Empresa) · Redacción de textos ₡25.000
  - Tienda con pagos en línea: se cotiza aparte
  - Mantenimiento ₡16.000/mes
  - Tipo de cambio para el aproximado en dólares: ₡455

### 2026-11-07 (duodécima actualización) — Confianza, ventas y Google
- **Política de privacidad**: nueva página `politica-privacidad.html` (basada en la Ley 8968 de Costa Rica). Enlazada debajo del formulario de contacto ("Al enviar acepta…"), en el aviso del cotizador y en el pie de página.
- **Sección "¿Por qué una página web?"** (antes de Servicios): 4 razones — más confianza, lo encuentran en Google, abierta 24 horas, es 100 % suya.
- **Paquete Logo + Página** (en Planes y precios): Logo + Landing page ₡110.000 (ahorra ₡10.000) y Logo + Sitio Pyme ₡195.000 (ahorra ₡15.000). En el cotizador, al marcar "Diseño de logo" se aplica el descuento automáticamente (`PRECIOS.descuentoLogo`).
- **Mejoras para Google (SEO)**:
  - Título: "Diseño de páginas web en Costa Rica | tupágina.cr" y nueva descripción con precios en colones.
  - Enlace canónico y datos estructurados (schema.org `ProfessionalService`) con nombre, correo, zona de servicio y rango de precios.
  - Nuevos archivos `robots.txt` y `sitemap.xml`.

### 2026-11-07 (decimotercera actualización) — Fotos libres en Selva y Mar
- Se reemplazaron las fotos temporales del curso por **fotos libres de derechos** (Pexels/Unsplash) que eligió Karina:
  - `portada.jpg` → vista aérea de Manuel Antonio con Punta Catedral.
  - `tour-caminata.jpg` → grupo caminando en sendero de madera.
  - `tour-miradores.jpg` → vista aérea del tómbolo.
  - `tour-privado.jpg` → puente de madera en la selva.
  - `tour-fauna.jpg` → monos carablanca durmiendo en una rama.
  - `playa-manuel-antonio.jpg`, `playa-espadilla.jpg`, `playa-biesanz.jpg` → playas.
- El 4.º tour cambió de "Traslados privados" a **Observación de fauna** ($50, 2 horas), porque no había foto de buseta.
- No se usaron: la foto de esnórquel, la segunda foto de caminantes (repetida), el mono solo, el río en la selva y una de las vistas aéreas.

## Pendientes

- [x] Correo del negocio elegido: contacto.tupaginacr@gmail.com (ya está en la página). Falta: nombre visible "tupágina.cr", foto de perfil con el ícono KA y datos de recuperación.
- [ ] Poner el número real de WhatsApp (línea nueva del negocio, pendiente) en `index.html`:
  - el botón flotante: `https://wa.me/50600000000`
  - el script: `const NUMERO_WHATSAPP = "50600000000";`
  - y el texto visible `+506 0000-0000` en la sección de contacto.
- [x] Portafolio con 3 proyectos conceptuales.
- [ ] Cuando haya clientes reales: agregarlos al portafolio como proyectos reales (con permiso y reseña).
- [x] Fotos de Selva y Mar reemplazadas por fotos libres. Opcional: anotar el enlace de origen de cada foto.
- [ ] Poner foto propia en la sección "Sobre mí".
- [ ] Revisar los métodos de pago que aparecen en las preguntas frecuentes (SINPE Móvil y transferencia).
- [ ] Crear páginas de **Facebook** e **Instagram** del negocio y poner sus enlaces en el pie de página (buscar `href="#" class="red-social"`).
- [ ] WhatsApp Business: para más adelante.
- [ ] LinkedIn: evaluar más adelante.
- [ ] Revisar y ajustar los precios de los extras del cotizador (propuestos, no definitivos).
- [ ] Consultar con Hacienda o un contador la inscripción para facturar (factura electrónica e IVA) antes del primer cobro formal.
- [ ] Al comprar dominio: cambiar `https://tupaginacr.github.io/` por el dominio en: etiquetas `og:` (index y proyectos), `canonical` y datos estructurados (`application/ld+json`) de `index.html`, `robots.txt` y `sitemap.xml`.
- [ ] Cuando tenga la línea nueva de WhatsApp: ponerla también en los datos estructurados (`"telephone": "+506 …"`).
- [ ] Después de publicar: registrar el sitio en Google Search Console y enviar el `sitemap.xml`.
- [ ] Revisar la política de privacidad con un abogado o contador si el negocio crece (es una base general).
- [ ] Después de publicar: probar la tarjeta en https://developers.facebook.com/tools/debug/ (pegar el enlace y tocar "Depurar").
- [ ] **Hosting (después):** publicar gratis en GitHub Pages → `https://tupaginacr.github.io`
- [ ] **Dominio (después):** `tupagina.cr` estaba disponible en nic.cr a $70/año + 13 % IVA (~$79). Opción barata: `tupaginacr.com` (~$10/año en spaceship.com o porkbun.com). Comprarlo cuando entre el primer cliente y conectarlo a GitHub Pages.
- [ ] **Correo con dominio (después):** cuando haya dominio, usar Cloudflare Email Routing (gratis) para tener por ejemplo hola@tupagina.cr que llegue al Gmail.

## Cómo subir cambios a GitHub (cuando ya esté publicado)

Abrir cmd en la carpeta del proyecto y escribir:

```
git add .
git commit -m "Descripción del cambio"
git push
```

Luego anotar el cambio en la sección **Historial** de este archivo.

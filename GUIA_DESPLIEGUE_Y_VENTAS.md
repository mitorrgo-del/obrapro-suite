# GUÍA DE OPERACIÓN Y ESCALADO: ObraPro Suite (0€ Inversión)

## 1. Qué es y por qué funciona
ObraPro Suite es un sistema B2B empaquetado para el sector de **reformas, construcción y pequeñas instalaciones** (albañilería, fontanería, electricidad, pladur).
* **Dolor que resuelve:** El 80% de los autónomos de reformas presupuestan a ojo, perdiendo entre 10.000 € y 40.000 € al año por imprevistos no presupuestados y subida de materiales.
* **Solución:** Sistema inteligente con cálculo de margen automático, catálogo de precios base y generador de presupuesto imprimible para cliente.
* **Precio de venta:** 39 € (pago único sin suscripción).

---

## 2. Archivos del Negocio Creados
Todos los archivos se encuentran en: `c:\Users\mitor\.gemini\antigravity\playground\ancient-singularity\obrafacil-app\`

* `index.html`: Landing page de alta conversión, optimizada para móviles, con:
  - Calculadora interactiva de pérdidas anuales por desvío de costes.
  - Tabla de desglose de partidas.
  - Testimonios y respuestas a objeciones.
  - Checkout integrado.
* `descarga.html`: Página post-pago con entrega inmediata del producto e instrucciones paso a paso.
* `ObraPro_Suite_Presupuestos_v1.xlsx`: El producto real digital con 3 hojas estructuradas (Calculador con fórmulas protegidas, Plantilla de Presupuesto oficial PDF para el cliente y Catálogo base de partidas).
* `generar_excel_producto.py`: Script generador de la plantilla Excel.

---

## 3. Cómo ponerlo online en 3 minutos (100% Gratis)

### Opción A: Vercel (Recomendada)
1. Entra en [vercel.com](https://vercel.com) (crea cuenta gratuita).
2. Arrastra la carpeta `obrafacil-app` o sube el repositorio.
3. Te dará una URL pública al instante (ej: `obrapro.vercel.app`) con SSL gratis.

### Opción B: Cloudflare Pages
1. Entra en [dash.cloudflare.com](https://dash.cloudflare.com) > Workers & Pages.
2. Sube la carpeta directa sin tocar nada más. 100% gratuito sin límite de tráfico.

---

## 4. Cómo automatizar los cobros a tu cuenta bancaria (0€ coste fijo)
Para cobrar con tarjeta/Bizum sin pagar cuotas mensuales fijas:

1. **Vía Gumroad o Lemonsqueezy:**
   * Creas un producto llamado "ObraPro Suite" a 39 €.
   * Subes el archivo `ObraPro_Suite_Presupuestos_v1.xlsx`.
   * En `index.html`, en el botón `btn-comprar`, sustituyes la función por tu enlace de pago directo de Gumroad.
   * Cobran solo un pequeño % cuando vendes.

2. **Vía Stripe Payment Links:**
   * Creas un enlace de pago de 39 € en Stripe Dashboard.
   * En la URL de éxito configuras la redirección a tu página `descarga.html`.
   * El cliente paga y se le descarga automáticamente el archivo.

---

## 5. Estrategia de Clientes sin Invertir en Publicidad
1. **Grupos de Facebook y Foros del Sector:** Publica un post compartiendo la calculadora de pérdidas: *"¿Cuánto dinero estáis perdiendo por no calcular los viajes al almacén y las mermas de pladur?"* y enlaza a la web.
2. **TikTok / Instagram Reels / YouTube Shorts:** Muestra vídeos cortos de 30 segundos comparando: *"Presupuesto en servilleta de papel VS Presupuesto profesional con ObraPro"*. Es un contenido con altísima viralidad entre profesionales.
3. **Outreach directo en Google Maps:** Busca pequeñas empresas de reformas en Google Maps en varias ciudades y mándales un correo o WhatsApp de cortesía ofreciéndoles el enlace.

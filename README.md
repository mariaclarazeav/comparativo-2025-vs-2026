# Comparativo Fajitex 2025 vs 2026

Dashboard de una sola página (`index.html`), sin dependencias más allá de las
fuentes de Google. Se abre directamente en el navegador.

Cinco bloques, con los datos entregados tal cual:

1. **Ventas por categoría** — Fajas, Short, Cinturilla y Brasier, Equipo de
   WhatsApp y Sitio Web, enero–septiembre de los dos años. Sale de las 72 filas
   del Excel dinámico (canal × categoría × mes) embebidas en el archivo: las
   tarjetas, los gráficos y las cuatro tablas se calculan de ahí, y los filtros
   de canal y categoría las recalculan todas. No incluye Accesorios, Vestido de
   baño ni Sin categoría.
2. **Septiembre 2026 por categoría — Shopify (e-commerce)**, **Venta online por
   subcanal** (FAJITEX_Dashboard_Online_Diario.xlsx, fuente definitiva de la
   venta online, con WhatsApp como un solo canal y el foco marcado).
3. **Pauta Meta** — gráfico de inversión mensual 2025 vs 2026 (ambos años cortados
   al 13 de septiembre), tabla mensual completa (inversión, compras, ROAS y CPA),
   detalle por categoría (inversión, compras en número y valor estimado, ROAS, CPA
   real, CPA como % del ticket frente al benchmark de 8% y semáforo) y ticket
   promedio por canal según el píxel de Meta.
   **Pauta Google Ads** — gráfico de costo mensual y tabla con costo y valor de
   conversión mes a mes (datos reales de Google), más los totales del periodo.
   Las conversiones y el costo por conversión del periodo siguen pendientes;
   septiembre 2026 sí tiene detalle por campaña.
4. **Embudo WhatsApp (agosto)** — rama de pauta desglosada. Debajo, las ventas
   cerradas por canal de origen, donde la fila de «Anuncio» es el mismo dato de
   la rama de pauta.
   **Embudo Shopify (agosto)** — sesiones por fuente y ventas atribuidas en dos
   donas, el embudo de conversión en trapecios, y las tablas de datos en
   secciones plegables. La advertencia del 74,3% sin atribuir va siempre visible.
   **Auditoría de walinks** — las cinco puertas de entrada a WhatsApp (home,
   anuncios Meta, Facebook, bio de Instagram y TikTok), cada una con su captura,
   el mensaje que llega hoy al chat y el mensaje sugerido. Debajo, las plantillas
   de campaña para Email y SMS. Las capturas viven en `img/` y se abren en grande
   al hacer clic.
5. **Leads / conversaciones / sesiones desde pauta** — 2025 completo vs 2026 parcial.
6. **Descuentos por canal (ERP, B2C)** — descuentos, neto y % sobre venta neta por
   canal, más la tendencia mensual del %. Septiembre 2026 trae por primera vez
   los cinco canales y el ticket promedio de cada uno. Sale del ERP de facturación, no de
   Shopify, así que no se mezcla con los Bloques 1 y 2.
7. **Auditoría del reporte de la agencia (MLO Growth)** — lo verificado contra
   nuestros datos de Meta, lo contradictorio, y el reparto real de los leads de
   pauta según B2Chat.
8. **Atribución por canal — Sitio Web vs WhatsApp (Meta Ads)** — inversión,
   clics, compras y ticket de cada canal, con el detalle mes a mes plegable.
   2025 es año completo y 2026 llega al 13 de septiembre.

Todo dato pendiente o proxy se muestra en amarillo con su nota, nunca oculto —
incluidas las capturas que faltan (las dos de la bio de Instagram).
Los totales, subtotales y porcentajes de variación se calculan a partir de las
cifras entregadas; no se agregó ningún dato nuevo.

Las cifras cuadran en tres niveles: los meses del Bloque 1 suman el total
general, las categorías del Bloque 2 suman ese mismo total, y la serie mensual
de los paneles suma tanto el total de cada categoría como las unidades de cada
mes del Bloque 1.

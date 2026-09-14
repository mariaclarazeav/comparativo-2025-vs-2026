# Comparativo Fajitex 2025 vs 2026

Dashboard de una sola página (`index.html`), sin dependencias más allá de las
fuentes de Google. Se abre directamente en el navegador.

Cinco bloques, con los datos entregados tal cual:

1. **Ventas generales por mes** — 4 categorías, ambos canales, enero–agosto.
   Arriba, dos gráficos mensuales (unidades y valor) con eje ajustado al rango
   de los datos; debajo, la tabla.
2. **Categoría × canal comercial** — unidades y valor, con subtotales por categoría.
   Debajo, cuatro paneles de tendencia (unidades por mes, enero–agosto), cada uno
   con el gráfico arriba y sus totales abajo, y eje vertical compartido desde cero: 2025 en nude oscuro `#9C7A56`, 2026 en morado `#4C1D6B`.
   Al pasar el mouse por un mes, un tooltip muestra las unidades de cada año y
   la diferencia 2026 − 2025 en unidades y en porcentaje.
3. **Pauta Meta** — gráfico de inversión mensual 2025 vs 2026 (ambos años cortados
   al 13 de septiembre) con su tabla de totales mensuales, y debajo el detalle por
   categoría: inversión, compras (número y valor estimado), ROAS, CPA real, CPA
   como % del ticket frente al benchmark de 8% y semáforo.
   **Pauta Google Ads** — valor de conversión mes a mes (dato real de Google) y
   tabla de totales del periodo. El costo, las conversiones y el costo por
   conversión siguen pendientes y entran por `googleTotales`.
4. **Embudo WhatsApp (agosto)** — rama de pauta desglosada; la rama de otros canales queda marcada como pendiente.
5. **Leads / conversaciones / sesiones desde pauta** — 2025 completo vs 2026 parcial.

Todo dato pendiente o proxy se muestra en amarillo con su nota, nunca oculto.
Los totales, subtotales y porcentajes de variación se calculan a partir de las
cifras entregadas; no se agregó ningún dato nuevo.

Las cifras cuadran en tres niveles: los meses del Bloque 1 suman el total
general, las categorías del Bloque 2 suman ese mismo total, y la serie mensual
de los paneles suma tanto el total de cada categoría como las unidades de cada
mes del Bloque 1.

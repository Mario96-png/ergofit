# Validation Experiments — ErgoFit

## Hipótesis a Validar

### Hipótesis 1 (🔴 Crítica): Tráfico Orgánico en TikTok
**"Se puede conseguir tráfico orgánico significativo en TikTok para una tienda nicho de dropshipping sin invertir en publicidad."**

**Experimento:**
- Publicar 1 video al día durante 7 días en TikTok
- Contenido: antes/después, educativo, reviews, tips
- Sin inversión en ads

**Criterio de éxito:**
- ≥ 500 impresiones totales en la primera semana
- ≥ 5 clicks al link de la tienda
- Al menos 1 video con > 100 reproducciones

**Coste:** 0€ (solo tiempo)
**Estado:** 🔄 En curso

---

### Hipótesis 2 (🟡 Media): Calidad del Contenido Generado por IA
**"Un agente de IA puede generar contenido de calidad suficiente para redes sociales que parezca auténtico y genere engagement."**

**Experimento:**
- Generar imágenes y scripts con IA (Claude Sonnet + FAL)
- Publicar sin edición humana adicional
- Medir engagement (likes, comentarios, compartidos)

**Criterio de éxito:**
- Ratio de engagement > 2% en los posts
- Sin comentarios negativos sobre calidad del contenido

**Coste:** ~1-2€ en APIs de IA
**Estado:** ⏳ Pendiente (depende de H1)

---

### Hipótesis 3 (🟡 Media): Viabilidad Económica del Dropshipping
**"Los márgenes de dropshipping (30-50% sobre precio de venta) cubren los costes operativos (Shopify 29€/mes + APIs ~30€/mes) y dejan beneficio."**

**Experimento:**
- Calcular margen real por producto (precio venta - coste proveedor - comisiones Shopify)
- Monitorear primeros pedidos

**Criterio de éxito:**
- Margen neto por producto ≥ 15€
- Break-even con ≥ 3 ventas/mes

**Coste:** 29€/mes (Shopify)
**Estado:** ⏳ Pendiente (depende de H1)

---

### Hipótesis 4 (🟢 Baja): Automatización de Investigación de Productos
**"Es posible encontrar productos ganadores para dropshipping de forma automatizada vía IA."**

**Experimento:**
- Pedir al agente que investigue productos para un nicho dado
- Comparar resultados con búsqueda manual en AliExpress

**Criterio de éxito:**
- El agente encuentra ≥ 3 productos relevantes por nicho
- Los productos tienen buena relación calidad-precio

**Coste:** ~0.5€ en API
**Estado:** ⏳ Pendiente

---

### Hipótesis 5 (🟢 Baja): Escalabilidad del Modelo
**"Una persona sin experiencia técnica puede gestionar 3-5 tiendas simultáneamente con ayuda de agentes de IA."**

**Experimento:**
- Una vez validado H1, repetir el proceso con un segundo nicho
- Medir tiempo de gestión semanal

**Criterio de éxito:**
- < 2 horas de gestión semanal por tienda
- Sin caídas en calidad del contenido

**Coste:** Variable
**Estado:** ⏳ Pendiente (depende de H1)

---

## Resumen de Prioridades

| Prioridad | Hipótesis | Estado | Siguiente acción |
|-----------|-----------|--------|-----------------|
| 🔴 1 | Tráfico orgánico TikTok | 🔄 En curso | Publicar Día 1 y medir |
| 🟡 2 | Calidad contenido IA | ⏳ Espera | Evaluar tras 7 días |
| 🟡 3 | Viabilidad económica | ⏳ Espera | Evaluar tras primera venta |
| 🟢 4 | Automatización investigación | ⏳ Espera | Tras validar H1 |
| 🟢 5 | Escalabilidad | ⏳ Espera | Tras validar H1-H3 |

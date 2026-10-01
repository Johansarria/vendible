# Vendible — Agentes de IA que venden por WhatsApp

**🏠 [vendible.cloud](https://vendible.cloud/) · Cali, Colombia · [LinkedIn](https://www.linkedin.com/company/vendiblecloud/) · [Instagram](https://www.instagram.com/vendiblecloud/)**

---

Vendible despliega agentes de IA que atienden, venden y dan posventa por el WhatsApp Business oficial (Meta Cloud API) de un negocio, sobre sus datos reales: inventario, pedidos, citas y clientes. El agente no improvisa datos duros: consulta el inventario antes de prometer disponibilidad o precio, y pasa el caso a una persona del equipo cuando se sale del guion.

## 📊 Caso medido: AUREN

Tienda de calzado en Shopify ([aurenstore.store](https://aurenstore.store)). Medición del **1-ago al 30-sep-2026**, sobre la base de datos de la tienda en solo lectura:

| Métrica | Valor |
|---|---|
| Facturado en la ventana | **$10.475.000 COP** (59 pedidos) |
| Pedidos que pasan por WhatsApp | **67,3 %** (corte 21-sep) |
| Clientes en base propia, con origen | **119** (y 46 leads) |
| Ticket promedio | **$177.542 COP** |

> **Qué no se puede atribuir al sistema:** en la misma ventana entró pauta pagada que administra un tercero, y no hay grupo de control. El método completo está en el [caso AUREN](https://vendible.cloud/casos/auren/).

## ⚙️ Qué hace

- **Atención 24/7** con relevo a una persona, sobre el inventario y los precios reales.
- **Recuperación de carritos abandonados** con escalera de mensajes que se detiene cuando el pedido se paga.
- **Guías de envío y posventa** con el estado real del despacho.
- **Agenda y citas** para negocios con cita previa (salones, consultorios, talleres).
- **Visibilidad en IA (AEO):** que el negocio sea citable por ChatGPT, Gemini y Perplexity.

## 📚 Dónde leer más

| Página | De qué trata |
|---|---|
| [Qué es un agente de IA para WhatsApp](https://vendible.cloud/blog/que-es-un-agente-de-ia-para-whatsapp/) | Agente vs. chatbot, con el caso real |
| [Caso AUREN](https://vendible.cloud/casos/auren/) | Qué se construyó, cómo se midió y qué no se atribuye |
| [Recuperación de carritos](https://vendible.cloud/casos-de-uso/recuperacion-carritos/) | El flujo completo, minuto a minuto |
| [Integración con Shopify](https://vendible.cloud/integracion/shopify/) | Agente sobre un catálogo de Shopify |
| [Integración con WooCommerce](https://vendible.cloud/integracion/woocommerce/) | Inventario real y posventa sin plugins nuevos |
| [Visibilidad en IA](https://vendible.cloud/casos-de-uso/visibilidad-ia/) | Qué hace citable a un negocio y cómo se mide |
| [Cómo se cotiza](https://vendible.cloud/precios/) | Qué mueve el precio |

## 🧱 Stack técnico

| Capa | Tecnología |
|---|---|
| **Agente conversacional** | LLM con acceso a inventario real vía API |
| **WhatsApp Business** | API oficial de Meta (WABA) con plantillas aprobadas |
| **Backend** | Python, desplegado en VPS |
| **Proxy/caché** | Caddy + Cloudflare |
| **Frontend** | HTML/CSS estático (landing), tema Shopify a medida (tienda) |

## 🗂️ Este repo

Contiene una copia de la **landing page** (`index.html`) y sus assets estáticos. La fuente de verdad es [vendible.cloud](https://vendible.cloud/). El código del agente y los scripts de despliegue se mantienen privados.

## 📄 Licencia

Material comercial público de Vendible. El código del agente y la lógica de producción son propiedad de Johan Sarria y no están incluidos aquí.

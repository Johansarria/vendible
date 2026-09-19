# Vendible — Agentes de IA que venden por WhatsApp

**🏠 [vendible.cloud](https://vendible.cloud/) · Cali, Colombia**

---

Vendible es un producto de inteligencia artificial que convierte el WhatsApp oficial de un negocio en un vendedor autónomo: atención 24/7, consulta de inventario real, recuperación de carritos abandonados y notificación de guías de envío — sin intervención humana.

En producción desde agosto de 2026 sobre una tienda real en Colombia.

## 📊 Resultados en producción

| Métrica | Valor |
|---|---|
| Pedidos entrando por WhatsApp | **71,7 %** |
| Conversión clic → pedido (1 mes) | **18 % → 55 %** |
| Base de clientes propia, con origen | **90** |
| Ticket promedio | **$186.000 COP** |

*Medición agosto–septiembre 2026 sobre una tienda real. Definición y período explícitos.*

## ⚙️ Qué hace

- **Atención 24/7** — responde consultas de stock, precios y disponibilidad sobre el inventario real, con relevo humano cuando el caso lo requiere.
- **Recuperación de carritos** — escalera de descuentos programada sobre el carrito abandonado real, no sobre templates genéricos.
- **Guías de envío automáticas** — el cliente recibe su guía en el momento del despacho.
- **Leads con origen** — cada interesado queda con el dato de la campaña que lo trajo (UTM, red social, QR).

También funciona para negocios con **agenda** (salones, barberías, consultorios): asigna citas sobre la disponibilidad real, confirma, recuerda y reprograma.

## 🧱 Stack técnico

| Capa | Tecnología |
|---|---|
| **Agente conversacional** | LLM auto-gestionado con acceso a inventario real vía API |
| **WhatsApp Business** | API oficial de Meta (WABA) con plantillas aprobadas |
| **Backend** | Python, desplegado en VPS (Hostinger) |
| **Proxy/Cache** | Caddy (auto-renovación SSL, compresión zstd/gzip) |
| **Frontend** | HTML/CSS estático (landing), tema Shopify a medida (tienda) |
| **Orquestación** | Hermes Agent |

## 🗂️ Este repo

Contiene la **landing page** de Vendible (`index.html`) y sus assets estáticos (favicons, fuente, opengraph). El código de producción del agente y los scripts de despliegue se mantienen privados.

→ [Ver el sitio en vivo](https://vendible.cloud/)

## 📄 Licencia

Este repositorio contiene material comercial público de Vendible. El código del agente y la lógica de producción son propiedad de Johan Sarria y no están incluidos aquí.

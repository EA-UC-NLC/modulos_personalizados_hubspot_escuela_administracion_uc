# Módulos Personalizados HubSpot - Escuela de Administración UC

Colección de módulos HTML reutilizables y personalizados para campañas de email marketing de la Escuela de Administración de la Pontificia Universidad Católica de Chile.

## 📋 Descripción

Este repositorio contiene componentes de email HTML-based diseñados específicamente para HubSpot, manteniendo estilos inline para máxima compatibilidad con clientes de email. Cada módulo sigue una línea estética coherente con los colores corporativos y tipografía de la institución.

## 🎨 Línea Estética

- **Color Primario**: #00b0db (Azul corporativo)
- **Colores Secundarios**: #ffffff (blanco), #03122E (azul oscuro), tonos beige/café
- **Iconografía**: Iconos de línea simbia desde Flaticon CDN (sin vínculos, solo imágenes)
- **Tipografía**: Arial, sans-serif
- **Layout**: Table-based (compatible con legacy email clients)
- **Estilos**: Inline CSS únicamente (requerido para HubSpot)

## 📁 Estructura del Repositorio

```
modulos_personalizados_hubspot_escuela_administracion_uc/
├── README.md
├── CorreosMKT/
│   └── Charla_MBA_19-03-2026/
│       └── content_silver_boxes.html         # Módulo: 3 cards con info
├── assets/
│   ├── calendario.png
│   ├── reloj-circular.png
│   └── camara-de-video.png
└── modulos/
    ├── hero_educativo/
    ├── info_cards_grid/
    ├── event_list/
    ├── cta_button/
    └── divider_section/
```

## 🧩 Módulos Disponibles

### 1. Content Silver Boxes
**Ubicación**: `CorreosMKT/Charla_MBA_19-03-2026/content_silver_boxes.html`

Componente de 3 cards informativos con:
- Icono (imagen Flaticon CDN)
- Título/texto principal
- Estilos redondeados y sombra
- Responsive y compatible con email

**Uso**: Ideal para mostrar tres datos clave (fecha, hora, modalidad).

---

## 🚀 Cómo Usar los Módulos

1. Copiar el HTML del módulo deseado
2. Pegar en el editor de HubSpot
3. Personalizar textos e imágenes
4. Ajustar dimensiones si es requerido

## 📧 Compatibilidad

- ✅ Gmail
- ✅ Outlook
- ✅ Apple Mail
- ✅ HubSpot Email Editor

## 🔧 Guía de Desarrollo

### Checklist Email-Safe

- [ ] Sin estilos externos (solo inline)
- [ ] Sin JavaScript
- [ ] Imágenes con `alt` text
- [ ] Table-based layout
- [ ] Ancho máximo 600px
- [ ] Colores hexadecimales explícitos

### Convención de Nombres

```
{tipo_elemento}_{tipo_contenido}.html

Ejemplos:
- hero_educativo.html
- info_cards_pricing.html
- event_list_webinar.html
- cta_button_green.html
```

## 📚 Recursos

- [Flaticon CDN](https://cdn-icons-png.flaticon.com/)
- [Campaign Monitor Email Guide](https://www.campaignmonitor.com/css/)

---

**Última actualización**: Marzo 20, 2026  
**Versión**: 1.0.0
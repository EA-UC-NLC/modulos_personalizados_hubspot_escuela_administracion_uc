# 📚 Índice de Módulos - Escuela de Administración UC

Guía de referencia rápida de todos los módulos disponibles en la librería.

---

## 🎯 Módulos por Categoría

### 🏢 HEROES / BANNERS PRINCIPALES

#### `hero_evento.html`
**Ubicación**: `modulos/hero_educativo/hero_evento.html`

Diseño de banner para eventos, charlas, reuniones especiales.
- Gradiente azul elegante
- Información de fecha, hora y lugar
- CTA destacado
- Ideal para: Charlas, seminarios, reuniones anuales

**Variables personalizables**:
- Titulo principal
- Subtítulo/descripción
- Fecha y hora
- Lugar/modalidad
- Texto botón CTA

---

#### `hero_diplomado.html`
**Ubicación**: `modulos/hero_educativo/hero_diplomado.html`

Banner especializado para promoción de diplomados y programas educativos.
- Layout 2 columnas (contenido + icono visual)
- Color corporativo azul oscuro
- Datos clave: inicio, modalidad, duración
- Botón "Ver más detalles"

**Variables personalizables**:
- Nombre del diplomado
- Fecha de inicio
- Modalidad (presencial/online/híbrida)
- Duración
- Descripción

---

#### `hero_destacado.html`
**Ubicación**: `modulos/hero_educativo/hero_destacado.html`

Banner para ofertas limitadas, descuentos, anuncios especiales.
- Diseño urgencia (contador de cupos y días)
- Gradiente destacado en azul
- Badge "Oferta limitada"
- Ideal para: Promociones, descuentos, inscripciones

**Variables personalizables**:
- Porcentaje/tipo de descuento
- Cupos disponibles
- Días restantes
- Descripción de oferta
- Texto disclaimer

---

### 📇 INFO CARDS / TARJETAS

#### `cards_4col.html`
**Ubicación**: `modulos/info_cards/cards_4col.html`

Grid de 4 tarjetas informativas con iconos.
- 4 cards iguales en ancho completo (600px)
- Iconos de Flaticon CDN
- Sombreado sutil
- Ideal para: Características, beneficios, datos clave

**Casos de uso**:
- Duración, Horario, Modalidad, Certificado
- Precio, Requerimientos, Beneficios, Apoyo
- Calendario, Reloj, Ubicación, Contacto

**Variables personalizables**:
- Título de cada card
- Descripción
- URL icono (Flaticon CDN)
- Número de cards (agregar/quitar)

---

#### `cards_grid_2x2.html`
**Ubicación**: `modulos/info_cards/cards_grid_2x2.html`

Grid 2x2 para mostrar 4 elementos con imagen/avatar.
- Tarjetas más grandes con espacio para imagen
- Perfectas para speakers, testimonios, facilitadores
- Colores degradados personalizables
- Sombra y borde redondeado

**Casos de uso**:
- Panel de speakers/facilitadores
- Testimonios de estudiantes
- Equipo docente destacado
- Partners/colaboradores

**Variables personalizables**:
- Nombre y apellido
- Cargo/especialidad
- Descripción corta (bio)
- Emoji o símbolo (en ausencia de foto)
- Color de fondo

---

### 📋 LISTADOS

#### `event_list_program.html`
**Ubicación**: `modulos/event_list/event_list_program.html`

Listado de eventos/programas en formato de línea.
- Ícono + título + fechas + link
- Separadores entre items
- Compacto y escaneable
- Ideal para: Calendarios, diplomados disponibles, webinars

**Casos de uso**:
- Listado de diplomados próximos
- Calendario de charlas
- Eventos mensuales
- Programas disponibles

**Variables personalizables**:
- Número de items (agregar/quitar filas)
- Título programa/evento
- Fecha inicio
- Modalidad
- URL del enlace "Ver más"

---

### ✨ BOTONES / CTA

#### `cta_multiple.html`
**Ubicación**: `modulos/cta_button/cta_multiple.html`

Colección de variantes de botones CTA.
- Botón azul primario
- Botón dorado/amarillo
- Botón blanco con borde
- Botón con icono

**Casos de uso**:
- Registrarse
- Ver más detalles
- Descargar brochure
- Contacto/información

**Colores disponibles**:
- Azul primario: `#00b0db`
- Dorado: `#ffd700`
- Azul oscuro: `#4a5f9d`
- Blanco: `#ffffff`

---

### 🔀 DIVISORES Y HEADERS

#### `divider_header.html`
**Ubicación**: `modulos/divider_header/divider_header.html`

Colección de separadores y headers de sección.
- Divider lineal simple
- Divider con icono central
- Header azul (sección principales)
- Header gradiente dorado
- Header azul oscuro
- Divider gradiente
- Divider doble línea

**Casos de uso**:
- Separar secciones
- Crear énfasis visual
- Agrupar contenido
- Títulos de sección

---

## 🎨 PALETA DE COLORES CORPORATIVA

```css
--color-primary: #00b0db        /* Azul corporativo */
--color-dark: #03122E           /* Azul oscuro */
--color-secondary: #4a5f9d      /* Azul secundario */
--color-accent: #ffd700         /* Dorado/Amarillo */
--color-white: #ffffff          /* Blanco */
--color-light-gray: #f8f9fa     /* Gris claro */
--color-border: #e0e0e0         /* Gris bordes */
--color-text: #666666           /* Texto medio */
```

---

## 📏 DIMENSIONES ESTÁNDAR

- **Ancho máximo**: 600px (email safe)
- **Padding estándar**: 20-30px
- **Border radius**: 6-12px
- **Sombra estándar**: `0 4px 12px rgba(0,60,90,0.12)`

---

## 🔗 RECURSOS DE ICONOS

**CDN Flaticon**: https://cdn-icons-png.flaticon.com/

### Iconos utilizados:

| Icono | URL CDN |
|-------|---------|
| Calendario | `https://cdn-icons-png.flaticon.com/128/2370/2370264.png` |
| Reloj | `https://cdn-icons-png.flaticon.com/128/601/601019.png` |
| Cámara/Video | `https://cdn-icons-png.flaticon.com/128/4021/4021967.png` |

---

## ✅ CHECKLIST ANTES DE ENVIAR

- [ ] Ancho máximo 600px
- [ ] Todos los estilos inline
- [ ] Sin JavaScript
- [ ] Imágenes con alt text
- [ ] Links con target="_blank"
- [ ] Testeado en 2+ clientes de email
- [ ] Colores en formato hexadecimal

---

## 🚀 PRÓXIMOS MÓDULOS PLANIFICADOS

- [ ] Sección de precios/pricing table
- [ ] Carrosel de imágenes
- [ ] Social media links grid
- [ ] Footer con múltiples links
- [ ] Testimonios en formato quote
- [ ] FAQ accordion simplificado
- [ ] Countdown timer visual

---

**Última actualización**: Marzo 20, 2026  
**Versión**: 1.1.0

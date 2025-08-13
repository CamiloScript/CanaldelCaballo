
# Canal del Caballo

Repositorio de documentación y recursos técnicos del sitio web oficial **Canal del Caballo**, desarrollado en **WordPress** con **Elementor** (tema Hello Elementor) y **WooCommerce**.  
Este proyecto centraliza toda la información técnica, estructura, personalizaciones y procedimientos realizados desde su creación hasta el despliegue en producción.

---

## 📌 LINK DIRECTO MAQUETA CANAL DEL CABALLO 2025

https://canaldelcaballocl.42web.io

---
## 📌 Descripción General

El sitio se diseñó como una **one-page** con páginas adicionales para WooCommerce y secciones personalizadas. Está orientado a presentar el proyecto Canal del Caballo, ofrecer señal online en vivo, mostrar contenido multimedia y vender productos mediante una tienda online.

### Secciones principales:
- **Inicio** → Header fijo moderno, fondo negro con video en loop.
- **Nosotros** → Video de fondo en escritorio / imagen en móvil, textos optimizados.
- **Señal Online** → Streaming `.m3u8` integrado con MediaElementPlayer.
- **Galería** → (en desarrollo) 15 fotos y 10 videos.
- **Auspiciadores** → Grilla de logos en bloques.
- **Contacto** → Formulario funcional con WPForms.
- **CanalPlus** → Página independiente con video y diseño minimalista.

### Páginas adicionales (WooCommerce):
- **Tienda**
- **Carrito**
- **Checkout**
- **Mi Cuenta**

---

## 🛠️ Tecnologías y Plugins Utilizados

- **WordPress** – CMS base del proyecto.
- **Tema:** Hello Elementor (ligero y optimizado para Elementor).
- **Elementor** v3.30.4 – Constructor visual principal.
- **WooCommerce** v10.0.4 – Tienda online base.
- **WPForms Lite** – Formulario de contacto.
- **WP Mail SMTP** – Configuración de correo saliente.
- **Better Search Replace** v1.4.10 – Reemplazo masivo de URLs en la base de datos.
- **Simple Custom CSS and JS** v3.50 – Scripts personalizados (logo animado, video CanalPlus).
- **MediaElementPlayer** – Reproductor de señal en vivo `.m3u8`.
- **SnapWidget** – Integración gratuita de feed de Instagram.
- **Facebook Page Plugin** – Integración gratuita de feed de Facebook.

---

## 📂 Estructura de Archivos

/wp-content
/themes
/hello-elementor # Tema base
/plugins
/better-search-replace
/elementor
/simple-custom-css-js
/woocommerce
/wpforms-lite
/wp-mail-smtp
/uploads # Imágenes, videos y medios subidos
/custom-css # CSS personalizado para WooCommerce y otras páginas
/custom-js # Scripts personalizados (logo y videos)


> **Nota:** Se incluirán capturas de pantalla y diagramas visuales en futuras versiones del repositorio.

---

## 🗺️ Diagrama de Estructura del Sitio

```markdown
Canal del Caballo (Sitio WordPress)
│
├── Inicio
│   ├── Header fijo con logo y redes
│   ├── Video de fondo (loop)
│   └── Menú de navegación (anclas internas)
│
├── Nosotros
│   ├── Video de fondo (desktop)
│   ├── Imagen estática (mobile)
│   └── Biografía fundadores
│
├── Señal Online
│   └── Video en vivo .m3u8 con MediaElementPlayer
│
├── Galería (en desarrollo)
│   ├── Fotos (15 planificadas)
│   └── Videos (10 planificados)
│
├── Auspiciadores
│   └── Logos en grilla responsiva
│
├── Contacto
│   ├── Formulario WPForms
│   └── Envío gestionado por WP Mail SMTP
│
├── CanalPlus
│   └── Página blanca minimalista con video
│
└── WooCommerce
    ├── Tienda
    ├── Carrito
    ├── Checkout
    └── Mi Cuenta
```
---

## 📱 Responsividad y Optimización
Para garantizar un diseño profesional en móviles:

- Se realizaron pruebas de responsividad en resoluciones desktop, tablet y smartphone.

- Problemas detectados en WooCommerce: botones e iconos sobredimensionados.

- Solución aplicada: creación de un contenedor general en cada página para controlar proporciones y aplicar CSS adaptativo.

- Configuración para mostrar un producto por fila en móvil y evitar desbordamientos.
  
---

## 🔄 Flujo de Desarrollo
Diseño inicial en LocalWP (entorno local).

- Creación de secciones y páginas con Elementor.

- Inserción de video .m3u8 y redes sociales mediante SnapWidget y Facebook Page Plugin.

- Migración a hosting InfinityFree.

- Reemplazo de URLs internas con Better Search Replace.

- Ajustes CSS para WooCommerce y optimización móvil.

---

## 🚀 Despliegue
El sitio se despliega en InfinityFree (Para pruebas, se carga maqueta a la cual se le realizan
pruebas funcionales.
La migración incluyó:

- Subida de archivos vía FTP.

- Importación de base de datos.

- Reemplazo de rutas internas con Better Search Replace.
  
---

## 📸 Capturas de Pantalla
(Pendiente — se agregarán imágenes y diagramas visuales en próximas actualizaciones)

---

## 📋 Pendientes / Próximas Mejoras

- Optimización de carga de videos y calidad de fotografias (Logos/Iconos).

- Integración de pasarelas de pago locales e internacionales.

- Mejoras visuales en la sección CanalPlus.

---

## 📜 Licencia
Este repositorio contiene únicamente documentación y recursos técnicos.
No se distribuye el código fuente completo por derechos de terceros.

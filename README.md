# <div align="center"> 🎣 PabloTC Fishing — Portfolio Personal de Pesca </div>

<div align="center">

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![TypeScript](https://img.shields.io/badge/typescript-%23007acc.svg?style=for-the-badge&logo=typescript&logoColor=white) ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

</div>

> [!NOTE]
> **Repositorio público de portfolio** — El código fuente completo se mantiene en un repositorio privado por razones de seguridad y propiedad intelectual. Este espacio sirve como portfolio técnico y documentación de arquitectura para reclutadores y desarrolladores interesados en el proyecto.

<div align="center">

Portfolio personal de **PabloTC Fishing** — un pescador apasionado que comparte su equipo, técnicas y experiencias desde las costas de Huelva y Cádiz.

🌐 **Web en vivo:** [pablotcfishing.com](https://pablotcfishing.com)

---

## 📸 Vista previa

![PabloTC Fishing](https://pablotcfishing.com/og-image.webp)

---

## 🚀 Tecnologías utilizadas

### Frontend
| Tecnología | Uso |
|:---:|:---:|
| [React 18](https://react.dev) | Framework de UI |
| [TypeScript](https://www.typescriptlang.org) | Tipado estático |
| [Vite](https://vitejs.dev) | Bundler y servidor de desarrollo |
| [Tailwind CSS](https://tailwindcss.com) | Estilos utilitarios |
| [React Router DOM](https://reactrouter.com) | Enrutamiento en cliente |
| [Framer Motion](https://www.framer.com/motion) | Animaciones |
| [Lucide React](https://lucide.dev) | Iconos |

### Backend
| Tecnología | Uso |
|:---:|:---:|
| PHP 8 | Procesamiento del formulario de contacto |
| [PHPMailer](https://github.com/PHPMailer/PHPMailer) | Envío de emails por SMTP |
| MySQL | Control de rate limiting y formulario |

### Infraestructura
| Servicio | Uso |
|:---:|:---:|
| [Hostinger](https://hostinger.com) | Hosting web |
| Hostinger Email | Servidor SMTP seguro |

---

## ✨ Características

### General
⚡ SPA con code splitting y lazy loading por ruta
🌙 Modo oscuro / claro con sincronización entre pestañas
🌍 Bilingüe — Español / Inglés con sistema de traducciones propio
📱 Totalmente responsive — móvil, tablet y escritorio
🖼️ Imágenes en formato WebP optimizadas con preload para mejorar el LCP
🗜️ Compresión Gzip y Brotli activas
🚀 HTTP/2 activo
📦 Caché de assets estáticos de 1 año

### Secciones de la web
**Inicio** — Hero, Sobre mí, Resumen del equipo, Redes sociales, Contacto
**Cañas de pesca** — 6 cañas premium con especificaciones completas y opinión personal
**Carretes** — 6 carretes de competición con especificaciones completas
**Accesorios** — Más de 10 accesorios esenciales
**Anzuelos** — Más de 15 tipos de anzuelos premium con consejo de veterano
**Hilos** — 6 tipos de hilo profesional para cada técnica
**Plomos** — Selección completa para cada situación de pesca

### Formulario de contacto
✅ Validación doble — frontend y backend
✅ Detección de emails temporales y dominios falsos
✅ Campo honeypot anti-bot
✅ Control de tiempo mínimo de relleno (anti-bot)
✅ Rate limit: 1 envío cada 30 segundos por IP
✅ Rate limit: 5 envíos máximos por día por IP
✅ Detección de patrones XSS
✅ Detección de inyección SQL
✅ Sanitización de todos los inputs
✅ Validación de longitud mínima y máxima
✅ Prepared statements en todas las consultas a la base de datos
✅ Checkbox de aceptación de privacidad obligatorio (RGPD)
✅ Contador regresivo visual cuando se alcanza el límite de tiempo
✅ Doble email — notificación al propietario y confirmación al usuario
✅ Versión en texto plano en todos los emails

---

## 🔒 Seguridad

### Cabeceras HTTP de seguridad — **Nota A+ en securityheaders.com**

| Cabecera | Protección |
|:---:|:---:|
| `Strict-Transport-Security` | Fuerza HTTPS en todos los accesos |
| `X-Frame-Options` | Protección anti-clickjacking |
| `X-Content-Type-Options` | Evita sniffing de tipos MIME |
| `X-XSS-Protection` | Filtro XSS en navegadores antiguos |
| `Referrer-Policy` | Control de información de referencia |
| `Permissions-Policy` | Geolocalización, micrófono y cámara desactivados |
| `X-Powered-By` | Eliminado — no expone tecnología del servidor |

### Medidas adicionales
🔐 HTTPS forzado con redirección permanente
🔐 Archivo `.env` bloqueado completamente a nivel de servidor
🔐 Todas las credenciales en `.env` — nunca en el código fuente
🔐 Mensajes de error genéricos — no expone información interna
🔐 Códigos de respuesta HTTP correctos según cada situación

---

## 📧 Configuración de Email

| Parámetro | Estado |
|:---:|:---:|
| Proveedor SMTP | Hostinger |
| SPF | ✅ Configurado y validado |
| DKIM | ✅ Configurado |
| DMARC | ✅ Configurado con informes diarios |
| Puntuación en mail-tester.com | **10 / 10** |
| Entrega en Gmail | ✅ Bandeja de entrada |
| Entrega en Hotmail/Outlook | ✅ Bandeja de entrada |

---

## 📊 Analytics y Seguimiento

| Servicio | Cuándo se activa |
|:---:|:---:|
| Google Analytics 4 | Solo si el usuario acepta cookies analíticas |
| Meta Pixel | Solo si el usuario acepta cookies de marketing |

Ambos servicios se cargan de forma **condicional** — únicamente tras el consentimiento explícito del usuario mediante el banner de cookies, cumpliendo con el RGPD.

---

## 🍪 Consentimiento de Cookies

Banner con opciones: Aceptar todo / Rechazar / Configurar
3 categorías: Necesarias, Analíticas, Marketing
Preferencias guardadas en cookies reales (no en localStorage)
100% cumplimiento con el RGPD

---

## 🔍 SEO

✅ Meta tags completos (descripción, palabras clave, autor, robots)
✅ Open Graph completo (Facebook, WhatsApp)
✅ Twitter Card configurada
✅ Schema.org JSON-LD (`Person` + `WebSite`)
✅ Sitemap XML enviado a Google Search Console y Bing Webmaster Tools
✅ URL canónica configurada
✅ Favicon en `.ico` y `.png` con múltiples tamaños
✅ Contenido estático en `<noscript>` para crawlers sin JavaScript
✅ Indexado en Google
✅ Indexado en Bing

---

## 🌐 Web en vivo

**[pablotcfishing.com](https://pablotcfishing.com)**

---

## 📬 Contacto

📧 [contacto@pablotcfishing.com](mailto:contacto@pablotcfishing.com)
🎥 [YouTube @PabloTCFishing](https://www.youtube.com/@PabloTCFishing)
📸 [Instagram @PabloTCFishing](https://instagram.com/PabloTCFishing)
🎵 [TikTok @PabloTCFishing](https://tiktok.com/@PabloTCFishing)

---

<sub>Hecho con pasión por la pesca deportiva 🎣</sub>

</div>

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

### **General**
⚡ SPA con code splitting y lazy loading por ruta <br>
🌙 Modo oscuro / claro con sincronización entre pestañas <br>
🌍 Bilingüe — Español / Inglés con sistema de traducciones propio <br>
📱 Totalmente responsive — móvil, tablet y escritorio <br>
🖼️ Imágenes en formato WebP optimizadas con preload para mejorar el LCP <br>
🗜️ Compresión Gzip y Brotli activas <br>
🚀 HTTP/2 activo <br>
📦 Caché de assets estáticos de 1 año <br>

<br>

### **Secciones de la web**
**Inicio** — Hero, Sobre mí, Resumen del equipo, Redes sociales, Contacto <br>
**Cañas de pesca** — 6 cañas premium con especificaciones completas <br>
**Carretes** — 6 carretes de competición con especificaciones completas <br>
**Accesorios** — Más de 10 accesorios esenciales <br>
**Anzuelos** — Más de 15 tipos de anzuelos premium <br>
**Hilos** — 6 tipos de hilo profesional para cada técnica <br>
**Plomos** — Selección completa para cada situación de pesca <br>

<br>

### **Formulario de contacto**
✅ Validación doble — frontend y backend <br>
✅ Detección de emails temporales y dominios falsos <br>
✅ Campo honeypot anti-bot <br>
✅ Control de tiempo mínimo de relleno (anti-bot) <br>
✅ Rate limit: 1 envío cada 30 segundos por IP <br>
✅ Rate limit: 5 envíos máximos por día por IP <br>
✅ Detección de patrones XSS <br>
✅ Detección de inyección SQL <br>
✅ Sanitización de todos los inputs <br>
✅ Validación de longitud mínima y máxima <br>
✅ Prepared statements en todas las consultas a la base de datos <br>
✅ Checkbox de aceptación de privacidad obligatorio (RGPD) <br>
✅ Contador regresivo visual <br>
✅ Doble email — notificación y confirmación <br>
✅ Versión en texto plano en todos los emails <br>

---

## 🔒 Seguridad

### **Cabeceras HTTP de seguridad — Nota A+**

| Cabecera | Protección |
|:---:|:---:|
| `Strict-Transport-Security` | Fuerza HTTPS en todos los accesos |
| `X-Frame-Options` | Protección anti-clickjacking |
| `X-Content-Type-Options` | Evita sniffing de tipos MIME |
| `X-XSS-Protection` | Filtro XSS en navegadores antiguos |
| `Referrer-Policy` | Control de información de referencia |
| `Permissions-Policy` | Geolocalización, micrófono y cámara desactivados |
| `X-Powered-By` | Eliminado — no expone tecnología del servidor |

<br>

### **Medidas adicionales**
🔐 HTTPS forzado con redirección permanente <br>
🔐 Archivo `.env` bloqueado completamente a nivel de servidor <br>
🔐 Todas las credenciales en `.env` — nunca en el código fuente <br>
🔐 Mensajes de error genéricos — no expone información interna <br>
🔐 Códigos de respuesta HTTP correctos según cada situación <br>

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

Ambos servicios se cargan de forma **condicional** tras el consentimiento.

---

## 🍪 Consentimiento de Cookies

Banner con opciones: Aceptar todo / Rechazar / Configurar <br>
3 categorías: Necesarias, Analíticas, Marketing <br>
Preferencias guardadas en cookies reales <br>
100% cumplimiento con el RGPD <br>

---

## 🔍 SEO

✅ Meta tags completos (descripción, keywords, author, robots) <br>
✅ Open Graph completo (Facebook, WhatsApp) <br>
✅ Twitter Card configurada <br>
✅ Schema.org JSON-LD (`Person` + `WebSite`) <br>
✅ Sitemap XML en Google Search Console y Bing <br>
✅ URL canónica configurada <br>
✅ Favicon en `.ico` y `.png` con múltiples tamaños <br>
✅ Contenido estático en `<noscript>` para crawlers <br>
✅ Indexado en Google y Bing <br>

---

## 🌐 Web en vivo

**[pablotcfishing.com](https://pablotcfishing.com)**

---

## 📬 Contacto

📧 [contacto@pablotcfishing.com](mailto:contacto@pablotcfishing.com) <br>
🎥 [YouTube @PabloTCFishing](https://www.youtube.com/@PabloTCFishing) <br>
📸 [Instagram @PabloTCFishing](https://instagram.com/PabloTCFishing) <br>
🎵 [TikTok @PabloTCFishing](https://tiktok.com/@PabloTCFishing) <br>

---

<sub>Hecho con pasión por la pesca deportiva 🎣</sub>

</div>

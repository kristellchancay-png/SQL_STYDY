# SQL Studio — Aprende SQL desde cero

Plataforma web interactiva en español para aprender SQL desde cero, sin backend y sin instalación.

## 🌐 Sitio en vivo

https://kristellchancay-png.github.io/SQL_STYDY/

## ✨ Qué incluye

- **9 metas / castillos** con **108 estapas** prácticas.
- Guía obligatoria por tema antes de practicar.
- **36 ejercicios de meta**, **9 quizzes** de 10 preguntas, **100 preguntas de examen** y **31 de entrevista**.
- Catálogo completo de sentencias SQL: **DQL, DML, DDL, TCL, DCL** y utilidades.
- Explicaciones con caso real, datos, consulta, resultado y lectura línea a línea.
- Motor SQL real en el navegador con **sql.js**, editor **Monaco**, gráficas con **Chart.js** y confeti.
- Progreso guardado en `localStorage` (`sqlMasterV2`).
- Certificado descargable en PDF.
- Diseño responsive, modo oscuro y accesibilidad por teclado.
- **Control de acceso por licencia** sin backend: la **meta 1 (Fundamentos) es gratis** y los 8 castillos restantes, el examen y el certificado requieren licencia.
- Códigos firmados con **ECDSA P-256** (no se pueden falsificar editando el navegador), cupones de descuento/días gratis y solicitudes de pago `PAY1`.
- **🎁 Modo abierto**: si el administrador aún no publica la configuración de licencias, el curso completo queda disponible para no bloquear el estudio.

## 🚀 Cómo abrirlo

- En GitHub Pages: entrar al sitio en vivo.
- Sin conexión: descargar `index.html` y abrirlo con doble clic en el navegador.

## 🛠️ Publicación

El sitio se sirve desde GitHub Pages usando la rama `main`, carpeta raíz (`/`).
`index.html` es un build autocontenido: no necesita servidor ni archivos adicionales.

## 🔐 Licencias y cobros

El Dueño del curso gestiona todo desde `portal-admin.html`, que se guarda **solo en su PC** (contiene la clave privada y **no debe subirse a GitHub**). Desde ese portal se pueden:

- Crear usuarios y generar sus códigos `SQL1...` firmados, con plan, duración y dispositivos.
- Renovar, revocar (eliminando al usuario) y llevar un registro de licencias emitidas.
- Generar códigos de beneficio: descuento porcentual o días gratis.
- Configurar precio, moneda, datos de transferencia bancaria y/o un enlace de pago (Mercado Pago, Stripe, PayPal).
- Importar solicitudes `PAY1` que generan los alumnos sin código, verificar el pago en el banco y aprobarlo manualmente; el portal crea al usuario y firma su licencia.
- Descargar la configuración pública y volver a inyectarla en `index.html` cuando cambien claves, precios o datos de contacto.

La verificación ocurre en el navegador del alumno: la app solo conoce la clave pública. Ningún dato bancario del alumno se envía a la app ni se guarda en el sitio.

## 🔐 Portal privado (solo administrador)

El administrador puede abrir el portal desde cualquier dispositivo en:

https://kristellchancay-png.github.io/SQL_STYDY/admin.html

Solicita un token de GitHub con acceso al repositorio privado `SQL_STYDY_ADMIN`, donde se guarda el registro de cada usuario con su licencia, cupones y cobros. El sitio público de estudiantes sigue siendo accesible sin token; el portal y las claves privadas nunca se publican en GitHub Pages.

## ✅ Estado

Build validado: 9 metas, 108 estapas, 60 ejemplos reales, 165 comprobaciones de contenido, 10 validadores automáticos, flujo administrativo de extremo a extremo y validadores activos en tiempo de ejecución.

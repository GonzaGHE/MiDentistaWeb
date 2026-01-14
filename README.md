# MiDentistaWeb - Sitio Web para Clínica Dental

Bienvenido a tu proyecto de sitio web para clínica dental. Este repositorio contiene todo el código necesario para desplegar una página web profesional, moderna y gratuita.

## 📋 Plan de Trabajo (Kanban)

Usa esta lista como tu tablero Kanban personal para seguir el progreso del proyecto.

### 🔴 Por Hacer (To Do)
- [ ] **Compra de Dominio**: Adquirir tu nombre de dominio (ej: `miclinicadental.com`) en Namecheap, GoDaddy o similar.
- [ ] **Personalización Básica**:
    - [ ] Editar `index.html` con el nombre real de la clínica.
    - [ ] Reemplazar los enlaces de WhatsApp e Instagram con los tuyos.
    - [ ] Actualizar la dirección en el mapa de Google.
- [ ] **Fotos**:
    - [ ] Reemplazar las imágenes de ejemplo con fotos reales de tu clínica y equipo (opcional pero recomendado).

### 🟡 En Progreso (In Progress)
- [x] **Estructura del Sitio**: Creación de archivos HTML, CSS y JS (Hecho por tu asistente de IA).
- [ ] **Revisión de Textos**: Leer y ajustar los textos de "Servicios" y "Nosotros" para que coincidan con tu realidad.

### 🟢 Completado (Done)
- [x] **Configuración Inicial**: Repositorio creado.

---

## 🚀 Guía de Despliegue (Cómo ponerlo en internet)

Vamos a usar **GitHub Pages**, que es gratuito, seguro y rápido.

1.  Ve a la pestaña **Settings** (Configuración) de este repositorio en GitHub.
2.  En el menú de la izquierda, baja hasta encontrar la sección **Pages**.
3.  En "Source", selecciona `Deploy from a branch`.
4.  En "Branch", selecciona `main` y la carpeta `/ (root)`.
5.  Haz clic en **Save**.
6.  Espera unos minutos y refresca la página. Verás un mensaje que dice: "Your site is live at..." con un enlace. ¡Tu web ya está online!

## 🌐 Configuración de Dominio (Tu nombre .com)

Una vez que tengas tu dominio comprado:

1.  **En tu proveedor de dominio (donde lo compraste):**
    - Busca la configuración de **DNS**.
    - Crea un registro **A** que apunte a las IPs de GitHub:
        - `185.199.108.153`
        - `185.199.109.153`
        - `185.199.110.153`
        - `185.199.111.153`
    - Crea un registro **CNAME** con el nombre `www` que apunte a `gonzaghe.github.io` (tu nombre de usuario de GitHub + .github.io).

2.  **En GitHub (Repetir pasos de despliegue):**
    - Ve a **Settings > Pages**.
    - En el campo **Custom domain**, escribe tu dominio (ej: `miclinicadental.com`).
    - Haz clic en **Save**.
    - Marca la casilla **Enforce HTTPS** (esto tardará un poco en activarse después de guardar).

---

## 🛠️ Estructura del Sitio

El sitio consta de una sola página (Landing Page) optimizada para conversión:

1.  **Inicio (Hero)**: Imagen impactante, frase principal y botón de "Pedir Cita" (WhatsApp).
2.  **Nosotros**: Breve historia y confianza.
3.  **Servicios**: Lista de tratamientos (Ortodoncia, Implantes, Blanqueamiento, etc.).
4.  **Testimonios**: Prueba social de clientes felices.
5.  **Contacto**:
    - Mapa de ubicación.
    - Botones grandes de WhatsApp e Instagram.
    - Teléfono y Horarios.

## 📞 Soporte
Si necesitas cambiar colores o agregar secciones, pide ayuda a tu asistente de IA o edita el archivo `styles.css`.
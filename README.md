# MiDentistaWeb - Sitio Web para Clínica Dental

Bienvenido a tu proyecto de sitio web para clínica dental. Este repositorio contiene todo el código necesario para desplegar una página web profesional, moderna y gratuita.

## 📸 Guía de Activos Multimedia (Checklist de Fotos)

Para personalizar tu web y que luzca profesional, necesitas recopilar las siguientes fotografías. He dejado espacios reservados (placeholders) en el código para ellas.

### 1. Identidad
- [ ] **Logo de la Clínica**: Formato PNG con fondo transparente (idealmente blanco o a color completo).

### 2. Sección "Nosotros" y Equipo
- [ ] **Foto Grupal del Equipo**: Una foto de alta calidad con los doctores y asistentes sonriendo.
- [ ] **Fotos de la Clínica**:
    - [ ] Fachada exterior (para que los pacientes reconozcan el lugar).
    - [ ] Recepción o sala de espera (para mostrar el ambiente acogedor).

### 3. Sección "Tecnología" (Calidad)
Necesitas fotos que demuestren la inversión en calidad:
- [ ] **Máquina de Blanqueamiento**: Primer plano mostrando el equipo.
- [ ] **Equipo de Rayos X / Panorámico**: Para mostrar capacidad diagnóstica.
- [ ] **Ultrasonido**: Foto del equipo de limpieza.

### 4. Sección "Casos de Éxito"
- [ ] **Casos Antes y Después**:
    - [ ] Caso 1: Blanqueamiento o Diseño de Sonrisa (Foto Antes vs. Foto Después).
    - [ ] Caso 2: Implante o rehabilitación compleja.
    *Nota: Asegúrate de tener el consentimiento de los pacientes para usar estas fotos.*

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

## 🛠️ Estructura del Sitio

El sitio consta de una sola página (Landing Page) optimizada para conversión:

1.  **Inicio (Hero)**: Imagen impactante, frase principal y botón de "Pedir Cita" (WhatsApp).
2.  **Nosotros**: Breve historia y confianza.
3.  **Tecnología**: Muestra tus equipos de vanguardia (Rayos X, Blanqueamiento, Ultrasonido).
4.  **Servicios**: Lista de tratamientos (Ortodoncia, Implantes, Blanqueamiento, etc.).
5.  **Casos de Éxito**: Galería de transformaciones reales.
6.  **Contacto**:
    - Mapa de ubicación.
    - Botones grandes de WhatsApp e Instagram.
    - Teléfono y Horarios.
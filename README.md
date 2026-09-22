# Clon 1:1 de Yo No Lo Hago (https://yonolohago.es/)

Este directorio contiene una réplica idéntica, completamente funcional y autocontenida de **[yonolohago.es](https://yonolohago.es/)**.

## 🚀 Características del Clon

- **Diseño y Maquetación 1:1**:
  - Encabezado con logotipo, menú de navegación y botón CTA *"¿Comenzamos?"*.
  - Sección Hero principal con fondo original y claim *"Tu web profesional sin preocuparte de nada"*.
  - Sección de 3 pasos (*Envío de material*, *Primera propuesta*, *Puesta en marcha*).
  - Tabla de tarifas y planes (*Landing 19€/mes*, *Completo 29€/mes*, *Tú decides* con cinta "Popular").
  - Carrusel / Muro de logotipos de clientes reales.
  - Bloques de mantenimiento y ahorro.
  - Acordeón interactivo de Preguntas Frecuentes (FAQ) completamente operativo.
  - Formulario de contacto con validación visual.
  - Botón flotante interactivo de WhatsApp (JoinChat).
  - Pie de página completo con enlaces corporativos y legales.
- **Autocontenido & Sin Dependencias Rotas**:
  - Todos los estilos CSS descargados localmente.
  - Todas las imágenes, webp, svg e iconos vectoriales guardados en local.
  - Tipografías Google Fonts (Poppins y Noto Sans) configuradas.
  - Scripts de tracking de terceros eliminados para máxima velocidad y privacidad.
- **Interacciones nativas JavaScript**:
  - Desplegado y colapsado fluido del acordeón de preguntas frecuentes.
  - Menú hamburguesa responsivo para dispositivos móviles.
  - Feedback visual al enviar el formulario de contacto.
  - Desplazamiento suave (smooth scroll) entre secciones.

---

## 💻 Cómo Ejecutarlo

### Opción 1: Abrir directamente en el navegador
Puedes hacer doble clic en `index.html` o arrastrarlo a Chrome, Edge, Safari o Firefox.

### Opción 2: Servidor local (Recomendado)
Desde esta carpeta:

**Con Python:**
```bash
python -m http.server 8080
```
Luego abre en tu navegador: [http://localhost:8080](http://localhost:8080)

**Con Node.js (npx serve):**
```bash
npx serve .
```

---

## 🌐 Cómo Desplegarlo

Este proyecto es 100% estático (HTML5, CSS3, JS). Puedes subirlo directamente a:
- **Cloudflare Pages**: Arrastrar la carpeta `yonolohago-clone`.
- **Netlify / Vercel**: `vercel deploy` o drag & drop en Netlify Drop.
- **GitHub Pages**: Subir al repositorio y activar Pages en branch main.
- **Hosting cPanel / Nginx / Apache**: Subir el contenido de la carpeta a `public_html/`.

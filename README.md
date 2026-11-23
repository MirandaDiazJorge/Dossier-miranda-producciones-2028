# Miranda Producciones — Rediseño Cinematográfico 2027

Sitio web cinematográfico premium diseñado desde cero para **Miranda Producciones** (Cineasta & Videógrafo de Bodas), con sede en Don Benito y Mérida (Extremadura), con disponibilidad nacional.

Este proyecto reemplaza la versión anterior de Wix, conservando el 100% de los contenidos, textos literales, tarifas, vídeos originales y datos de contacto, elevando radicalmente la dirección de arte y la experiencia de usuario.

---

## 🎬 Características Principales

1. **Dirección de Arte Cinematográfica:**
   - Paleta de color oscura profunda (`#080808`, `#10100f`) con acentos dorados y champaña (`#d4af37`, `#faedd7`).
   - Textura sutil de grano de película analógica (35mm film grain overlay).
   - Tipografía editorial de alta gama: **Cinzel** (titulares majestuosos) + **Playfair Display** (citas y subtítulos) + **Plus Jakarta Sans** (cuerpo de lectura limpio).
   - Márgenes amplios y respiración visual entre secciones.

2. **Portada (Hero) a Pantalla Completa:**
   - Vídeo cinematográfico 1080p en bucle de fondo con oscurecimiento suave y barras cinemascope (letterbox 2.39:1).
   - Control interactivo de audio con ecualizador animado.
   - Indicador y recomendación original: *"Para una mejor experiencia visualizar con auriculares"*.
   - Botón directo para reproducir la película en pantalla completa (Modo Cine).

3. **Portfolio & Capítulos Completos (6 Secciones Originales):**
   - **01. Las Casas** (Preparativos en casa de los novios).
   - **02. El Sí Quiero** (Ceremonia oficial).
   - **03. Recién Casados** (Sesión de exteriores íntima).
   - **04. La Celebración** (Convite y banquete).
   - **05. Barra Libre** (Baile y fiesta).
   - **06. Otra Perspectiva** (Filmaciones aéreas con dron).
   - Tarjetas con formato 16:9, miniaturas de alta resolución, duración exacta, textos íntegros y efectos hover.
   - Filtros por categoría dinámicos.

4. **Reproductor Cinema Modal Lightbox:**
   - Reproductor personalizado integrado con vídeo 1080p MP4.
   - Controles a medida: barra de progreso interactiva (seek bar), código de tiempo (00:00 / 02:10), volumen, silenciar, pantalla completa nativa y navegación fluida de siguiente/anterior capítulo.
   - Panel inferior con la descripción editorial original de cada sección.
   - Atajos de teclado: Espacio (Play/Pausa), Flechas izquierda/derecha (retroceder/avanzar 5s), Esc (Cerrar).

5. **Sobre Nosotros ("Mi Historia"):**
   - Texto biográfico original de Jorge Miranda íntegro.
   - Distintivo de "+14 Años Narrando Historias de Boda" (desde 2010).
   - Credenciales profesionales: Cobertura a 2 cámaras, piloto de dron titulado y postproducción de color/sonido master.

6. **Servicios & Tarifas (Dossier Oficial):**
   - Tarjeta destacada de **Boda Completa (1.700 €)** con desglose de servicios incluidos (2 operadores, preparativos hasta barra libre, tráiler en ~1 mes, película completa máx. 5 meses en memoria USB decorativa, 120 km incluidos desde Don Benito).
   - **Nuevo Complemento Exclusivo Destacado — Experiencia Inmersiva 360° VR (Desde 300 €):**
     - Slogan: *«No vuelvas a ver tu boda. Vuelve a estar allí».*
     - Incluye 2 Gafas VR para smartphone para reproducir el archivo 360° entregado desde el móvil.
     - 3 conceptos visuales editoriales (01 Vive el momento, 02 Cambia tu perspectiva, 03 Regresa a ese instante).
     - Lista de momentos seleccionados para grabación 360° (entrada de la novia, votos, alianzas, salida, banquete, baile, celebración).
     - Espacio técnico preparado para showreel demostrativo en 360°.
     - Botón de reserva directa «QUIERO REVIVIR MI BODA EN 360°» sincronizado con el formulario y la calculadora.
   - Grid de servicios opcionales:
     - **Filmaciones Aéreas:** 200 €
     - **Vídeo Luna de Miel (Kit GoPro):** 400 €
     - **Pre-boda:** 350 €
     - **Post-Boda:** 350 €

7. **Calculadora Interactiva de Presupuesto:**
   - Permite a las parejas configurar sus opciones en tiempo real.
   - Selector de kilómetros extra (0,30 €/km más allá de los 120 km incluidos).
   - Desglose y cálculo instantáneo.
   - Botón para aplicar el presupuesto al formulario o enviarlo directamente redactado por WhatsApp.

8. **Logística & Condiciones (FAQ):**
   - Acordeón accesible con información sobre desplazamientos, dietas del equipo, plazos y formatos de entrega, formas de pago (100 € reserva, 50% una semana antes, 50% a la entrega) y duración del filme (media orientativa ~45 min).

9. **Contacto & Formulario Completo:**
   - Teléfono directo: `696 47 70 74`
   - Correo electrónico: `miranda-producciones@hotmail.com`
   - Base en Don Benito y Mérida (Badajoz).
   - Formulario de contacto con validación de campos.
   - Botón para **Enviar directamente por WhatsApp** con todos los datos del formulario estructurados.
   - Botón flotante permanente de WhatsApp con indicador de estado en tiempo real.

---

## 📁 Estructura del Proyecto

```text
miranda-producciones/
├── index.html              # Estructura semántica HTML5, metadatos SEO y Schema.org
├── css/
│   └── style.css           # Estilos cinematográficos, tokens, animaciones y responsive
├── js/
│   └── main.js             # Motor interactivo, reproductor cine, calculadora y validación
├── assets/
│   └── img/                # Recursos gráficos y miniaturas
└── README.md               # Esta documentación
```

---

## 🚀 Cómo Ejecutar en Local desde Visual Studio Code

1. Abre la carpeta `miranda-producciones` en **Visual Studio Code**:
   ```bash
   code c:\Users\jorge\Downloads\miranda-producciones
   ```
2. Instala la extensión recomendada **Live Server** (de *Ritwick Dey*) si no la tienes.
3. Haz clic derecho sobre `index.html` y selecciona **"Open with Live Server"** (o presiona `Alt+L Alt+O`).
4. Se abrirá automáticamente en tu navegador en `http://127.0.0.1:5500`.

También puedes ejecutar un servidor local con Python o Node:
- **Python 3:** `python -m http.server 8000` -> Abre `http://localhost:8000`
- **Node / npx:** `npx serve .` o `npx http-server`

---

## 🌐 Publicación en Alojamiento Independiente

Al ser un desarrollo con **HTML5, CSS3 y JavaScript vanilla** (sin dependencias de Wix, PHP ni bases de datos), puedes publicarlo en cualquier alojamiento:

- **Netlify:** Arrastra la carpeta `miranda-producciones` a [app.netlify.com/drop](https://app.netlify.com/drop) y tendrás la web online en segundos con certificado SSL gratis.
- **Vercel:** Ejecuta `npx vercel` o conecta el repositorio de GitHub.
- **GitHub Pages:** Sube los archivos a la rama `main` o `gh-pages`.
- **Hosting Tradicional (cPanel / Apache / Nginx):** Sube el contenido al directorio `public_html` mediante FTP/SFTP.

---

## ✉️ Conexión del Formulario a Producción

Para recibir los mensajes del formulario directamente en tu email sin programar un backend:
- **Formspree:** Regístrate gratis en [formspree.io](https://formspree.io), crea un endpoint y cambia el atributo `action="https://formspree.io/f/TU_ID"` y `method="POST"` en la etiqueta `<form>` de `index.html`.
- **WhatsApp Directo:** Ya está integrado y operativo sin configuración adicional.

# Práctica Formativa Obligatoria 1 - Landing Page de Portafolio Personal

**Descripción del Proyecto:**
Este proyecto es la Práctica Formativa Obligatoria 1 para la materia Desarrollo de Sistemas Web (Front End) del IFTS N°29. 
Consiste en una Landing Page estática construida con HTML5 y CSS. Funciona como un portafolio personal y profesional, con secciones que detallan proyectos académicos realizados, habilidades técnicas y blandas, películas favoritas y un formulario de contacto, con un diseño totalmente responsivo y enfocado en la experiencia de usuario (UX).

**URL del Proyecto Publicado en Vercel:** https://pfo1-frontend-tec-ds.vercel.app  
**URL del Repositorio de GitHub:** https://github.com/IvanaZandona/PFO1-FrontEnd-TecDS

---

## Checklist - Práctica Formativa Obligatoria 1

### Estructura del Proyecto:
- [x] Archivo "index.html" ubicado en la raíz.
- [x] Carpeta "css" que contenga el archivo "styles.css".
- [x] (Opcional) Carpeta "img" para recursos gráficos.
- [x] Archivo "README.md" creado, que incluya una breve descripción del TP y este checklist.

### Repositorio y Publicación:
- [x] Repositorio en GitHub creado.
- [x] Proyecto subido al repositorio.
- [x] Proyecto publicado utilizando Vercel.
- [x] En el "README.md" se indica la URL de Vercel.

### Uso de Google Fonts:
- [x] Enlace a Google Fonts incluido en la sección "head" del HTML.
- [x] La tipografía importada se aplica en el sitio.
- [x] Redacta brevemente tu decisión: ¿Por qué elegiste esa fuente?
**Respuesta:** Elegí la tipografía "Inter" porque fue diseñada para pantallas de computadora, lo que garantiza una legibilidad excelente en cualquier dispositivo. Tiene un diseño limpio y minimalista que transmite una estética tecnológica profesional, alineándose perfectamente con el perfil de este portafolio.

### HTML:
- [x] El documento inicia con la declaración DOCTYPE y usa el atributo lang="es".
- [x] Se han incluido las metaetiquetas obligatorias: charset y viewport.
- [x] Se ha definido un título descriptivo.
- [x] Se han vinculado correctamente el archivo CSS y el enlace a Google Fonts.

**Secciones obligatorias en "main":**
- [x] Barra de navegación ("nav") presente y contiene al menos 3 enlaces.
- [x] Se han insertado al menos 4 comentarios explicativos en el código HTML.

### CSS:
- [x] Existe el archivo "styles.css" con estilos personalizados.
- [x] Se utilizan selectores basados en clases e identificadores.
- [x] La tipografía importada desde Google Fonts se aplica correctamente en todos los elementos.

**Layout y Organización:**
- [x] Se ha organizado el layout (especialmente en la sección "tarjetas") utilizando Flexbox o Grid.
- [x] Redacta: ¿Qué ventajas encontraste al utilizar Flexbox o Grid en tu proyecto?
**Respuesta:** Utilizar CSS Grid en la sección de tarjetas representa una ventaja enorme para la responsividad. Aplicando la regla `grid-template-columns: repeat(auto-fit, minmax(280px, 1fr))` logré que las tarjetas se adapten dinámicamente al ancho de la pantalla sin necesidad de escribir múltiples *media queries*. Además, utilicé Flexbox en el encabezado y la barra de navegación, lo que permitió centrar y distribuir los elementos rápidamente.

**Estilización de Componentes:**
- [x] Se han personalizado los estilos de tablas, botones, enlaces y formularios.
- [x] Se han ajustado las dimensiones de imágenes y contenedores utilizando unidades relativas (%, rem, vh).
- [x] Se ha implementado al menos una animación o transición (por ejemplo, efecto hover en tarjetas o botones).
- [x] Redacta: ¿Qué animación o transición implementaste y por qué consideraste que era adecuada para tu proyecto?
**Respuesta:** Implementé un efecto dinámico de borde que se dibuja alrededor de las tarjetas al realizar la acción de `:hover`. Lo logré manipulando el ancho y alto de los pseudo-elementos `::before` y `::after` junto con la propiedad `transition` y sumé una transición suave en el `box-shadow`. Lo consideré adecuado porque aporta un detalle moderno y sofisticado, sin caer en el clásico efecto de escalar (`transform: scale`) que a nivel UX puede confundir al usuario haciéndole creer que toda la tarjeta es un botón clickeable. También, implementé un efecto al hacer `:focus` en los input y el texarea del formulario.  

### Consideraciones Adicionales:
- [x] El diseño es responsivo y se visualiza correctamente en distintos dispositivos.
- [x] Se aplicaron buenas prácticas de accesibilidad (por ejemplo, uso adecuado de atributos alt en las imágenes).
- [x] Se añadieron comentarios adicionales donde se describan decisiones de diseño o la lógica de implementación.
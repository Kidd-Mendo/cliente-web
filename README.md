# Portafolio Web - Joan Mendoza

Proyecto educativo de desarrollo web que demuestra los fundamentos de HTML5, CSS3 y diseño responsivo con Flexbox.

## Descripción del Proyecto

Este es un portafolio personal web desarrollado como ejercicio de aprendizaje en Ingeniería de Software. El proyecto implementa conceptos clave de desarrollo frontend incluyendo:

- **Estructura Semántica HTML5**: Uso correcto de etiquetas semánticas
- **Estilizado CSS3**: Aplicación de estilos modernos y efectivos
- **Modelo de Caja**: Comprensión del box model de CSS
- **Flexbox**: Diseño flexible y responsivo con CSS Flexbox

## Características

✅ **Responsive**: Diseño adaptable a diferentes tamaños de pantalla  
✅ **Moderno**: Uso de CSS3 y HTML5 semántico  
✅ **Fácil de personalizar**: Estructura clara y bien documentada  
✅ **Accesible**: Marcado HTML semántico  

## Estructura del Proyecto

```
Taller1/
├── index.html          # Estructura HTML del portafolio
├── styles.css          # Estilos CSS del proyecto
├── EJECUCIÓN.md        # Guía detallada de ejecución
├── README.md           # Este archivo
└── .gitignore          # Archivo de configuración Git
```

## Contenido

### Header (Encabezado)
- Nombre del estudiante: Joan Mendoza
- Descripción: Estudiante de Ingeniería de Software

### Secciones Principales
1. **Sobre mí**: Descripción personal y áreas de interés
2. **Mis Habilidades**: Lista interactiva de competencias técnicas
   - HTML5
   - CSS3
   - JavaScript
   - Flexbox

## Requisitos

- Navegador web moderno (Chrome, Firefox, Edge, Safari)
- No requiere instalación adicional

## Cómo Usar

### Opción 1: Abrir directamente (Más Simple)
1. Navega a la carpeta `Taller1/`
2. Haz doble clic en `index.html`
3. El navegador abrirá automáticamente

### Opción 2: Usar un Servidor Local (Recomendado)

#### Con Python 3:
```bash
cd Taller1
python -m http.server 8000
```
Luego abre en tu navegador: `http://localhost:8000`

#### Con Node.js (http-server):
```bash
npm install -g http-server
cd Taller1
http-server
```

#### Con VS Code (Live Server):
1. Instala la extensión "Live Server" en VS Code
2. Haz clic derecho en `index.html`
3. Selecciona "Open with Live Server"

### Opción 3: Publicar con GitHub Pages
1. Crea un repositorio en GitHub
2. Sube los archivos del proyecto
3. Ve a Settings > Pages
4. Selecciona la rama (main o master) como fuente
5. Tu sitio estará disponible en: `https://tuusuario.github.io/nombre-repo/`

## Personalización

### Cambiar el nombre
Edita `index.html` y busca:
```html
<h1>Hola, soy Joan Mendoza</h1>
```
Reemplaza "Joan Mendoza" por tu nombre.

### Agregar más habilidades
En la sección de habilidades, añade nuevos `<li>`:
```html
<li>Tu Habilidad</li>
```

### Cambiar colores
Edita `styles.css` y modifica los valores de color. Por ejemplo:
- `#2c3e50`: Color del header (azul oscuro)
- `#f4f7f6`: Color de fondo (gris claro)

### Agregar más secciones
Duplica la estructura de `<section class="contenedor">` y personaliza el contenido.

## Conceptos Aprendidos

| Concepto | Descripción |
|----------|-------------|
| **HTML Semántico** | Uso correcto de etiquetas `<header>`, `<section>`, `<nav>` |
| **Box Model** | Margin, padding, border y content |
| **Flexbox** | Alineación y distribución flexible de elementos |
| **CSS Selectores** | Clases, IDs y selectores de elemento |
| **Responsive Design** | Adaptación a diferentes tamaños de pantalla |

## Troubleshooting

### El archivo CSS no carga
- ✅ Verifica que `styles.css` esté en la misma carpeta que `index.html`
- ✅ Comprueba que el nombre sea exactamente `styles.css`
- ✅ Recarga la página: `Ctrl+Shift+R` o `Cmd+Shift+R`

### Los estilos no se aplican
- Limpia el caché del navegador
- Verifica que la etiqueta `<link>` en HTML sea correcta
- Revisa la consola del navegador (F12) para errores

### Flexbox no funciona
- Usa navegadores modernos
- Verifica que `display: flex;` esté presente

## Próximos Pasos de Aprendizaje

Después de dominar este proyecto, puedes aprender:

1. **Responsive Design**: Media queries y layout adaptable
2. **CSS Grid**: Sistema de rejillas avanzado
3. **JavaScript**: Interactividad y dinamismo
4. **Frameworks**: Bootstrap, Tailwind CSS
5. **Backend**: Node.js, Python, bases de datos
6. **Versionado**: Git y GitHub

## Autor

- **Nombre**: Joan Mendoza
- **Carrera**: Ingeniería de Software
- **Estado**: En desarrollo 🚀

## Licencia

Este proyecto es educativo y está disponible para uso académico y personal.

## Recursos Útiles

- [MDN Web Docs - HTML](https://developer.mozilla.org/es/docs/Web/HTML)
- [MDN Web Docs - CSS](https://developer.mozilla.org/es/docs/Web/CSS)
- [CSS Tricks - Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Can I Use - Browser Compatibility](https://caniuse.com/)

## Historial de Cambios

Ver [EJECUCIÓN.md](EJECUCIÓN.md) para la guía de ejecución y desarrollo.

---

**Última actualización**: Abril 2026  
**Versión**: 1.0.0

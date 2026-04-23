# Guía de Ejecución - Proyecto Web

## Cómo Ejecutar los Proyectos

### Opción 1: Abrir directamente en el navegador (Más Simple)

1. Navega a la carpeta del proyecto (ej: `Taller1/`)
2. Haz doble clic en el archivo `index.html`
3. El navegador abrirá automáticamente el proyecto

### Opción 2: Usar un servidor local (Recomendado)

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

### Opción 3: Con Git y GitHub Pages (Para publicar)

1. Crea un repositorio en GitHub
2. Sube los archivos al repositorio
3. Ve a Settings > Pages
4. Selecciona la rama (main o master) como fuente
5. Tu sitio estará disponible en: `https://tuusuario.github.io/nombre-repo/`

## Verificación

Al ejecutar el proyecto deberías ver:
- ✅ Header azul oscuro con el nombre "Joan Mendoza"
- ✅ Descripción: "Estudiante de Ingeniería de Software"
- ✅ Sección "Sobre mí" con contenido
- ✅ Botón "Contactar" (funcional con estilos CSS)
- ✅ Lista de habilidades alineadas horizontalmente con Flexbox

## Editando el Proyecto

Para realizar cambios:
1. Abre `index.html` en tu editor de código favorito
2. Modifica el contenido HTML
3. Los cambios se reflejarán al guardar y recargar el navegador

### Cambios Comunes:

**Cambiar el nombre:**
Busca `<h1>Hola, soy Joan Mendoza</h1>` y reemplaza "Joan Mendoza" por tu nombre

**Agregar más habilidades:**
Añade `<li>Tu Habilidad</li>` dentro de la lista `<ul class="habilidades">`

**Cambiar colores:**
Edita `styles.css` y modifica los valores de color (ej: `#2c3e50`)

## Troubleshooting

### El archivo CSS no carga
- Verifica que `styles.css` esté en la misma carpeta que `index.html`
- Comprueba que el nombre sea exactamente `styles.css` (sin mayúsculas)

### Los estilos no se aplican
- Limpia el caché del navegador: `Ctrl+Shift+R` (o `Cmd+Shift+R` en Mac)
- Asegúrate de que la etiqueta `<link>` en HTML sea correcta

### Flexbox no funciona
- Usa navegadores modernos (Chrome, Firefox, Edge, Safari)
- Verifica que `display: flex;` esté en `.habilidades`

## Próximos Pasos

Una vez domines estos conceptos, puedes aprender:
- Responsive Design (Media Queries)
- CSS Grid
- JavaScript interactivo
- Frameworks como Bootstrap o Tailwind

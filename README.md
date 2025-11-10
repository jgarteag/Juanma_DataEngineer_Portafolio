# 🖥️ Portafolio Personal - Juan Manuel Guerrero

Portafolio profesional de Data Engineer con diseño minimalista estilo Mac OS clásico.

## ✨ Características

- 🎨 Diseño Mac OS clásico minimalista
- 🌍 Bilingüe (Español/Inglés)
- 📱 Responsive (móvil, tablet, desktop)
- ♿ Accesible (WCAG 2.1 AA)
- ⚡ Rápido (HTML/CSS puro)
- 🎭 Animaciones elegantes
- 💾 Sin dependencias

## 🚀 Despliegue en GitHub Pages

### Paso 1: Crear Repositorio en GitHub

1. Ve a [GitHub](https://github.com) e inicia sesión
2. Click en el botón **"+"** (arriba derecha) → **"New repository"**
3. Configura el repositorio:
   - **Repository name:** `portfolio` (o el nombre que prefieras)
   - **Description:** "Mi portafolio profesional"
   - **Public** ✅ (debe ser público para GitHub Pages gratis)
   - **NO** marques "Add a README file"
4. Click en **"Create repository"**

### Paso 2: Subir tu Código

Abre la terminal en la carpeta de tu proyecto y ejecuta:

```bash
# Inicializar repositorio Git
git init

# Añadir todos los archivos
git add .

# Hacer el primer commit
git commit -m "Initial commit: Portfolio with Mac OS design"

# Renombrar rama a main
git branch -M main

# Conectar con tu repositorio de GitHub
# Reemplaza 'tuusuario' con tu nombre de usuario de GitHub
git remote add origin https://github.com/tuusuario/portfolio.git

# Subir el código
git push -u origin main
```

### Paso 3: Activar GitHub Pages

1. Ve a tu repositorio en GitHub
2. Click en **"Settings"** (arriba)
3. En el menú lateral, click en **"Pages"**
4. En **"Source"**, selecciona:
   - Branch: **main**
   - Folder: **/ (root)**
5. Click en **"Save"**
6. Espera 1-2 minutos

### Paso 4: ¡Listo! 🎉

Tu portafolio estará disponible en:
```
https://tuusuario.github.io/portfolio/
```

## 🌐 Añadir Dominio Personalizado (Opcional)

### Opción 1: Dominio Gratuito de GitHub

Tu sitio ya está en: `tuusuario.github.io/portfolio`

### Opción 2: Dominio Personalizado

1. **Compra un dominio** (ej: juanmaguerrero.com)
   - Recomendados: Namecheap, Google Domains, GoDaddy

2. **Configura DNS** en tu proveedor de dominio:
   ```
   Tipo: A
   Host: @
   Valor: 185.199.108.153
   
   Tipo: A
   Host: @
   Valor: 185.199.109.153
   
   Tipo: A
   Host: @
   Valor: 185.199.110.153
   
   Tipo: A
   Host: @
   Valor: 185.199.111.153
   
   Tipo: CNAME
   Host: www
   Valor: tuusuario.github.io
   ```

3. **En GitHub Pages Settings:**
   - Añade tu dominio en "Custom domain"
   - Marca "Enforce HTTPS"
   - Espera 24-48 horas para propagación DNS

## 📁 Estructura del Proyecto

```
portfolio/
├── index.html          # Página principal
├── styles.css          # Estilos Mac OS
├── assets/
│   └── cv.pdf         # Tu CV
├── README.md          # Este archivo
└── .gitignore         # Archivos ignorados por Git
```

## 🛠️ Tecnologías

- HTML5
- CSS3 (Variables CSS, Grid, Flexbox)
- JavaScript (Vanilla)
- SVG (Logos minimalistas)

## 🎨 Personalización

### Cambiar Colores

Edita las variables CSS en `styles.css`:

```css
:root {
  --color-bg: #ECECEC;
  --color-text: #000000;
  --color-accent: #000000;
  /* ... más variables */
}
```

### Actualizar Contenido

Todo el contenido está en `index.html`. Las traducciones están en el objeto `translations` dentro del `<script>`.

### Cambiar CV

Reemplaza el archivo `assets/cv.pdf` con tu CV actualizado.

## 📊 Características Técnicas

- **Performance:** < 100KB total
- **Accesibilidad:** WCAG 2.1 AA
- **SEO:** Optimizado con meta tags
- **Responsive:** Mobile-first design
- **Navegadores:** Chrome, Firefox, Safari, Edge

## 🔄 Actualizar el Sitio

Cada vez que hagas cambios:

```bash
# Añadir cambios
git add .

# Commit con mensaje descriptivo
git commit -m "Actualizar experiencia laboral"

# Subir a GitHub
git push

# GitHub Pages se actualiza automáticamente en 1-2 minutos
```

## 📝 Licencia

Este proyecto es de uso personal. Siéntete libre de usarlo como inspiración para tu propio portafolio.

## 👤 Autor

**Juan Manuel Guerrero**
- LinkedIn: [linkedin.com/in/juanmagart](https://www.linkedin.com/in/juanmagart)
- GitHub: [github.com/tuusuario](https://github.com/tuusuario)

---

**Hecho con ❤️ y diseño Mac OS clásico**

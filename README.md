# � Portfoflio - Juan Manuel Guerrero

Professional portfolio showcasing my experience as a Data Engineer, built with a minimalist Mac OS classic design.

> 🌐 **Live Site:** [jgarteag.github.io/Juanma_DataEngineer_Portafolio](https://jgarteag.github.io/Juanma_DataEngineer_Portafolio/)

---

## ✨ Features

- 🎨 **Mac OS Classic Design** - Minimalist and elegant interface
- 🌍 **Bilingual** - Spanish/English language switcher
- 📱 **Fully Responsive** - Optimized for mobile, tablet, and desktop
- ♿ **Accessible** - WCAG 2.1 AA compliant
- ⚡ **Fast Loading** - Pure HTML/CSS/JavaScript, no frameworks
- 🎭 **Smooth Animations** - Typewriter effect and subtle transitions
- 💾 **Zero Dependencies** - Lightweight and performant
- 🔒 **Secure** - Static site with no backend vulnerabilities

## 🚀 Quick Start

### View Online
Visit the live portfolio at: **[jgarteag.github.io/Juanma_DataEngineer_Portafolio](https://jgarteag.github.io/Juanma_DataEngineer_Portafolio/)**

### Run Locally
```bash
# Clone the repository
git clone https://github.com/jgarteag/Juanma_DataEngineer_Portafolio.git

# Navigate to the directory
cd Juanma_DataEngineer_Portafolio

# Open in browser
open index.html
# or simply double-click index.html
```

---

## 🛠️ Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom properties, Grid, Flexbox
- **JavaScript** - Vanilla JS for interactivity
- **SVG** - Minimalist company logos

---

## 📂 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # Mac OS themed styles
├── assets/
│   └── cv.pdf         # Resume/CV
├── README.md          # Documentation
└── .gitignore         # Git ignore rules
```

---

## 🎨 Customization

### Change Colors
Edit CSS variables in `styles.css`:
```css
:root {
  --color-bg: #ECECEC;
  --color-text: #000000;
  --color-accent: #000000;
}
```

### Update Content
All content is in `index.html`. Translations are in the `translations` object within the `<script>` tag.

### Replace CV
Replace `assets/cv.pdf` with your updated resume.

---

## 🌐 Deployment on GitHub Pages

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

## � Pereformance

- **Page Size:** < 100KB (excluding fonts)
- **Load Time:** < 1s
- **Lighthouse Score:** 95+
- **Accessibility:** WCAG 2.1 AA

---

## 🤝 Contributing

This is a personal portfolio project, but feel free to:
- Fork it for your own portfolio
- Report issues
- Suggest improvements

---

## 📄 License

This project is open source and available for personal use. Feel free to use it as inspiration for your own portfolio.

---

## 👤 Author

**Juan Manuel Guerrero**
- 💼 Data Engineer
- 🔗 LinkedIn: [linkedin.com/in/juanmagart](https://www.linkedin.com/in/juanmagart)
- 🐙 GitHub: [@jgarteag](https://github.com/jgarteag)
- 🌐 Portfolio: [jgarteag.github.io/Juanma_DataEngineer_Portafolio](https://jgarteag.github.io/Juanma_DataEngineer_Portafolio/)

---

## 🙏 Acknowledgments

- Design inspired by classic Mac OS interface
- Built with modern web standards
- Optimized for performance and accessibility

---

<div align="center">

**Made with ❤️ and Mac OS classic design**

⭐ Star this repo if you like it!

</div>

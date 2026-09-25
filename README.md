# carta-carrito

Proyecto web para el restaurante **"El Desvío"**, una carta digital interactiva con panel de administración para gestión de productos.

---

## 📖 Descripción general

Esta aplicación consiste en un sitio web de carta/menu para un restaurante de comida rápida, desarrollado con tecnologías web modernas. El proyecto incluye:

- **Frontend** interactivo con animaciones y diseño responsive
- **Panel de administración** para gestionar productos de la carta
- **Integración con Firebase** para autenticación y base de datos en tiempo real
- **Dominio personalizado** configurado (eldesvio.xyz)

---

## 📁 Estructura del proyecto

| Archivo | Descripción |
|---------|-------------|
| `index.html` | Página principal de la carta/menu del restaurante. Contiene la estructura HTML, enlaces a fuentes y estilos, y el contenedor de la lógica principal. |
| `style.css` | Hoja de estilos CSS con diseño responsive, animaciones, tipografía personalizada (Montserrat, Nunito) y estilos para el footer con información de contacto. |
| `app.js` | Lógica principal del lado del cliente. Maneja la interacción con Firebase, renderizado de la carta y funcionalidades del frontend. |
| `admin.html` | Panel de control para dueños del restaurante. Incluye sección de login y panel de administración de productos. |
| `admin.js` | Lógica del panel de administración. Utiliza Firebase Authentication y Firestore para autenticación de usuarios, carga y gestión de productos por categoría, con ordenamiento por precio. |
| `CNAME` | Archivo de configuración de dominio que apunta el repositorio a `eldesvio.xyz`. |

---

## 🛠️ Tecnologías utilizadas

- **HTML5** - Estructura semántica de las páginas
- **CSS3** - Estilos, diseño responsive, animaciones y Flexbox
- **JavaScript (ES6+)** - Programación modular con `import/export`
- **Firebase** - 
  - `firebase/auth` - Autenticación de usuarios (login/logout)
  - `firebase/firestore` - Base de datos NoSQL para productos de la carta
- **Google Fonts** - Montserrat y Nunito para tipografía
- **Responsive Design** - Adaptación a móviles, tablets y desktop

---

## ▶️ Cómo ejecutar el proyecto

1. **Clona el repositorio:**
   ```bash
   git clone <tu-repositorio>
   cd carta-carrito
   ```

2. **Abre el proyecto:**
   - Simplemente abre `index.html` en tu navegador preferido.
   - O utiliza la extensión "Live Server" de VS Code para una experiencia completa.

3. **Panel de administración:**
   - Accede a `admin.html` en tu navegador.
   - Necesitarás credenciales de Firebase para iniciar sesión (configured en `admin.js`).
   - Una vez logueado, podrás ver y gestionar los productos de la carta.

---

## 🌐 Despliegue

El proyecto está listo para desplegar en cualquier servicio de hosting estático:

- **GitHub Pages**: Sube los archivos y habilita la rama `main` / master con el origen `docs/` o la raíz.
- **Vercel / Netlify**: Conecta el repositorio y el sitio se desplegará automáticamente.
- **Dominio personalizado**: El archivo `CNAME` ya está configurado para `eldesvio.xyz`.

---

## 👤 Autor

**Tito**
- Correo: `pedrotitojerial@gmail.com`
- Proyecto: [github/tu-usuario/carta-carrito](https://github.com/tu-usuario/carta-carrito)

---
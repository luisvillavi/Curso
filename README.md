# UTCJ - Landing Page de Servicios Tecnológicos y Educación Continua

Una landing page moderna y responsive para la Universidad Tecnológica de Ciudad Juárez, diseñada para mostrar sus servicios tecnológicos y programas de educación continua.

## 🎨 Características

- **Diseño Moderno**: Inspirado en Tailwind CSS con estilos limpios y profesionales
- **Totalmente Responsive**: Optimizada para dispositivos móviles, tablets y desktop
- **Animaciones Interactivas**: Efectos de scroll, contadores animados y transiciones suaves
- **Formulario de Contacto**: Con validación en tiempo real y notificaciones
- **Navegación Suave**: Scroll automático a secciones con offset para header fijo
- **Colores Institucionales**: Basados en la identidad visual de la UTCJ

## 🚀 Tecnologías Utilizadas

- **HTML5**: Estructura semántica y accesible
- **CSS3**: Estilos modernos con CSS Grid, Flexbox y variables CSS
- **JavaScript ES6+**: Interactividad y animaciones
- **Font Awesome**: Iconografía profesional
- **Google Fonts**: Tipografía Inter para mejor legibilidad

## 📁 Estructura del Proyecto

```
utcj-landing-page/
├── index.html              # Página principal
├── styles.css              # Estilos CSS
├── script.js               # Funcionalidades JavaScript
├── logo-utcj.png           # Logo institucional UTCJ (imagen)
├── generate-test-images.html # Generador de imágenes de prueba
├── README.md               # Documentación del proyecto
└── images/                 # Directorio de imágenes
    ├── estudiantes-laboratorio.jpg
    ├── robotica-industrial.jpg
    ├── estudiantes-proyecto.jpg
    ├── capacitacion-taller.jpg
    ├── capacitacion-grupo.jpg
    ├── cnc-operacion.jpg
    ├── estudiantes-presentacion.jpg
    ├── capacitacion-software.jpg
    └── automatizacion-sistema.jpg
```

## 🎯 Secciones de la Landing Page

### 1. Header
- Navegación fija con efecto de transparencia
- Menú hamburguesa para dispositivos móviles
- Logo institucional UTCJ (imagen)
- Slogan: "La Universidad de la industria"

### 2. Hero Section
- Título principal con animación de escritura
- Llamadas a la acción
- Tarjeta informativa con efecto glassmorphism
- Efecto parallax

### 3. Servicios Tecnológicos
- 6 tarjetas de servicios principales con imágenes integradas:
  - Microelectrónica y Semiconductores (estudiantes en laboratorio)
  - Mecatrónica y Automatización (brazo robótico industrial)
  - Tecnologías de la Información (estudiantes desarrollando proyecto)
  - Energía y Desarrollo Sustentable (capacitación en taller)
  - Logística Internacional (grupo en capacitación)
  - Mantenimiento Industrial (operación de máquina CNC)

### 4. Educación Continua
- Certificaciones Profesionales (estudiantes presentando)
- Capacitación Empresarial (capacitación en software)
- Cursos Técnicos (sistema de automatización)
- Call-to-action para solicitar información

### 5. Estadísticas
- Contadores animados con datos institucionales
- 15 Carreras Profesionales
- 5000 Estudiantes Activos
- 95% de Empleabilidad
- 200 Empresas Vinculadas
- Imagen de fondo con estudiantes en laboratorio

### 6. Contacto
- Información de contacto institucional
- Formulario de contacto con validación
- Ubicación, teléfono y email

### 7. Footer
- Enlaces rápidos
- Redes sociales
- Información institucional

## 🎨 Paleta de Colores

```css
--primary-color: #00805F;    /* Verde institucional exacto del logo */
--secondary-color: #f59e0b;  /* Dorado */
--accent-color: #dc2626;     /* Rojo */
--dark-color: #1f2937;       /* Gris oscuro */
--light-color: #f8fafc;      /* Gris claro */
```

## ⚡ Funcionalidades JavaScript

### Navegación
- Menú móvil con animación hamburguesa
- Header con efecto de scroll
- Navegación suave entre secciones

### Animaciones
- Contadores animados al hacer scroll
- Efectos de entrada para elementos
- Animación de escritura en el título
- Efecto parallax en el hero

### Formulario
- Validación en tiempo real
- Notificaciones de éxito/error
- Simulación de envío

### Efectos Visuales
- Partículas flotantes en el hero
- Hover effects en tarjetas
- Transiciones suaves

## 📱 Responsive Design

La landing page está optimizada para:

- **Desktop**: 1200px+
- **Tablet**: 768px - 1199px
- **Mobile**: 320px - 767px

### Breakpoints
```css
@media (max-width: 768px) { /* Tablet y Mobile */ }
@media (max-width: 480px) { /* Mobile pequeño */ }
```

## 🚀 Instalación y Uso

1. **Clonar o descargar** los archivos del proyecto
2. **Descargar las imágenes de prueba**:
   - Abre `generate-test-images.html` en tu navegador
   - Descarga todas las imágenes y colócalas en la carpeta `images/`
3. **Abrir** `index.html` en tu navegador web
4. **¡Listo!** La página está lista para usar

### 📸 Imágenes de Prueba

El archivo `generate-test-images.html` contiene un generador de imágenes de prueba que te permite:
- Ver todas las imágenes necesarias para la página
- Descargar cada imagen con el nombre correcto
- Obtener instrucciones sobre el tipo de contenido que debe tener cada imagen

**Imágenes requeridas:**
- `estudiantes-laboratorio.jpg` - Estudiantes trabajando en laboratorios
- `robotica-industrial.jpg` - Brazos robóticos industriales
- `estudiantes-proyecto.jpg` - Estudiantes desarrollando proyectos
- `capacitacion-taller.jpg` - Personas en talleres de capacitación
- `capacitacion-grupo.jpg` - Grupos de profesionales en capacitación
- `cnc-operacion.jpg` - Operación de máquinas CNC
- `estudiantes-presentacion.jpg` - Estudiantes presentando proyectos
- `capacitacion-software.jpg` - Capacitación en software especializado
- `automatizacion-sistema.jpg` - Sistemas de automatización industrial

### Para desarrollo:
```bash
# Si tienes Python instalado
python -m http.server 8000

# Si tienes Node.js instalado
npx serve .

# Si tienes PHP instalado
php -S localhost:8000
```

## 🔧 Personalización

### Cambiar Colores
Edita las variables CSS en `styles.css`:
```css
:root {
    --primary-color: #tu-color;
    --secondary-color: #tu-color;
    /* ... */
}
```

### Agregar Servicios
Modifica la sección de servicios en `index.html`:
```html
<div class="service-card">
    <div class="service-icon">
        <i class="fas fa-tu-icono"></i>
    </div>
    <h3>Tu Servicio</h3>
    <p>Descripción del servicio</p>
    <a href="#" class="service-link">Saber más <i class="fas fa-arrow-right"></i></a>
</div>
```

### Modificar Estadísticas
Actualiza los valores en `index.html`:
```html
<div class="stat-number" data-target="tu-numero">0</div>
```

## 🚀 Despliegue en Vercel

### Opción 1: Despliegue Directo (Recomendado)
1. Ve a [vercel.com](https://vercel.com) y crea una cuenta
2. Haz clic en "New Project"
3. Sube tu carpeta del proyecto arrastrándola
4. Vercel detectará automáticamente que es un sitio estático
5. Haz clic en "Deploy"

### Opción 2: Usando Vercel CLI
```bash
# Instalar Vercel CLI
npm install -g vercel

# Inicializar y desplegar
vercel

# Para despliegues futuros
vercel --prod
```

### Opción 3: Desde GitHub
1. Sube tu código a GitHub
2. Conecta tu repositorio en Vercel
3. Cada push a `main` se desplegará automáticamente

### Configuración
El proyecto incluye:
- `vercel.json` - Configuración optimizada para Vercel
- `.gitignore` - Archivos excluidos del despliegue
- Headers de caché para mejor rendimiento

## 📞 Información de Contacto

**Universidad Tecnológica de Ciudad Juárez**
- **Dirección**: Av. Universidad Tecnológica No. 3051, Col. Lote Bravo II, Cd. Juárez, Chih.
- **Teléfono**: 649.0600
- **Email**: info@utcj.edu.mx
- **Sitio Web**: [www.utcj.edu.mx](https://www.utcj.edu.mx/)

## 🎓 Carreras Profesionales

La UTCJ ofrece las siguientes carreras:

### Ingenierías
- Ing. en Energía y Desarrollo Sustentable
- Ing. en Logística Internacional
- Ing. en Mantenimiento Industrial
- Ing. en Mecatrónica
- Ing. en Nanotecnología
- Ing. Industrial
- Ing. en Tecnologías de la Información e Innovación Digital
- Ing. en Microelectrónica y Semiconductores

### Licenciaturas
- Lic. en Negocios y Mercadotecnia
- Lic. en Contaduría
- Lic. en Protección Civil
- Lic. en Terapia Física

### Posgrados
- Especialidad en Semiconductores
- Maestría en Ingeniería de Sistemas Industriales Sustentables
- Maestría en Logística y Negocios Sustentables

## 🤝 Contribuciones

Este proyecto está diseñado específicamente para la Universidad Tecnológica de Ciudad Juárez. Para sugerencias o mejoras, contacta directamente con la institución.

## 📄 Licencia

Este proyecto es propiedad de la Universidad Tecnológica de Ciudad Juárez. Todos los derechos reservados.

---

**Desarrollado con ❤️ para la UTCJ** 
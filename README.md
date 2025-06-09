# Aero4
# Aero4 - Página Web Profesional de Servicios de Drones

## Descripción del Proyecto

Página web profesional para **Aero4**, empresa especializada en servicios de grabación aérea con drones y postproducción. El sitio web presenta una imagen moderna y profesional que refleja la calidad de los servicios ofrecidos, manteniendo precios competitivos como freelance en crecimiento.

## Características Principales

### ✨ Diseño y Experiencia de Usuario
- **Diseño moderno y profesional** con colores que coinciden con el logo (azul cian/turquesa)
- **Totalmente responsivo** - se adapta perfectamente a dispositivos móviles, tablets y desktop
- **Animaciones suaves** y efectos visuales que mejoran la experiencia del usuario
- **Navegación intuitiva** con menú sticky y transiciones fluidas
- **Tipografía optimizada** para legibilidad en todos los dispositivos

### 🎯 Contenido Estratégico
- **Página de inicio** con presentación clara de la empresa y servicios
- **Sección "¿Qué puedes ofrecer a ese precio?"** destacando el valor del servicio
- **Sección "Claves para justificar ese precio"** explicando las ventajas competitivas
- **Página de servicios detallada** con información sobre:
  - Vuelo de dron profesional (precio variable según objetivo y tiempo)
  - Edición y postproducción (precio variable según material y tomas)
  - Opción de contratar servicios por separado
- **Página de contacto** con formulario funcional y información de contacto

### 🛠️ Tecnologías Utilizadas
- **React 19** - Framework principal
- **Vite** - Herramienta de desarrollo y build
- **Tailwind CSS** - Framework de estilos
- **shadcn/ui** - Componentes de interfaz de usuario
- **Lucide React** - Iconos modernos
- **React Router DOM** - Enrutamiento de páginas
- **Framer Motion** - Animaciones (preparado para uso futuro)

### 📱 Características Técnicas
- **Diseño responsivo** con breakpoints optimizados
- **Navegación por rutas** (/inicio, /servicios, /contacto)
- **Componentes reutilizables** y código bien estructurado
- **Optimización de rendimiento** con lazy loading y code splitting
- **Accesibilidad mejorada** con estados de focus y navegación por teclado
- **SEO optimizado** con meta tags y estructura semántica

## Estructura del Proyecto

```
aero4-website/
├── public/
├── src/
│   ├── assets/
│   │   └── aero4-logo.png          # Logo de la empresa
│   ├── components/
│   │   ├── ui/                     # Componentes de interfaz
│   │   │   ├── badge.jsx
│   │   │   ├── button.jsx
│   │   │   ├── card.jsx
│   │   │   ├── input.jsx
│   │   │   └── textarea.jsx
│   │   ├── Header.jsx              # Navegación principal
│   │   └── Footer.jsx              # Pie de página
│   ├── pages/
│   │   ├── Home.jsx                # Página de inicio
│   │   ├── Services.jsx            # Página de servicios
│   │   └── Contact.jsx             # Página de contacto
│   ├── App.jsx                     # Componente principal
│   ├── App.css                     # Estilos personalizados
│   └── main.jsx                    # Punto de entrada
├── package.json
├── vite.config.js
└── README.md
```

## Instalación y Uso

### Prerrequisitos
- Node.js (versión 18 o superior)
- pnpm (recomendado) o npm

### Instalación
```bash
# Clonar el repositorio (si aplica)
cd aero4-website

# Instalar dependencias
pnpm install

# Iniciar servidor de desarrollo
pnpm run dev

# Construir para producción
pnpm run build

# Previsualizar build de producción
pnpm run preview
```

### Comandos Disponibles
- `pnpm run dev` - Inicia el servidor de desarrollo
- `pnpm run build` - Construye la aplicación para producción
- `pnpm run preview` - Previsualiza la build de producción
- `pnpm run lint` - Ejecuta el linter de código

## Páginas y Funcionalidades

### 🏠 Página de Inicio (/)
- **Hero section** con presentación de la empresa
- **Sección de servicios** destacando lo que se ofrece
- **Justificación de precios** explicando las ventajas competitivas
- **Call-to-action** para solicitar cotización

### 🚁 Página de Servicios (/servicios)
- **Vuelo de Dron Profesional**
  - Descripción detallada del servicio
  - Explicación de precios variables
  - Características incluidas
- **Edición y Postproducción**
  - Servicios de edición profesional
  - Precios basados en tiempo y material
  - Entrega optimizada para redes
- **Flexibilidad de contratación**
  - Servicios por separado
  - Paquete completo con descuentos
  - Ventajas de cada opción

### 📞 Página de Contacto (/contacto)
- **Formulario de cotización** con campos específicos
- **Información de contacto** completa
- **Ventajas de elegir Aero4**
- **Tiempo de respuesta** garantizado

## Personalización y Mantenimiento

### Colores de Marca
Los colores principales están definidos en `App.css` y siguen la paleta del logo:
- **Primario**: Azul cian (#06b6d4)
- **Secundario**: Azul (#3b82f6)
- **Fondo**: Tonos de gris oscuro para contraste

### Modificar Contenido
- **Textos**: Editar directamente en los archivos de componentes
- **Imágenes**: Reemplazar en la carpeta `src/assets/`
- **Estilos**: Modificar en `App.css` o usar clases de Tailwind

### Añadir Nuevas Páginas
1. Crear nuevo archivo en `src/pages/`
2. Añadir ruta en `App.jsx`
3. Actualizar navegación en `Header.jsx`

## Optimizaciones Implementadas

### Rendimiento
- **Code splitting** automático con Vite
- **Lazy loading** de componentes
- **Optimización de imágenes** con formatos modernos
- **Minificación** de CSS y JavaScript

### SEO
- **Meta tags** optimizados
- **Estructura semántica** HTML5
- **URLs amigables** con React Router
- **Títulos descriptivos** en cada página

### Accesibilidad
- **Navegación por teclado** completa
- **Estados de focus** visibles
- **Contraste de colores** adecuado
- **Textos alternativos** en imágenes

## Próximos Pasos Recomendados

### Funcionalidades Adicionales
1. **Formulario funcional** - Integrar con servicio de email
2. **Galería de trabajos** - Mostrar proyectos realizados
3. **Blog/Noticias** - Contenido para SEO
4. **Testimonios** - Reseñas de clientes
5. **Chat en vivo** - Atención inmediata

### Integraciones
- **Google Analytics** - Seguimiento de visitantes
- **Google Maps** - Ubicación de servicios
- **Redes sociales** - Enlaces funcionales
- **WhatsApp Business** - Contacto directo

### Marketing Digital
- **Optimización SEO** avanzada
- **Google My Business** - Presencia local
- **Campañas de Google Ads** - Publicidad dirigida
- **Content marketing** - Blog especializado

## Soporte y Contacto

Para modificaciones, mantenimiento o nuevas funcionalidades, el código está bien documentado y estructurado para facilitar futuras actualizaciones.

### Tecnologías Modernas
El proyecto utiliza las últimas versiones de React y herramientas modernas, garantizando:
- **Mantenibilidad** a largo plazo
- **Escalabilidad** para nuevas funciones
- **Rendimiento** optimizado
- **Compatibilidad** con navegadores modernos

---

**Aero4** - Servicios Profesionales de Drones
*Freelance en crecimiento comprometido con la excelencia*


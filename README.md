# ☕ Cafe Dinorin - Tienda Web Oficial

Tienda web oficial de **Cafe Dinorin** para la venta de café premium de alta calidad en presentaciones de 500 gramos y 1 kg.

---

## 📋 Descripción

**Cafe Dinorin** es una plataforma de comercio electrónico dedicada a la distribución de café de excelente calidad. Nuestro objetivo es acercar el mejor café a los amantes de esta bebida en sus casas, con un proceso de compra simple, seguro y confiable.

Este repositorio contiene el código fuente de la tienda web oficial donde los clientes pueden:
- Explorar nuestros productos de café
- Ver detalles e información nutricional
- Realizar compras en línea
- Rastrear pedidos
- Contactar con nuestro equipo de atención al cliente

---

## ✨ Características

- 🛍️ **Catálogo de productos** - Visualización clara de presentaciones (500g y 1kg)
- 🛒 **Carrito de compras** - Añade y gestiona tus productos
- 💳 **Pagos seguros** - Integración con pasarelas de pago confiables
- 👤 **Gestión de cuenta** - Registro, login y perfil de usuario
- 📦 **Seguimiento de pedidos** - Rastreo en tiempo real de tus compras
- 📱 **Diseño responsivo** - Optimizado para móviles, tablets y desktop
- 🔍 **Búsqueda avanzada** - Filtra por tipo de café, precio, etc.
- 📧 **Newsletter** - Suscríbete para recibir ofertas especiales

---

## 🛠️ Tecnologías

### Frontend
- **HTML5** - Estructura semántica
- **CSS3** - Estilos y diseño responsivo
- **JavaScript** - Interactividad y lógica del cliente

### Backend (Próximo)
- **Node.js / Express** - Servidor web
- **MongoDB** - Base de datos NoSQL
- **JWT** - Autenticación segura

### Herramientas
- **Git** - Control de versiones
- **GitHub** - Repositorio y colaboración

---

## 🚀 Cómo Correrlo Paso a Paso

### Requisitos Previos
- Git instalado en tu máquina
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Editor de código (VS Code recomendado)

### Instalación Local

1. **Clona el repositorio**
   ```bash
   git clone https://github.com/contactocafedinorin/cafe-dinorin.git
   cd cafe-dinorin
   ```

2. **Abre el proyecto en tu editor**
   ```bash
   code .
   ```

3. **Inicia un servidor local** (si tienes Python)
   ```bash
   # Python 3.x
   python -m http.server 8000
   
   # O usa Live Server en VS Code
   ```

4. **Accede a la aplicación**
   - Abre tu navegador en `http://localhost:8000`
   - La tienda web se cargará automáticamente

5. **Explora la tienda**
   - Navega por los productos
   - Prueba el carrito de compras
   - Interactúa con las distintas secciones

---

## 📁 Estructura del Proyecto

```
cafe-dinorin/
│
├── README.md                 # Este archivo
├── LICENSE                   # Licencia del proyecto
├── .gitignore               # Archivos ignorados por Git
│
├── index.html               # Página principal
├── styles/
│   ├── main.css            # Estilos generales
│   ├── components.css      # Estilos de componentes
│   └── responsive.css      # Diseño responsivo
│
├── js/
│   ├── main.js             # Lógica principal
│   ├── cart.js             # Gestión del carrito
│   ├── products.js         # Manejo de productos
│   └── utils.js            # Funciones auxiliares
│
├── assets/
│   ├── images/             # Imágenes de productos
│   ├── icons/              # Iconos de la página
│   └── logos/              # Logo de Cafe Dinorin
│
├── pages/
│   ├── productos.html      # Página de productos
│   ├── contacto.html       # Página de contacto
│   ├── carrito.html        # Página del carrito
│   ├── checkout.html       # Página de pago
│   └── about.html          # Acerca de nosotros
│
└── data/
    └── products.json       # Base de datos de productos (JSON)
```

---

## 🤝 Cómo Contribuir

¡Nos encanta recibir contribuciones! Sigue estos pasos para colaborar:

1. **Haz un Fork del proyecto**
   ```bash
   git clone https://github.com/tu-usuario/cafe-dinorin.git
   ```

2. **Crea una rama para tu feature**
   ```bash
   git checkout -b feature/mi-nueva-caracteristica
   ```

3. **Realiza tus cambios**
   - Edita los archivos necesarios
   - Asegúrate de mantener la calidad del código
   - Comenta tu código cuando sea necesario

4. **Commit tus cambios**
   ```bash
   git commit -m "Añade: descripción clara del cambio"
   ```

5. **Push a tu rama**
   ```bash
   git push origin feature/mi-nueva-caracteristica
   ```

6. **Abre un Pull Request**
   - Describe los cambios que realizaste
   - Explica por qué son importantes
   - Espera la revisión del equipo

### Convenciones de Código
- Usa nombres claros y descriptivos
- Comenta el código complejo
- Sigue estándares de indentación (2 espacios)
- Mantén el código DRY (Don't Repeat Yourself)

---

## 📊 Estado del Proyecto

**Estado Actual: MVP (Mínimo Producto Viable)**

### ✅ Completado
- [x] Estructura base del repositorio
- [x] Diseño inicial de la tienda
- [x] Página de inicio
- [x] Catálogo de productos

### 🔄 En Progreso
- [ ] Sistema de carrito de compras
- [ ] Autenticación de usuarios
- [ ] Integración de pagos

### 📋 Pendiente
- [ ] Backend con Node.js y Express
- [ ] Base de datos MongoDB
- [ ] Sistema de órdenes y seguimiento
- [ ] Panel de administración
- [ ] Optimización SEO
- [ ] Tests automatizados

---

## 📄 Licencia

Este proyecto está bajo la licencia **MIT**. Consulta el archivo [LICENSE](LICENSE) para más detalles.

La licencia MIT permite:
- ✅ Uso comercial
- ✅ Modificación
- ✅ Distribución
- ✅ Uso privado

Con la condición de:
- ⚠️ Incluir la licencia original

---

## 📞 Contacto

- **Email:** contacto@cafedinorin.com
- **Sitio Web:** www.cafedinorin.com
- **Instagram:** @cafedinorin
- **Teléfono:** +1 (XXX) XXX-XXXX

---

## 🙏 Agradecimientos

Agradecemos a todos los que contribuyen a mejorar Cafe Dinorin y a nuestros clientes por su confianza.

---

**Hecho con ☕ y amor por el equipo de Cafe Dinorin**

*Última actualización: Septiembre 2026*

# 💰 Alke Wallet - Billetera Digital

**Una aplicación web moderna de billetera digital con diseño dark theme**

---

## 📋 Descripción

Alke Wallet es una aplicación web educativa de billetera digital desarrollada como parte del programa de formación **SENCE - OTEC Infocal**. Este proyecto tiene fines de aprendizaje y demostración de habilidades en desarrollo frontend, permitiendo a los usuarios gestionar sus finanzas virtuales mediante una interfaz moderna, intuitiva y completamente responsive.

Este proyecto implementa las mejores prácticas de desarrollo web, incluyendo diseño responsive, gestión de estado con LocalStorage, y una experiencia de usuario fluida con animaciones y validaciones en tiempo real.

### 🎯 Propósito Educativo

Este proyecto fue desarrollado como parte de un programa de formación en desarrollo web full-stack, específicamente para el **Módulo 2: Desarrollo Frontend Avanzado**. Su objetivo es demostrar competencias en:

- Maquetación HTML5 semántica
- Diseño CSS3 avanzado con variables y temas personalizados
- Programación JavaScript vanilla y jQuery
- Gestión de datos con LocalStorage
- Diseño responsive mobile-first
- UX/UI modernas
- Manejo de formularios y validaciones

> ⚠️ **Nota Importante**: Esta es una aplicación de demostración con fines educativos. No debe utilizarse para transacciones reales ni almacenar información financiera sensible.

---

## ✨ Características

### 🔐 Autenticación
- Sistema de login con validación de credenciales
- Toggle para mostrar/ocultar contraseña
- Animaciones de error (shake effect)
- Persistencia de sesión

### 💵 Gestión de Fondos
- **Depósitos**: Añadir fondos con múltiples métodos de pago
- **Transferencias**: Enviar dinero a contactos con validación de saldo
- **Montos rápidos**: Botones de acceso rápido para cantidades comunes
- Formateo automático de moneda chilena (CLP)

### 📊 Historial y Estadísticas
- Visualización completa de transacciones
- Filtros por tipo, fecha y búsqueda de texto
- Estadísticas mensuales (ingresos/egresos)
- Detalles completos de cada transacción
- Paginación y ordenamiento

### 👥 Gestión de Contactos
- Agregar y guardar contactos
- Autocompletado en búsqueda
- Selección rápida desde lista
- Avatares con iniciales

### 🎨 Diseño y UX
- **Dark Theme** con paleta de colores burdeos
- Interfaz completamente responsive
- Animaciones fluidas y transiciones suaves
- Iconografía con Font Awesome
- Modales de confirmación
- Estados de carga y feedback visual

### 🔒 Seguridad y Privacidad
- Datos separados por usuario (cada usuario tiene su propia información)
- Validación de formularios
- Mensajes de error claros
- Confirmaciones antes de acciones importantes

---

## 🚀 Demo

### Usuarios de Prueba

Para probar la aplicación, puedes usar las siguientes credenciales:

| Usuario | Contraseña | Descripción |
|---------|------------|-------------|
| `admin` | `admin123` | Usuario administrador |
| `usuario` | `user123` | Usuario demo estándar |

> 💡 **Tip**: Cada usuario tiene sus propios datos independientes (saldo, transacciones, contactos)

---

## 💻 Instalación

### Requisitos Previos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Conexión a internet (para CDNs de Bootstrap, jQuery y Font Awesome)
- Opcionalmente: Servidor local para desarrollo

### Pasos de Instalación

1. **Clonar el repositorio**
```bash
git clone https://github.com/jitv-dev/AlkeWallet-Modulo2.git
cd alke_wallet_modulo2
```

2. **Opción A: Abrir directamente**
   - Simplemente abre `index.html` en tu navegador

3. **Opción B: Usar servidor local** (recomendado)
```bash
# Con Python 3
python -m http.server 8000

# Con Node.js
npx http-server

# Con PHP
php -S localhost:8000
```

4. **Acceder a la aplicación**
   - Navega a `http://localhost:8000`

---

## 📁 Estructura del Proyecto

```
alke_wallet_modulo2/
│
├── index.html              # Página de entrada (redirección)
├── login.html             # Inicio de sesión
├── menu.html              # Panel principal
├── deposit.html           # Realizar depósitos
├── sendmoney.html         # Enviar dinero
├── transactions.html      # Historial de transacciones
├── README.md              # Documentación
├── LICENSE                # Licencia MIT
│
├── css/
│   └── styles.css        # Estilos personalizados (Dark Theme)
│
└── js/
    └── script.js         # Lógica de la aplicación
```

---

## 🛠️ Tecnologías Utilizadas

### Frontend
- **HTML5** - Estructura semántica
- **CSS3** - Estilos avanzados con variables CSS
- **JavaScript (ES6+)** - Lógica de negocio
- **jQuery 3.7.0** - Manipulación DOM y AJAX

### Frameworks y Librerías
- **Bootstrap 5.3.0** - Framework CSS responsive
- **Font Awesome 6.4.0** - Iconografía
- **jQuery UI** - Autocompletado de contactos

### Almacenamiento
- **LocalStorage API** - Persistencia de datos del cliente

### Herramientas de Desarrollo
- Git - Control de versiones
- Visual Studio Code - Editor de código (recomendado)

---

## 📖 Uso

### 1. Inicio de Sesión
1. Abre la aplicación en tu navegador
2. Serás redirigido automáticamente a `login.html`
3. Ingresa un usuario y contraseña de prueba
4. Haz clic en "Iniciar Sesión"

### 2. Panel Principal
Una vez autenticado, verás:
- **Saldo disponible** con animación de conteo
- **Acciones rápidas**: Depositar, Enviar Dinero, Movimientos, Estadísticas
- **Últimas transacciones** (si las hay)

### 3. Realizar un Depósito
1. Haz clic en "Depositar" desde el menú
2. Ingresa el monto (mínimo $1.000 CLP)
3. Usa los botones de montos rápidos o ingresa uno personalizado
4. Selecciona el método de depósito
5. Opcionalmente, agrega una descripción
6. Haz clic en "Realizar Depósito"

### 4. Enviar Dinero
1. Haz clic en "Enviar Dinero"
2. Busca un contacto o ingresa los datos manualmente
3. Ingresa el monto a transferir
4. Agrega un mensaje (opcional)
5. Marca "Guardar contacto" si deseas agregarlo a tu lista
6. Haz clic en "Enviar Dinero"

### 5. Ver Transacciones
1. Accede a "Movimientos" desde el menú
2. Usa los filtros para buscar transacciones específicas
3. Haz clic en cualquier transacción para ver detalles
4. Exporta tu historial (función en desarrollo)

---

## 🎨 Personalización

### Cambiar Tema de Colores

El archivo `css/styles.css` utiliza variables CSS para facilitar la personalización:

```css
:root {
    --primary-color: #8b1538;      /* Burdeo principal */
    --primary-dark: #6b0f2a;       /* Burdeo oscuro */
    --primary-light: #a91d42;      /* Burdeo claro */
    --bg-light: #1a1a1a;           /* Fondo oscuro */
    --bg-white: #252525;           /* Fondo de tarjetas */
    --text-dark: #e5e7eb;          /* Texto principal */
    --text-muted: #9ca3af;         /* Texto secundario */
}
```

Modifica estos valores para cambiar la paleta de colores completa.

---

## 🗺️ Roadmap

### Funcionalidades Futuras

- [ ] Gráficos de estadísticas con Chart.js
- [ ] Exportación de transacciones a PDF/Excel
- [ ] Sistema de notificaciones
- [ ] Modo claro/oscuro toggle
- [ ] Multi-idioma (i18n)
- [ ] Integración con API backend
- [ ] Autenticación con JWT
- [ ] Recuperación de contraseña
- [ ] Verificación en dos pasos (2FA)
- [ ] Categorización de gastos

---

## 🤝 Contribuciones

Las contribuciones son bienvenidas y apreciadas. Si deseas colaborar:

1. Haz un **Fork** del repositorio
2. Crea una rama para tu característica:
   ```bash
   git checkout -b feature/nueva-caracteristica
   ```
3. Realiza tus cambios y haz **commit**:
   ```bash
   git commit -m "Añadir: nueva característica X"
   ```
4. Sube tus cambios:
   ```bash
   git push origin feature/nueva-caracteristica
   ```
5. Abre un **Pull Request**

### Guías de Contribución
- Mantén el código limpio y comentado
- Sigue las convenciones de nomenclatura existentes
- Asegúrate de que el diseño sea responsive
- Prueba en múltiples navegadores

---

## 🐛 Problemas Conocidos

- [ ] El autocompletado de contactos requiere jQuery UI
- [ ] La exportación de transacciones está pendiente de implementación
- [ ] Las notificaciones push no están disponibles
- [ ] No hay validación de formato de email en tiempo real

---

## 📚 Recursos de Aprendizaje

Este proyecto utiliza conceptos de:

- [MDN Web Docs](https://developer.mozilla.org/) - Documentación web
- [Bootstrap Documentation](https://getbootstrap.com/docs/) - Framework CSS
- [jQuery API](https://api.jquery.com/) - Biblioteca JavaScript
- [Font Awesome Icons](https://fontawesome.com/icons) - Iconografía

---

## 📝 Licencia

Este proyecto está licenciado bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

---

## 👨‍💻 Autor

**Javier Torres**

Desarrollador Web Full-Stack en formación  
Programa SENCE - OTEC Infocal, 2026

- 🔗 GitHub: [@jitv-dev](jitv-dev/AlkeWallet-Modulo2)
- 💼 LinkedIn: [Javier Torres](https://www.linkedin.com/in/javier-torres-valenz/)
- 🌐 Portfolio: [jitv-dev](https://jitv-dev.github.io/portafolio/)

---

## 🙏 Agradecimientos

- A **SENCE** y **OTEC Infocal** por el programa de formación
- A la comunidad de desarrolladores por los recursos y documentación
- A **Bootstrap** por el excelente framework CSS
- A **Font Awesome** por los iconos profesionales
- A **Claude AI** (Anthropic) por la asistencia en la documentación de este proyecto
- A todos los que contribuyeron con feedback y sugerencias

---

## 📞 Soporte

Si tienes preguntas o necesitas ayuda:

1. Revisa la [documentación](#-uso)
2. Busca en los [issues existentes](https://github.com/jitv-dev/AlkeWallet-Modulo2/issues)
3. Crea un [nuevo issue](https://github.com/jitv-dev/AlkeWallet-Modulo2/issues/new) si no encuentras solución

---

**Desarrollado con ❤️ por Javier Torres - 2026**

*Proyecto educativo - SENCE OTEC Infocal*
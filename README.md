# 🛒 Sistema de Ventas Laravel

<p align="center">
  <img src="https://img.shields.io/badge/Laravel-11.x-red?style=for-the-badge&logo=laravel" alt="Laravel 11">
  <img src="https://img.shields.io/badge/PHP-8.2+-blue?style=for-the-badge&logo=php" alt="PHP 8.2+">
  <img src="https://img.shields.io/badge/AdminLTE-4.0-green?style=for-the-badge" alt="AdminLTE 4">
  <img src="https://img.shields.io/badge/Bootstrap-5.3.7-purple?style=for-the-badge&logo=bootstrap" alt="Bootstrap 5.3.7">
  <img src="https://img.shields.io/badge/MariaDB-Latest-orange?style=for-the-badge&logo=mariadb" alt="MariaDB">
</p>

Sistema de gestión de ventas desarrollado con Laravel 11 y AdminLTE 4. Plantilla modular con diseño responsivo y moderno para la administración eficiente de procesos comerciales.

## 📋 Descripción del Proyecto

Sistema web completo para la gestión de ventas que incluye:

- ✅ **Gestión de Productos** - Catálogo completo con categorías
- ✅ **Control de Inventario** - Stock y movimientos en tiempo real  
- ✅ **Administración de Clientes** - Base de datos de clientes
- ✅ **Proceso de Ventas** - Facturación y reportes
- ✅ **Dashboard Administrativo** - Métricas y estadísticas
- ✅ **Plantilla Modularizada** - Componentes reutilizables

## 🚀 Tecnologías Utilizadas

| Tecnología | Versión | Propósito |
|------------|---------|-----------|
| **Laravel** | 11.x | Framework PHP backend |
| **PHP** | 8.2+ | Lenguaje de programación |
| **AdminLTE** | 4.0 | Plantilla administrativa |
| **Bootstrap** | 5.3.7 | Framework CSS |
| **MariaDB** | Latest | Base de datos |
| **Vite** | Latest | Build tool para assets |

## 📦 Instalación

### Prerequisitos
- PHP 8.2 o superior
- Composer
- MariaDB/MySQL
- Node.js y npm

### Pasos de Instalación

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/daisersenpro/Sistema-de-Ventas.git
   cd Sistema-de-Ventas
   ```

2. **Instalar dependencias PHP**
   ```bash
   composer install
   ```

3. **Instalar dependencias Node.js**
   ```bash
   npm install
   ```

4. **Configurar archivo de entorno**
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

5. **Configurar base de datos en `.env`**
   ```env
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=dbsistema
   DB_USERNAME=root
   DB_PASSWORD=1234
   ```

6. **Ejecutar migraciones**
   ```bash
   php artisan migrate
   ```

7. **Compilar assets**
   ```bash
   npm run build
   ```

8. **Iniciar servidor de desarrollo**
   ```bash
   php artisan serve
   ```

## 🏗️ Estructura del Proyecto

### Plantillas Modularizadas
```
resources/views/
├── plantilla/
│   ├── app.blade.php      # Layout principal
│   ├── header.blade.php   # Barra de navegación
│   ├── menu.blade.php     # Menú lateral
│   └── footer.blade.php   # Pie de página
└── welcome.blade.php      # Página de inicio
```

### Características de la Plantilla
- 🎨 **Diseño Modular**: Componentes separados y reutilizables
- 📱 **Responsivo**: Compatible con dispositivos móviles
- 🎯 **AdminLTE 4**: Interfaz administrativa moderna
- ⚡ **Bootstrap 5.3.7**: Componentes UI actualizados

## 🔧 Configuración

### Base de Datos
El sistema utiliza MariaDB con la siguiente configuración por defecto:
- **Host**: 127.0.0.1
- **Puerto**: 3306
- **Base de datos**: `dbsistema`
- **Usuario**: `root`
- **Contraseña**: `1234`

### Assets y Recursos
Los assets están optimizados con Vite:
```bash
npm run dev     # Modo desarrollo
npm run build   # Compilar para producción
```

## 👨‍💻 Desarrollo

### Comandos Útiles
```bash
# Limpiar cache
php artisan cache:clear
php artisan config:clear
php artisan view:clear

# Generar controlador
php artisan make:controller NombreController

# Generar modelo
php artisan make:model NombreModelo -m
```

## 📊 Características del Sistema

- **Dashboard Dinámico**: Métricas en tiempo real
- **Gestión de Usuarios**: Control de acceso y permisos
- **Reportes Avanzados**: Exportación en múltiples formatos
- **API REST**: Endpoints para integración externa
- **Seguridad**: Autenticación y autorización Laravel

## 🤝 Contribución

Las contribuciones son bienvenidas. Para contribuir:

1. Fork el proyecto
2. Crea una rama feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

## 👤 Desarrollador

**Anyelo Bustos Galdames**
- GitHub: [@daisersenpro](https://github.com/daisersenpro)
- Email: [tu-email@dominio.com](mailto:tu-email@dominio.com)

## 🙏 Agradecimientos

- [Laravel](https://laravel.com) - Framework PHP
- [AdminLTE](https://adminlte.io) - Plantilla administrativa
- [Bootstrap](https://getbootstrap.com) - Framework CSS

---

⭐ ¡Si te gusta este proyecto, no olvides darle una estrella!

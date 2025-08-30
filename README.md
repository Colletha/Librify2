# Sistema de Librify

Sistema web completo para la administración de una biblioteca escolar desarrollado en PHP, MySQL, HTML5, CSS3, JavaScript y Bootstrap 5.

## 🚀 Características Principales

- **Sistema de Autenticación**: Login seguro con roles (Administrador, Bibliotecario, Alumno)
- **Gestión de Libros**: CRUD completo con búsqueda y filtros
- **Gestión de Usuarios**: Administración de usuarios por roles
- **Sistema de Préstamos**: Registro y control de préstamos/devoluciones
- **Sistema de Multas**: Cálculo automático por retrasos
- **Reportes Completos**: Estadísticas y reportes imprimibles
- **Interfaz Responsiva**: Compatible con dispositivos móviles

## 📋 Requisitos del Sistema

- XAMPP (Apache + MySQL + PHP 7.4+)
- Navegador web moderno
- 50MB de espacio en disco

## Para Acceder al Sistema
1. Abrir el navegador y ir a: [http://localhost/Librify/biblioteca-escolar](http://localhost/Librify/biblioteca-escolar)
2. Usar las credenciales de prueba para acceder

## 👥 Credenciales de Acceso

### Administrador
- **Usuario**: admin@biblioteca.edu
- **Contraseña**: password
- **Permisos**: Acceso completo al sistema

### Bibliotecario
- **Usuario**: bibliotecaria@biblioteca.edu
- **Contraseña**: password
- **Permisos**: Gestión de libros, usuarios y préstamos

### Alumno
- **Usuario**: alumno@biblioteca.edu
- **Contraseña**: password
- **Permisos**: Solo consulta de libros disponibles y vista de préstamos

## 📁 Estructura del Proyecto

\`\`\`
biblioteca-escolar/
├── assets/
│   ├── css/
│   │   └── dashboard.css
│   └── js/
│       └── dashboard.js
├── config/
│   ├── database.php
│   └── session.php
├── database/
│   └── biblioteca_escolar.sql
├── includes/
│   ├── navbar.php
│   └── sidebar.php
├── libros/
│   ├── index.php
│   ├── crear.php
│   ├── editar.php
│   └── eliminar.php
├── prestamos/
│   ├── index.php
│   ├── crear.php
│   └── devolver.php
├── reportes/
│   ├── index.php
│   ├── reporte_usuarios.php
│   ├── reporte_prestamos_activos.php
│   └── reporte_libros_disponibles.php
├── usuarios/
│   ├── index.php
│   ├── crear.php
│   ├── editar.php
│   └── eliminar.php
├── dashboard.php
├── login.php
├── logout.php
└── README.md
\`\`\`

## 🔧 Funcionalidades por Rol

### Administrador
- ✅ Gestión completa de usuarios
- ✅ Gestión completa de libros
- ✅ Gestión de préstamos y devoluciones
- ✅ Acceso a todos los reportes
- ✅ Configuración del sistema

### Bibliotecario
- ✅ Gestión de libros (crear, editar, eliminar)
- ✅ Gestión de préstamos y devoluciones
- ✅ Acceso a reportes
- ❌ No puede gestionar usuarios administradores

### Alumno
- ✅ Consulta de libros disponibles
- ✅ Ver sus propios préstamos
- ❌ No puede realizar operaciones administrativas

## 📊 Módulos del Sistema

### 1. Gestión de Libros
- Registro de nuevos libros
- Edición de información
- Control de inventario
- Búsqueda y filtros
- Categorización

### 2. Gestión de Usuarios
- Registro de usuarios por rol
- Edición de perfiles
- Control de acceso
- Validación de datos

### 3. Sistema de Préstamos
- Registro de préstamos
- Control de fechas límite
- Proceso de devolución
- Cálculo automático de multas
- Historial completo

### 4. Sistema de Reportes
- Reporte por usuario
- Préstamos activos
- Libros disponibles
- Estadísticas generales
- Exportación para impresión

## 🔒 Seguridad Implementada

- Contraseñas encriptadas utiliando password_hash()
- Validación de sesiones
- Protección contra inyección SQL (PDO)
- Validación de datos de entrada
- Control de acceso por roles
- Sanitización de salidas HTML

## 📝 Notas de Desarrollo

- Desarrollado siguiendo las mejores prácticas de PHP
- Código comentado y estructurado
- Base de datos normalizada
- Interfaz responsiva con Bootstrap 5
- Validaciones tanto del lado cliente como servidor
- Algúnas tecnologías comenzaron como posibles ideas para el proyecto y se pegaron al programa, sin embargo no se llegaron a concretar por cuestiones de tiempo. 

## 🎓 Proyecto 5BCC

Este sistema fue desarrollado como proyecto final para Quinto Bachillerato en Computación por Amelia Guaré, Cesia Ortiz y Colleth Sánchez, cumpliendo con todos los requisitos establecidos por el profe Sunun en las tres fases del proyecto:

- **Fase 1**: Análisis, diseño y sistema de login ✅
- **Fase 2**: CRUDs y gestión de préstamos ✅
- **Fase 3**: Reportes y documentación ✅


---

**Versión**: 1.0  
**Fecha**: 29/08/2025 
**Tecnologías**: PHP 8.0+, MySQL 8.0+, Bootstrap 5, HTML5, CSS3, JavaScript

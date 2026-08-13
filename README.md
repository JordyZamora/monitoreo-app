# 🌐 UTEQ Sensor Monitor

Sistema de monitoreo de sensores en tiempo real desarrollado con React + Vite. Permite visualizar datos de sensores distribuidos en diferentes ubicaciones geográficas.

![Application Screenshot](./screenshot.png)

## 📋 Descripción del Proyecto

UTEQ Sensor Monitor es una aplicación web moderna que proporciona un dashboard interactivo para monitorear sensores. La aplicación está integrada con Firebase para almacenamiento y gestión de datos en tiempo real.

## ✨ Características Principales

- **Dashboard de Sensores**: Visualiza datos en tiempo real de sensores específicos
- **Mapa de Ubicaciones**: Interfaz para gestionar y visualizar ubicaciones de sensores
- **Navegación Intuitiva**: Barra de navegación moderna para acceder a las diferentes secciones
- **Tarjetas de Sensor**: Componentes reutilizables para mostrar información de sensores
- **Integración Firebase**: Conexión en tiempo real con base de datos Firebase
- **Diseño Responsivo**: Interfaz optimizada para diferentes dispositivos

## 🛠️ Tecnologías Utilizadas

- **React 19** - Librería de UI
- **Vite 8** - Bundler rápido y moderno
- **React Router 7** - Enrutamiento
- **Firebase 12** - Base de datos y autenticación
- **CSS3** - Estilos personalizados

## 📁 Estructura del Proyecto

```
src/
├── components/          # Componentes reutilizables
│   ├── Navbar.jsx      # Barra de navegación
│   └── SensorCard.jsx  # Tarjeta de sensor
├── pages/              # Páginas principales
│   ├── Dashboard.jsx   # Dashboard de sensores
│   └── Ubicaciones.jsx # Página de ubicaciones
├── hooks/              # Hooks personalizados
│   └── useSensorData.js # Hook para obtener datos de sensores
├── services/           # Servicios
│   └── firebase.js     # Configuración de Firebase
├── App.jsx            # Componente raíz
└── styles/            # Estilos globales
```

## 🚀 Inicio Rápido

### Requisitos Previos
- Node.js 16+
- npm o yarn

### Instalación

```bash
# Clonar el repositorio
git clone <repository-url>
cd monitoreo-app

# Instalar dependencias
npm install
```

### Desarrollo

```bash
# Iniciar servidor de desarrollo
npm run dev
```

La aplicación estará disponible en `http://localhost:5174/`

### Producción

```bash
# Compilar para producción
npm run build

# Vista previa de la compilación
npm run preview
```

## 📊 Funcionalidades

### Dashboard
- Visualización de datos en tiempo real del sensor
- Actualización automática de información
- Interfaz limpia y moderna

### Ubicaciones
- Gestión de ubicaciones de sensores
- Mapa interactivo de ubicaciones

## 🔌 Integración Firebase

La aplicación se conecta a Firebase para:
- Almacenamiento de datos de sensores
- Sincronización en tiempo real
- Autenticación (si aplica)

Configura las credenciales de Firebase en `src/services/firebase.js`

## 📝 Cambios Recientes (v0.0.0)

- ✅ Inicialización del proyecto React + Vite
- ✅ Configuración de enrutamiento con React Router
- ✅ Creación de componentes base (Navbar, SensorCard)
- ✅ Implementación de páginas (Dashboard, Ubicaciones)
- ✅ Integración Firebase
- ✅ Estilos CSS personalizados
- ✅ Hook personalizado para datos de sensores

## 📄 Licencia

Este proyecto es privado.

---

**Estado**: En desarrollo 🚀

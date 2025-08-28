# KrakenwareProject

Un proyecto Flutter desarrollado con múltiples tecnologías incluyendo C++, CMake, Dart, Swift, C y HTML.

## 📱 Plataformas Soportadas

- ✅ Android
- ✅ iOS
- ✅ Web
- ✅ Desktop (Windows, macOS, Linux)

## 🚀 Inicio Rápido

### Requisitos Previos

Antes de comenzar, asegúrate de tener instalado:

- **Flutter SDK** (versión 3.0 o superior)
- **Dart SDK** (incluido con Flutter)
- **Git** para control de versiones
- **Android Studio** o **VS Code** con extensiones de Flutter
- Un **dispositivo físico** o **emulador** configurado

Para verificar que Flutter está correctamente instalado, ejecuta:
```bash
flutter doctor
```

### Instalación

Sigue estos pasos para configurar y ejecutar el proyecto:

#### 1. Clonar el repositorio

```bash
git clone https://github.com/JosephJMRG1/KrakenwareProject.git
```

#### 2. Navegar a la carpeta del proyecto

```bash
cd KrakenwareProject
```

#### 3. Limpiar el proyecto

```bash
flutter clean
```

#### 4. Instalar dependencias

```bash
flutter pub get
```

#### 5. Ejecutar la aplicación

```bash
flutter run
```

### Comandos en Secuencia

Para una instalación rápida, ejecuta todos los comandos de una vez:

```bash
git clone https://github.com/JosephJMRG1/KrakenwareProject.git && cd KrakenwareProject && flutter clean && flutter pub get && flutter run
```

## 🛠️ Tecnologías Utilizadas

- **Dart** (10.9%) - Lenguaje principal de Flutter
- **C++** (44.8%) - Lógica nativa de alto rendimiento
- **CMake** (35.9%) - Sistema de construcción multiplataforma
- **Swift** (3.3%) - Integración iOS nativa
- **C** (2.6%) - Código nativo de bajo nivel
- **HTML** (2.2%) - Soporte web

## 📋 Comandos Útiles

### Verificar dispositivos disponibles
```bash
flutter devices
```

### Construir para producción
```bash
# Android
flutter build apk --release

# iOS
flutter build ios --release

# Web
flutter build web --release
```

### Análisis de código
```bash
flutter analyze
```

### Ejecutar pruebas
```bash
flutter test
```

## 🔧 Resolución de Problemas

### Problemas comunes

1. **No se detectan dispositivos:**
   ```bash
   flutter devices
   ```
   Asegúrate de tener un emulador ejecutándose o un dispositivo físico conectado.

2. **Errores de dependencias:**
   ```bash
   flutter clean
   flutter pub cache repair
   flutter pub get
   ```

3. **Problemas de compilación:**
   ```bash
   flutter clean
   flutter pub get
   flutter run --verbose
   ```

## 📊 Estado del Proyecto

- **Estrellas:** 0 ⭐
- **Watchers:** 0 👀
- **Forks:** 0 🍴
- **Estado:** En desarrollo 🚧

## 📄 Licencia

Este proyecto no tiene licencia especificada. Consulta con el propietario del repositorio para más información sobre el uso y distribución.

## 👤 Autor

**JosephJMRG1**
- GitHub: [@JosephJMRG1](https://github.com/JosephJMRG1)
- GitHub: [@AdolfotULS](https://github.com/AdolfotULS)
- GitHub: [@Chibi](https://github.com/IgnaciaMiranda)
- GitHub: [@Pato](https://github.com/PatriciAstrado)
- GitHub: [@Jere](https://github.com/JereR1621)



## 🤝 Contribuir

Las contribuciones son bienvenidas. Por favor:

1. Haz fork del proyecto
2. Crea tu rama de características (`git checkout -b feature/AmazingFeature`)
3. Confirma tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Empuja a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

---

*Creado con ❤️ usando Flutter*
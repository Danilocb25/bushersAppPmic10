# BushersApp PMIC 10

Aplicación móvil desarrollada con React Native y Expo que proporciona funcionalidades para los usuarios de PMIC.

## ⬇️ Descargar APK

[![Descargar APK](https://github.com/Danilocb25/bushersAppPmic10/releases/tag/v1.0.0)]

> **Nota:** Asegúrate de tener habilitada la opción "Orígenes desconocidos" en la configuración de tu dispositivo Android para instalar aplicaciones fuera de Google Play Store.

## 🚀 Características

- Interfaz de usuario moderna y receptiva
- Navegación fluida con Expo Router
- Compatible con iOS y Android
- Diseño adaptativo para diferentes tamaños de pantalla
- Integración con funcionalidades nativas

## 📋 Requisitos Previos

- Node.js (v16 o superior)
- npm o yarn
- Expo CLI instalado globalmente (`npm install -g expo-cli`)
- Git
- Dispositivo móvil con la aplicación Expo Go o un emulador de Android/iOS

## 🛠 Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/Danilocb25/bushersAppPmic10.git
   cd bushersAppPmic10
   ```

2. Instala las dependencias:
   ```bash
   npm install
   # o
   yarn install
   ```

3. Inicia el servidor de desarrollo:
   ```bash
   npx expo start
   ```

4. Escanea el código QR con la aplicación Expo Go en tu dispositivo móvil o presiona:
   - `a` para abrir en un emulador de Android
   - `i` para abrir en un simulador de iOS
   - `w` para abrir en el navegador web

## 📸 Capturas de Pantalla

<div style="display: flex; flex-wrap: wrap; gap: 16px; justify-content: center;">
  <img src="./assets/images/screen/img1.jpeg" alt="Pantalla 1" width="200" />
  <img src="./assets/images/screen/img2.jpeg" alt="Pantalla 2" width="200" />
  <img src="./assets/images/screen/img3.jpeg" alt="Pantalla 3" width="200" />
  <img src="./assets/images/screen/img4.jpeg" alt="Pantalla 4" width="200" />
</div>

## 🏗 Estructura del Proyecto

```
bushersAppPmic10/
├── android/           # Configuración específica de Android
├── ios/               # Configuración específica de iOS
├── app/               # Directorio principal de la aplicación con Expo Router
│   └── (tabs)/        # Navegación por pestañas
├── assets/            # Recursos estáticos (imágenes, fuentes, etc.)
├── data/              # Datos y configuraciones
├── hooks/             # Custom hooks reutilizables
├── lib/               # Utilidades y lógica de negocio
├── node_modules/      # Dependencias
├── .gitignore
├── app.json           # Configuración de Expo
├── package.json       # Dependencias y scripts
└── tsconfig.json      # Configuración de TypeScript
```

## 🚦 Scripts Disponibles

- `expo start`: Inicia el servidor de desarrollo
- `expo run:android`: Ejecuta la aplicación en Android
- `expo run:ios`: Ejecuta la aplicación en iOS (solo macOS)
- `expo build:android`: Crea un APK/AAB para Android
- `expo build:ios`: Crea un IPA para iOS (solo macOS)


## 📱 Plataformas Soportadas

- Android 5.0+ (API 21+)
- iOS 13.0+
- Web (con limitaciones)


## 📄 Licencia

Este proyecto está bajo la Licencia [MIT](LICENSE).



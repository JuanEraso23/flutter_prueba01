# Dispositivos Moviles

## Primer Proyecto Flutter en Android Studio

---

## Propósito del Proyecto

El objetivo de este proyecto es iniciar el aprendizaje práctico de **Flutter** utilizando **Android Studio** como entorno de desarrollo.

Este proyecto corresponde a una aplicación básica generada con Flutter, la cual permite comprender la estructura inicial de un proyecto, el funcionamiento de los widgets principales y la ejecución de una aplicación en un emulador Android.

---

## Descripción

La aplicación muestra una interfaz inicial con una barra superior, un contador y un botón flotante que permite incrementar el valor mostrado en pantalla.

Este proyecto sirve como punto de partida para aprender conceptos fundamentales de Flutter, como:

- Estructura de carpetas de un proyecto Flutter.
- Uso del archivo `main.dart`.
- Widgets principales como `MaterialApp`, `Scaffold`, `AppBar`, `Center`, `Column` y `Text`.
- Uso de `StatefulWidget`.
- Actualización de estado mediante `setState`.
- Ejecución de la aplicación en un emulador Android.

---

## Herramientas Utilizadas

- **Flutter**: Framework utilizado para el desarrollo de aplicaciones multiplataforma.
- **Dart**: Lenguaje de programación utilizado por Flutter.
- **Android Studio**: Entorno de desarrollo utilizado para crear, editar y ejecutar el proyecto.
- **Android Emulator**: Emulador utilizado para visualizar y probar la aplicación.
- **Git**: Sistema de control de versiones utilizado para gestionar los cambios del proyecto.
- **GitHub**: Plataforma utilizada para almacenar el repositorio del proyecto.

---

## Estructura Principal del Proyecto

  ```text
  flutter_prueba01/
  │
  ├── android/              # Archivos de configuración para Android
  ├── ios/                  # Archivos de configuración para iOS
  ├── lib/                  # Código principal de la aplicación
  │   └── main.dart         # Archivo principal del proyecto
  ├── linux/                # Configuración para Linux
  ├── macos/                # Configuración para macOS
  ├── test/                 # Archivos de pruebas
  ├── web/                  # Configuración para aplicación web
  ├── windows/              # Configuración para Windows
  ├── pubspec.yaml          # Configuración de dependencias y recursos
  ├── pubspec.lock          # Registro de versiones exactas de paquetes
  ├── analysis_options.yaml # Reglas de análisis del código
  └── README.md             # Documentación del proyecto
  ```

---

## Instrucciones para Clonar y Ejecutar el Proyecto

### Requisitos Previos

Antes de ejecutar el proyecto, es necesario tener instalado:

- Flutter SDK
- Dart SDK
- Android Studio
- Git
- Un emulador Android configurado o un dispositivo físico conectado

También se recomienda verificar la instalación de Flutter con el siguiente comando:
Shellflutter doctorMostrar más líneas
Si todo está correctamente configurado, deberá aparecer un mensaje indicando que no existen problemas.

### Instalación

1. Clonar este repositorio en la máquina local:

  ```
  Shellgit clone URL_DEL_REPOSITORIO``Mostrar más líneas
  ```

2. Entrar a la carpeta del proyecto:

  ```
  Shellcd flutter_prueba01Mostrar más líneas
  ```

3. Obtener las dependencias del proyecto:

  ```
  Shellflutter pub getMostrar más líneas
  ```

4. Ejecutar la aplicación:

  ```
  Shellflutter runMostrar más líneas
  ```

---

### Ejecución
También se puede ejecutar el proyecto directamente desde Android Studio:

- Abrir Android Studio.
- Seleccionar la opción Open.
- Buscar y abrir la carpeta del proyecto flutter_prueba01.
- Seleccionar un emulador Android o dispositivo físico.
- Presionar el botón Run.
- Esperar a que Gradle compile e instale la aplicación.

---

## Autor(es)

Juan Eraso

---

## Expresiones de gratitud (Acknowledgments)

* Aprende de poco a poco para llegar lejos...

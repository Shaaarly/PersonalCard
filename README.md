# Aplicación Móvil para Intercambio de Tarjetas de Visita Digitales mediante Bluetooth/NFC

## Descripción General

Este repositorio contiene el código fuente de una aplicación móvil diseñada para facilitar el intercambio de tarjetas de visita digitales utilizando tecnología Bluetooth y NFC. La aplicación permite a los usuarios compartir su información de contacto de forma rápida y sencilla con solo acercar sus dispositivos móviles.

## Características Principales

- **Intercambio de Información mediante NFC y Bluetooth**: Permite la transferencia de datos entre dispositivos compatibles simplemente acercándolos.
- **Personalización de Tarjetas de Visita**: Los usuarios pueden elegir qué información compartir, como nombre, número de teléfono, correo electrónico, dirección de trabajo, y más.
- **Interfaz de Usuario Intuitiva**: Diseño amigable y fácil de usar para una experiencia de usuario óptima.
- **Compatibilidad Multiplataforma**: Disponible tanto para dispositivos Android como iOS.
- **Seguridad y Privacidad**: La información compartida está protegida mediante cifrado para garantizar la privacidad de los usuarios.

## Tecnologías Utilizadas

- **Lenguajes de Programación**: Kotlin para Android, Swift para iOS.
- **Frameworks y Librerías**: Android SDK, iOS SDK, y librerías específicas para la gestión de NFC y Bluetooth.
- **Backend**: Firebase para almacenamiento y autenticación de usuarios.
- **Gestión de Dependencias**: Gradle para Android, CocoaPods para iOS.

## Instalación

### Requisitos Previos

- Android Studio para desarrollo en Android.
- Xcode para desarrollo en iOS.
- Dispositivos móviles con soporte para NFC y Bluetooth.

### Pasos para la Instalación

1. Clona el repositorio en tu máquina local.
    ```bash
    git clone https://github.com/usuario/nombre-del-repositorio.git
    ```
2. **Para Android**:
    - Abre el proyecto en Android Studio.
    - Configura el proyecto con tu clave API de Firebase.
    - Compila y ejecuta la aplicación en un dispositivo o emulador compatible.
3. **Para iOS**:
    - Abre el proyecto en Xcode.
    - Configura el proyecto con tu clave API de Firebase.
    - Compila y ejecuta la aplicación en un dispositivo o simulador compatible.

## Uso

1. Abre la aplicación en ambos dispositivos móviles.
2. Selecciona la información que deseas compartir en la sección de configuración de la tarjeta de visita.
3. Acerca los dispositivos para iniciar el intercambio de datos mediante NFC o Bluetooth.
4. Verifica que la transferencia se ha realizado correctamente en ambos dispositivos.

## Contribuciones

Las contribuciones son bienvenidas. Por favor, sigue los siguientes pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-caracteristica`).
3. Realiza los cambios necesarios y haz commit de los mismos (`git commit -m 'Agrega nueva característica'`).
4. Sube los cambios a tu repositorio (`git push origin feature/nueva-caracteristica`).
5. Abre un Pull Request para revisión.


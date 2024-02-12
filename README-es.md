# Proyecto React Native

Este proyecto es una aplicación React Native que consta de dos pantallas:

1. **Screen1**: Esta pantalla muestra un mensaje de bienvenida y una imagen. También tiene un botón para acceder a la segunda pantalla.
   
2. **Screen2**: En esta pantalla, los usuarios pueden ingresar dos números y luego presionar un botón para dividirlos. El resultado de la división se muestra debajo de los campos de entrada.

## Instrucciones de Ejecución

1. Clona este repositorio en tu máquina local.
2. Asegúrate de tener instalado Node.js y npm en tu sistema.
3. Abre una terminal en la carpeta del proyecto y ejecuta el siguiente comando para instalar las dependencias:

   ```bash
   npm install
   ```

4. Para ejecutar la aplicación en un emulador o dispositivo físico, asegúrate de tener configurado un entorno de desarrollo para React Native. Luego, ejecuta el siguiente comando:

   ```bash
   npx react-native run-android
   ```

   o

   ```bash
   npx react-native run-ios
   ```

## Estructura del Proyecto

- **src/**
  - **components/**: Contiene componentes reutilizables.
  - **screens/**: Contiene las pantallas de la aplicación.
  - **navigation/**: Contiene la configuración de navegación.

## Dependencias

Este proyecto utiliza las siguientes dependencias principales:

- **React Native**: Plataforma de desarrollo móvil basada en JavaScript.
- **@react-navigation/native**: Biblioteca de navegación para React Native.
- **@react-navigation/stack**: Navegador de pila para React Navigation.

## Contribución

Si deseas contribuir a este proyecto, siéntete libre de crear pull requests y reportar problemas.

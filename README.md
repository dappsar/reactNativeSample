# Ejemplo Aplicación en react-native

## Requerimientos

### Software base

- nodeJs ([Install nodeJs with NVM! ([Windows](https://docs.microsoft.com/en-us/windows/nodejs/setup-on-windows) / [Linux-Mac](https://nodesource.com/blog/installing-node-js-tutorial-using-nvm-on-mac-os-x-and-ubuntu/))
- [Android Studio](https://developer.android.com/studio/index.html)
- [xCode](https://developer.apple.com/xcode/) (for Mac)
- [Java JDK](https://docs.oracle.com/javase/10/install/installation-jdk-and-jre-microsoft-windows-platforms.htm#JSJIG-GUID-A7E27B90-A28D-4237-9383-A58B416071CA)


### Configuración

Para android, es necesario aceptar (por línea de comando) las licencias del SDK

```bash
# Ejecutar el siguiente comando
cd $ANDROID_HOME
tools/bin/sdkmanager --licenses
```


### Paquetes de NPM

```bash
# Instalar react-native-cli
npm install -g react-native-cli
```

## Ejecutar aplicación

## Desktop

```bash
npm start
```

## IOS

```bash
react-native run-ios
# o
#  react-native run-ios --simulator="iPhone 8 Plus"
```

## Android

```bash
react-native run-android
```

Para ejecutar en un dispositivo real, seguir las instrucciones de [aquí](https://facebook.github.io/react-native/docs/running-on-device).


---

## Big ToDo

- Offline data storage with AsyncStorage
- Working with third-party APIs
- Maps
- Splash Screens
- Navigation
- Redux (for state management)
- Redux Saga and Persist
- Tests and TDD
- Push notifications
- UI Animations
- Build and publish your app
- Continuous Delivery or CI

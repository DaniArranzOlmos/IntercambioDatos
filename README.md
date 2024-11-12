# 📱 Proyecto Android - Intercambio de Datos entre Actividades con Intents en Java

Este proyecto en Android Studio está diseñado para practicar y comprender cómo intercambiar datos entre actividades utilizando `Intents` en aplicaciones Android con Java. Los `Intents` no solo permiten la navegación entre actividades, sino también el paso de datos entre ellas.

## 📝 Descripción

En este proyecto, se implementa una aplicación sencilla que utiliza `Intents` para intercambiar datos entre dos actividades. El objetivo es demostrar cómo enviar datos de una actividad a otra y cómo recibir esos datos en la actividad de destino.

### 🔧 Funcionalidades

- **Navegación entre actividades**: Desde la actividad principal, se inicia una segunda actividad utilizando `Intent`.
- **Enviar datos a otra actividad**: Se usa `putExtra` para pasar datos (como un texto o número) desde la actividad principal a la segunda actividad.
- **Recibir datos de la actividad destino**: En la segunda actividad, se recibe el dato utilizando `getIntent()` y `getStringExtra()`, luego se muestra el dato en un `TextView`.

## 🛠️ Tecnologías utilizadas

- **Android Studio**: Entorno de desarrollo integrado (IDE) para el desarrollo de aplicaciones Android.
- **Java**: Lenguaje de programación utilizado para desarrollar la aplicación.
- **Android SDK**: Herramientas necesarias para el desarrollo de aplicaciones Android.

## 🚀 Instrucciones para ejecutar el proyecto

1. Clona este repositorio en tu máquina local:

   ```bash
   git clone https://github.com/DaniArranzOlmos/IntercambioDatos.git

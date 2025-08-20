# ConversorMonedas
Aplicación de consola en Java que obtiene tasas de cambio en tiempo real desde una API y permite conversiones entre múltiples monedas

 Características
✅ Obtiene tasas de cambio en tiempo real desde ExchangeRate-API

✅ Conversión entre 6 pares de monedas diferentes

✅ Interfaz de consola intuitiva y amigable

✅ Manejo de errores y validación de entradas

✅ Almacenamiento en caché de tasas para mejor performance

✅ Código modular y bien estructurado

📋 Requisitos del Sistema
Java JDK: versión 11 o superior

Biblioteca Gson: 2.10.1 o superior

IDE: IntelliJ IDEA Community Edition (recomendado)

Conexión a Internet: para obtener tasas actualizadas

 Instalación y Configuración
Clona o descarga el proyecto

Configura las dependencias - Asegúrate de tener Gson en tu classpath:

Descarga Gson desde: https://github.com/google/gson

O usa Maven/Gradle para gestionar la dependencia

Compila el proyecto:

bash
javac -cp .:gson-2.10.1.jar ConversorMonedas.java
Ejecuta la aplicación:

bash
java -cp .:gson-2.10.1.jar ConversorMonedas
 Uso de la Aplicación
Al iniciar, verás un menú con las opciones de conversión disponibles

Selecciona una opción del 1 al 6 para conversiones o 7 para salir

Ingresa el monto que deseas convertir

La aplicación mostrará el resultado de la conversión

Presiona Enter para volver al menú principal


 Monedas Soportadas
USD: Dólar Estadounidense

ARS: Peso Argentino

BRL: Real Brasileño

COP: Peso Colombiano

 API Utilizada
La aplicación utiliza la API de ExchangeRate-API para obtener tasas de cambio actualizadas.

Endpoint: https://v6.exchangerate-api.com/v6/API_KEY/latest/USD

Formato de respuesta: JSON

Actualizaciones: Las tasas se actualizan cada hora






# Oracle Convertidor de Divisas

Este es el primer desafío de backend de la Academia de ALURA LATAM.

Este programa es un conversor de monedas que utiliza la API de ExchangeRate-API para obtener tasas de cambio actualizadas y realizar conversiones entre diferentes monedas.

## Funcionalidades

- Conversión entre múltiples monedas, incluyendo:
  - Dólar estadounidense (USD)
  - Peso argentino (ARS)
  - Real brasileño (BRL)
  - Peso colombiano (COP)
  - Colón costarricense (CRC)
  - Won surcoreano (KRW)
  - Yen japonés (JPY)
  - Yuan chino (CNY)
- Interfaz de usuario basada en texto con un menú de opciones.
- Validación de entradas del usuario para evitar errores.
- Manejo de errores al obtener tasas de cambio o procesar datos.

## Tecnologías utilizadas

- Java
- Gson (para parsear JSON)
- HttpClient (para realizar solicitudes a la API)
- ExchangeRate-API (para obtener tasas de cambio)

## Cómo usar el programa

1. Clona el repositorio:

git clone https://github.com/sumforthefool/oracleConvertidorDeDivisas.git

2. Configura la clave API:

- Obtén una clave API gratuita o de pago de ExchangeRate-API.
- Reemplaza el valor de API_KEY en el código con tu clave.

3. Compila y ejecuta el programa:

- Puedes usar un IDE como IntelliJ IDEA o compilar y ejecutar desde la línea de comandos.

4. Sigue las instrucciones del menú:

- Selecciona la opción de conversión deseada.
- Ingresa la cantidad que deseas convertir.
- El programa mostrará el resultado de la conversión.

## Limitaciones

- El programa utiliza la versión gratuita de ExchangeRate-API, que tiene un límite de solicitudes.
- La precisión de las tasas de cambio depende de la API de ExchangeRate-API.
- El programa no tiene una interfaz gráfica de usuario.

## Mejoras futuras

- Implementar una interfaz gráfica de usuario (GUI).
- Permitir al usuario configurar la clave API y la URL base de la API desde un archivo de configuración o como argumentos de línea de comandos.
- Agregar soporte para más monedas.
- Mejorar el manejo de errores y excepciones.

## Contribuciones

¡Las contribuciones son bienvenidas! Si deseas mejorar el programa, puedes crear un fork del repositorio y enviar un pull request.

## Licencia

Este programa se distribuye bajo la licencia MIT.

# Conversor de Monedas 💵💱💶

Este proyecto fue desarrollado como parte del *Challenge Conversor de Monedas*, propuesto por Alura Latam en colaboración con Oracle, dentro del programa ONE de la especialización en *Back-End*.

## Descripción 📝

El **Conversor de Monedas** es una aplicación escrita en Java que permite realizar conversiones entre diferentes divisas, utilizando una API externa que proporciona tasas de cambio en tiempo real. A través de esta herramienta, los usuarios pueden:

- Consultar el valor de una moneda en relación a otra.
- Filtrar las monedas de interés y mostrar resultados claros y comprensibles.
- Consultar un historial de conversiones, incluyendo la marca de tiempo de cada consulta.

El proyecto incluye la integración con una API de tasas de cambio, análisis de respuestas en formato JSON, y almacenamiento del historial de conversiones en un archivo local.

## Características 🌟

- **Conversiones en tiempo real:** Utiliza una API para obtener las tasas de cambio más actualizadas.
- **Historial de conversiones:** Guarda las conversiones previas con marcas de tiempo, permitiendo un seguimiento completo.
- **Interfaz de consola interactiva:** Permite al usuario realizar conversiones mediante un menú fácil de usar.

## Tecnologías Utilizadas 💻

- **Lenguaje de Programación:** Java
- **API de Tasas de Cambio:** API externa para obtener las tasas de cambio entre diferentes monedas en tiempo real.
- **Biblioteca Gson:** Utilizada para analizar la respuesta JSON de la API y convertirla a objetos Java.
- **Control de Versiones:** Git y GitHub para la gestión del código y colaboración en equipo.
- **IDE:** IntelliJ IDEA para el desarrollo y depuración del código.

## Estructura del Proyecto 📂

### Clases y Funcionalidades

- **`Calculos.java`**: Contiene la lógica de las conversiones de monedas. Incluye métodos para almacenar valores de monedas, realizar cálculos y devolver los resultados.

- **`ConsultaConversion.java`**: Encargada de realizar las consultas a la API de tasas de cambio y manejar la respuesta. Aquí se gestiona la comunicación con la API externa.

- **`GeneradorDeArchivos.java`**: Se encarga de almacenar el historial de conversiones en un archivo de texto, registrando la fecha y hora de cada conversión realizada.

- **`Principal.java`**: Es el punto de entrada del programa. Gestiona la interacción con el usuario a través de la consola, presenta un menú y ejecuta las conversiones solicitadas.


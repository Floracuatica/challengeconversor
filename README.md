Conversor de Monedas en Java 💱

Este proyecto es una aplicación de consola desarrollada en Java que permite realizar conversiones entre diferentes monedas utilizando tasas de cambio actualizadas mediante una API externa. Fue creado con fines educativos como parte de mi aprendizaje en programación Java, orientado a objetos con Alura Latam.

🎯 Objetivos del proyecto

Aplicar los conceptos de Programación Orientada a Objetos (POO).
Practicar el uso de clases, interfaces y listas (ArrayList).
Aprender a consumir una API REST utilizando HttpClient.
Implementar un menú interactivo en consola.
Registrar un historial de conversiones con fecha y hora usando java.time.

🧠 Tecnologías y herramientas usadas

Java 17+
Gson (Google Gson Library): para deserializar los datos JSON obtenidos desde la API de tipo de cambio.
java.net.http.HttpClient para consumo de API
java.time.LocalDateTime para marca de tiempo
ArrayList para manejo de historial
Scanner: para capturar entrada del usuario desde la consola.
IDE: IntelliJ IDEA / VS Code

🚀 ¿Cómo usarlo?
Clona este repositorio o copia los archivos .java.
⚠️ Este proyecto requiere una API Key de ExchangeRate-API. Reemplaza el valor de API_KEY en el la clase "OperacionCambioMoneda.java" con tu propia clave.
Ejecuta la clase Principal.java.
Selecciona del menú la conversión que deseas realizar.
Ingresa la cantidad.
¡Listo! El resultado y el historial quedarán registrados en consola.

📌 Monedas disponibles
Dólar (USD) ⇄ Peso Argentino (ARS)
Dólar (USD) ⇄ Real Brasileño (BRL)
Dólar (USD) ⇄ Peso Colombiano (COP)
Dólar (USD) ⇄ Peso Chileno (CLP)
Dólar (USD) ⇄ Peso Mexicano (MXN)
Dólar (USD) ⇄ Yen Japonés (JPY)

📚 Cursos relacionados
Java: aplicando la Orientación a Objetos
Java: trabajar con listas y colecciones de datos
Java: consumir API, escribir archivos y manejar errores

🕘 Ejemplo de historial de conversión
-100.00 [USD] => 86300.00 [ARS] | Fecha y hora: 08-05-2025 16:25:12

-200.00 [JPY] => 1.28 [USD] | Fecha y hora: 08-05-2025 16:27:41

👤 Autora
Rommy Bejar Rivera - Alumna Alura Latam Full Stack Java
Estudiante de programación
Challenge Conversor de Monedas con Java

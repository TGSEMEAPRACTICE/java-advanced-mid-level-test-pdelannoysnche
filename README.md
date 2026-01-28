🛠 Reto Técnico: Procesador de Transacciones Java
Instrucciones:

Implementa una solución que use Java Streams para filtrar y transformar una lista de objetos.

Aplica el patrón de diseño Strategy para la lógica de cálculos/comisiones.

Usa CompletableFuture para simular una tarea asíncrona (ej. una validación externa).

Importante: La clase principal debe llamarse Main.java para que el test automático funcione.

Se valorará el uso de Clean Code, manejo de excepciones y la justificación de las decisiones técnicas en la entrevista.

🚀 Java Technical Challenge: Multi-Source Data Processor
Objetivo: Implementar un módulo de procesamiento de datos que combine múltiples fuentes de forma eficiente.

Requerimientos Técnicos:

Modelo de Datos: Crea una clase Transaction con id, amount, currency y status.

Java Streams: Dada una lista de transacciones:

Filtra las que tengan un amount superior a 50.

Transforma el status a "PROCESSED" usando .map().

Obtén la suma total de los montos filtrados.

Asincronía (CompletableFuture): Simula una llamada a una API externa para validar cada transacción. Debe ejecutarse de forma no bloqueante (asíncrona) y devolver un mensaje de confirmación al terminar todas.

Patrón de Diseño (Strategy): Implementa el patrón Strategy para calcular diferentes comisiones según la moneda (USD tiene 2%, EUR tiene 1%, otras 5%).

Clean Code: El código debe ser legible, usar nombres de variables claros y manejar posibles excepciones (ej. montos negativos).

Entrega: Realiza los "commits" y "push" necesarios en este repositorio de GitHub Classroom antes de la hora acordada.

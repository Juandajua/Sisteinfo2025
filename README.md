# Análisis del video: Funciones Lambda (AWS)
## Resumen general

El video explica de forma sencilla qué es **AWS Lambda**, un servicio de **computación sin servidor** (serverless) que ofrece Amazon Web Services.  
La idea principal es que puedes **ejecutar código sin tener que preocuparte por administrar servidores**.  

## Cómo funciona AWS Lambda

1. **Se escribe una función:**  
   Es decir, un fragmento de código que hace una tarea específica (por ejemplo, procesar una imagen o leer datos de una base).  

2. **Se configura un evento que la activa:**  
   Puede ser la subida de un archivo, una petición HTTP, o una acción dentro de otro servicio de AWS.  

3. **AWS la ejecuta automáticamente:**  
   No se necesita mantener un servidor encendido todo el tiempo.  

4. **Pago por uso:**  
   Solo se cobra por el tiempo y recursos usados mientras la función se ejecuta.

## Conceptos clave que aprendí

- “**Serverless**” no significa que no haya servidores, sino que **el usuario no los administra**.  
- Las funciones deben ser **rápidas y específicas**, porque si duran mucho tiempo o consumen mucha memoria, pueden aumentar los costos.  
- Cada ejecución es **independiente**, no guarda datos de la anterior (es “stateless”).  
- Es ideal para tareas pequeñas o procesos que se activan por un evento (por ejemplo, cuando se recibe un pedido o llega un correo).  

## Limitaciones o puntos a tener en cuenta

- No sirve para procesos que necesitan estar corriendo **todo el tiempo** o que dependen de un estado constante.  
- Puede ser **más caro** si las funciones se ejecutan muchas veces o duran mucho.  
- Se necesita una buena **planificación del flujo de información**, porque no hay un servidor fijo que mantenga el contexto.

## Conclusión

AWS Lambda representa una nueva forma de entender cómo se ejecutan los sistemas de información: **más automatizados, eficientes y adaptables**.  
Como estudiante de Ingeniería Industrial, me parece una herramienta que se conecta mucho con la idea de optimizar procesos, reducir desperdicios y aprovechar los recursos tecnológicos sin tener que ser experto en infraestructura.


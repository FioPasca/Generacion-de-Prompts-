# **Entrega Final- Inteligencia Artificial Generación de Prompts"** #
### Alumna: Fiorella Pasca
### Comisión: 84185

## Problemática:
Muchas personas que desean redecorar su hogar no saben por dónde empezar. Aunque buscan inspiración en redes sociales o sitios web, a menudo esas ideas no se adaptan a sus gustos personales, espacio disponible o estilo preferido. La falta de orientación concreta genera indecisión o resultados insatisfactorios.

Este problema es relevante porque afecta la calidad del entorno cotidiano, el uso eficiente del espacio y la experiencia emocional dentro del hogar. Generar ideas visuales y descriptivas adaptadas a cada usuario facilita la toma de decisiones y aumentaría la satisfacción con la decoración.


## Propuesta de solución:
Se plantea desarrollar una herramienta basada en prompts IA que permita generar recomendaciones personalizadas de ambientación y una imagen realista que represente dicha propuesta.

Prompt texto-texto:
“Sugiereme una ambientación para un dormitorio pequeño con estilo boho chic, tonos off white, marrones y fibras naturales. Preferencias: luz cálida y presencia de plantas.”

Prompt texto-imagen:
“Imagen realista de un dormitorio estilo boho chic con cama de madera clara, textiles off white, decoración en tonos tierra, plantas colgantes y luz cálida natural. Vista frontal.”

Esto permite visualizar y comprender cómo se vería el ambiente con las características pedidas, incluso antes de realizar cambios reales. 


## Viabilidad del proyecto:
La propuesta es factible de implementar en el marco del curso. Se empleará una notebook Jupyter con Python para crear una POC basada en Fast Prompting. El usuario ingresará datos básicos del espacio (tipo, estilo deseado, colores) y el sistema devolverá una recomendación textual + una imagen generada con IA.

No se requiere entrenamiento de modelos, ya que se utilizarán modelos existentes (GenAI). Los recursos disponibles (como el entorno de notebooks y el acceso a modelos mediante API o simulación) son suficientes para validar la idea.

## Técnica de fast prompting utilizada:

Zero-shot Prompting 
Aunque no se le dan ejemplos explícitos (como en few-shot), el modelo está realizando la tarea basándose únicamente en las instrucciones que recibe. No hay pares de entrada-salida previos que le muestren el formato deseado más allá de las propias instrucciones. En este sentido, confía en el conocimiento pre-entrenado del modelo para generar la descripción y luego la optimización para la imagen.

## Instalaciones requeridas para el funcionamiento del python:
google.genai 
Para este proyecto se utilizó google.genai tanto para la creación de texto como de imagen
pandas

## Resultados
La herramienta genera descripciones detalladas de todos los atributos necesarios para lograr la decoración con el estilo solicitado. A su vez, genera  imagenes ilustrativas muy acertadas, que mejoran la experiencia del usuario al poder visualizar los puntos claves del diseño propuesto.


## Conclusión del testeo:
El modelo cumple con lo esperado y permite resolver el problema inicial de forma simple, estética y funcional.

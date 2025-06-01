# 🔍 Introducción
El objetivo de esta práctica es evaluar la usabilidad del prototipo utilizando dos métodos complementarios: la prueba A/B y el cuestionario SUS (System Usability Scale). Esta combinación facilitará la comparación entre dos prototipos y funcionará también como herramienta de coevaluación en el contexto de las actividades en clase.
El proyecto que nos ha tocado evaluar es el del equipo DIU3.PalmeraFosforita. Su proyecto, Kerarqueo, se basa en una aplicación movil para vender productos de ceramica artesanal, ralizar cursillos y eventos sobre la misma.

Sus diseños se pueden encontar aquí: [Prototipo Kerarqueo](https://www.figma.com/proto/RmxUR8LE3bxbivaD4IAYlw/layout_hi-fi?node-id=2-359&t=LVN78XnzukW0aWbK-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1)

# 👥 Users. Elección y características de los usuarios reclutados
Para evaluar la usabilidad de su aplicación hemos elegido 4 personas con diferentes características:
- Una mujer de 50 años con poca experiencia usando tecnología
- Una joven de 19 años con buen manejo de la tecnología
- Un hombre de 40 años con baja experiencia
- Una mujer de 30 con mucha experiencia
- Un hombre de 22 años con buen manejo.
- Una mujer de 21 años con gran experiencia.

A las dos primeras personas evaluan el caso A (la web de Tierra Nazarí), y por tanto, las dos segundas el caso B (la app Kerarqueo). Para llevar a cabo la evaluación, solicitamos la colaboración de personas conocidas cuya experiencia es similar a la de los usuarios ficticios, con el fin de obtener un feedback más preciso y rellenar el cuestionario SUS de forma realista, minimizando así posibles sesgos en los resultados. A continuación, se presenta en una tabla la información de los usuarios ficticios seleccionados para esta actividad:

| 🆔 ID | 👤 Sexo / Edad | 💼 Ocupación | 🌐 Experiencia en Internet | 📱 Plataforma | 🧩 Perfil cubierto | 🧪 Test | 📊 SUS Score |
|------|----------------|--------------|----------------------------|----------------|--------------------|---------|---------------|
| U1   | Mujer / 50     | Secretaria   | Bajo                       | Móvil (Android) | Trabaja como secretaria en un centro de salud y solo usa el móvil para WhatsApp y ver fotos en Facebook. Nunca ha comprado online ni usado apps de compras. Le cuesta adaptarse a cambios tecnológicos. | A       | 68            |
| U2   | Mujer / 19    | Estudiante   | Alto                       | Android, Ordenador | Estudiante de psicología. Lleva desde pequeña utilizando el movil a diario, además de una tablet y un PC. | A       | 80            |
| U3   | Hombre / 22     | Estudiante    | Avanzado                   | Android, Linux  | Está cursando Ingeniería Informática con nosotras, por lo que tiene mucha experiencia con las tecnologías. | A       | 75            |
| U4   | Hombre / 40    | Comercial    | Bajo                       | iOS              | Trabaja en una tienda de electrodomésticos y utiliza su iPhone tan solo para las tareas básicas. | B       | 63            |
| U5   | Mujer / 30     | Ingeniera    | Avanzado                   | Android, Tablet  | Ingeniera de telecomunicaciones que utiliza apps de productividad y compra online. Perfil avanzado y exigente. | B       | 53            |
| U6   | Mujer / 21     | Estudiante    | Avanzado                   | Android, Windows  | Estudiando informática, utiliza mucho su teléfono y su portatil para las prácticas. | B       | 68            |

<br>
<br>


# 🧪 Diseño de las pruebas

## ✅ SUS Questionnaire
Para esta prueba le pedimos a los 4 usuarios del estudio que probaran el prototipo que les había tocado estudiar. Creamos un formulario de google forms (en base al proporcionado por los profesores en el guión de prácticas: https://forms.gle/yww2tnbZj5iQDKkcA) y se lo enviamos a los usuarios. Les pedimos que probaran el prototipo que le habíamos asignado explicándoles antes la idea detrás de cada plataforma y que debían intentar hacer hacer una compra y apuntarse a un taller (o un evento en el caso de Kerarqueo). Tras ello, resolvieron el cuestionario.

Una vez todos los usuarios habían completado el cuestionario descargamos las respuestas en un excel y añadimos una nueva columna que utiliza la formula para calcular la escala SUS de cada usuario (formula explicada en el artículo del guión de prácticas). El excel en formato pdf con estos resultados se puede encontrar en: [SUS Questionnaire](./sus_results.pdf).

<br>

En conclusión, tras hacer las medias, encontramos que la escala SUS para el prototipo A es 74 y la del prototipo B 61. Usando la siguiente escala, para estos usuarios la usabilidad del prototipo A es **buena**, mientras que para el prototipo B **aceptable**.

Escala SUS utilizada:

- 0-25 --> La peor imaginable
- 25-50 --> Muy pobre
- 51-70 --> Aceptable
- 71-80 --> Buena
- 81-100 --> Excelente

<br>


## 👁️ Eye Tracking
Con el objetivo de evaluar la calidad del diseño de la interfaz y determinar qué secciones captan en mayor medida la atención del usuario, se ha utilizado la herramienta RealEye. Esta aplicación genera mapas de calor y gráficas asociadas que indican las zonas donde la mirada del usuario se mantiene durante más tiempo.

Se han llevado a cabo dos pruebas correspondientes al caso B. En el caso A, surgieron una serie de problemas técnicos que se detallan en el documento adjunto. En ese mismo documento puede consultarse un análisis completo del estudio realizado para el caso B. 

 [Eye Tracking](Eye_Tracking.pdf)

<br>


# 🧾 Usability Report de ambos casos

Se ha realizado el Usability Report tanto del caso B como del caso A, en dichos informes detallamos un análisis completo de la usabilidad de ambos casos. 

Los archivos se pueden consultar aqui:
[Report Caso A](Usability-Report-LasTres.md)
[Report Caso B](Usability-Report-PalmeraFosforita.md)

Ambos archivos cuentan con sugerencias de mejora, aqui podemos verlas resumidamente para cada caso:

## Caso A
- Hacer más visible la funcionalidad de compra frecuente, ya que actualmente se encuentra demasiado escondida dentro de la lista de productos
- Permitir aplicar códigos de descuento directamente desde la vista de descuentos, en lugar de obligar al usuario a llegar hasta el carrito final
- Añadir un selector de cantidad antes de añadir productos al carrito, evitando tener que modificarlos dentro de la cesta
- Incluir un pequeño mensaje o tooltip que indique que solo se puede aplicar un descuento por compra
- Añadir una breve guía interactiva o tutorial inicial para usuarios con baja alfabetización digital
  
## Caso B
- Añadir mensajes de confirmación tras completar acciones clave
- Mejorar la jerarquía visual en secciones repetitivas como cursos y eventos
- Implementar filtros funcionales que permitan ordenar el catálogo por tipo, precio, popularidad o fecha.
- Aumentar la información mostrada en los eventos (fechas, plazas, nivel, precio) para facilitar la toma de decisiones del usuario.
- Revisar el uso de botones y formularios para asegurarse de que siempre ofrecen retroalimentación clara.

Si se llevan a cabo estas pequeñas mejoras la usabilidad de la página mejorara notablemente en ambos casos.
<br>


# 🧠 Conclusiones

## A/B testing
En conclusión, en la prueba del A/B testing, nuestro Caso A (Tierra Nazarí), con una puntuación SUS de 74, demuestra buena usabilidad, mientras que el Caso B (Kerarqueo), con 61, indica una experiencia aceptable pero mejorable. Las mejoras sugeridas en los reportes de usabilidad, basadas en el feedback obtenido por parte de nuestros usuarios, facilitarían la navegación y mejorarían la experiencia de usuario. Implementar pruebas de usabilidad continuas y encuestas ayudará a mantener y mejorar la calidad de la aplicación.

## Trabajo desempeñado por el grupo
Tras la realización de esta práctica hemos podido comprobar lo necesarias que son las pruebas de usabilidad y hemos podido autoevaluar el trabajo desempeñado durante el cuatrimestre. Hemos utilizado los materiales proporcionados por el profesorado para realizar las pruebas exceptuando el recurso proporcionado para la prueba del eye tracking.
El trabajo del equipo ha sido bueno, manteniendo una comunicación clara y una asignación de tareas estructurada. Una pequeña dificultad encontrada ha sido el uso de la herramienta Figma para el prototipado ya que no se había usado antes.

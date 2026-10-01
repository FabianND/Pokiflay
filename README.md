# Edwar Fabian Nossa Díaz

Estudiante de Ingeniería Biomédica y técnico en sistemas. Trabajo en análisis de imágenes médicas en formato DICOM, en particular resonancia magnética de columna lumbar, y lo hago con una prioridad clara de que cada resultado sea reproducible, que sus limitaciones queden escritas y que ninguna hipótesis se presente como si ya estuviera demostrada.

## About me

Curso Ingeniería Biomédica en la Escuela Colombiana de Ingeniería Julio Garavito en convenio con la Universidad del Rosario. Mi trabajo técnico se reparte entre el procesamiento de imágenes médicas en Python, la automatización de procesos documentales y el mantenimiento de equipos biomédicos y de laboratorio.

## Proyecto principal: medición automática de la curvatura coronal lumbar en resonancia magnética

La pregunta que guía el proyecto es si resulta posible detectar y medir de forma automática la escoliosis lumbar, definida como un ángulo de Cobb coronal de al menos 10°, en resonancias magnéticas lumbares que se toman de rutina a adultos por otros motivos. Se trata, por lo tanto, de detección oportunista de una curvatura que ya existe en la imagen, y no de predecir quién la desarrollará en el futuro ni de estimar su riesgo de progresión.

El punto de partida es trabajo ya publicado, en especial el de van der Graaf et al. (2024, European Radiology, doi:10.1007/s00330-024-10616-8), que midió el Cobb coronal automáticamente en RM lumbar sagital. Por eso la primera etapa no pretende presentarse como una idea nueva, sino como una reproducción independiente y abierta de ese enfoque a la que se suma una prueba de robustez frente al grosor de corte, la secuencia (T1 o T2) y el centro de adquisición. Esta etapa usa únicamente datos públicos, con SPIDER como conjunto principal, y reporta tanto la concordancia con la referencia como la sensibilidad y la especificidad de la detección.

La herramienta se está construyendo para ejecutarse de forma local, independiente de cualquier plataforma comercial, con entrada en DICOM y salidas en JSON y PDF. Es de uso exclusivo en investigación, no es un dispositivo médico y no cuenta con validación clínica. Las etapas posteriores, que requieren cohortes hospitalarias y lectura de consenso por radiólogos, dependen de establecer colaboraciones institucionales que todavía no existen.

## Formación y certificaciones

Además del pregrado en Ingeniería Biomédica, tengo formación técnica del SENA como Técnico en Sistemas y Técnico en Informática, y certificaciones de Globant en automatización de control de calidad y en el patrón Serenity/Screenplay. Trabajo en español y en inglés (nivel B2).

Contacto
LinkedIn · https://www.linkedin.com/in/fabiannossa/

Estoy abierto a conversar con grupos de investigación, radiólogos e instituciones interesadas en la validación de métodos automáticos de medición en columna.

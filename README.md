
# 🌟 Clasificador de Contenido para Videos – Estrellas App

Este proyecto es una **prueba de concepto** para automatizar la clasificación de contenido audiovisual utilizando modelos de IA de Hugging Face. El objetivo es agilizar y estandarizar el proceso editorial de videos en la plataforma **Estrellas App** https://estrellas.app/.

## 🧩 Descripción del reto y propuesta

La clasificación manual de contenido audiovisual para plataformas como Estrellas representa un desafío significativo debido a su alto costo en tiempo, recursos humanos y riesgo de errores. Este proceso ralentiza la publicación de videos y compromete la coherencia y calidad del contenido mostrado al público. Ante esta situación, surge la necesidad urgente de automatizar el análisis de videos para evaluar su idoneidad, asegurando que cumplan con los estándares editoriales, normativos y de estilo requeridos para su difusión.

El sistema permite al usuario cargar un video desde su dispositivo. Luego, se extraen varios fotogramas del video para ser analizados por un modelo de captioning de imágenes, el cual genera descripciones del contenido visual. Estas descripciones se evalúan para determinar si el contenido es **apto o no para publicación**.

---

## 🚀 Características principales

- 🎥 Análisis automático de videos frame por frame.
- 🤖 Generación de descripciones mediante **IA de Hugging Face** (`blip-image-captioning-base`).
- 🛡️ Clasificación basada en reglas predefinidas sobre las descripciones generadas.
- 📤 Interfaz simple para cargar y analizar contenido.
- 📊 Resultado visual del análisis: **Permitido / No permitido**.

---

## 🛠️ Tecnologías utilizadas

- HTML, CSS y JavaScript (Vanilla)
- Hugging Face Inference API
- Modelo: `Salesforce/blip-image-captioning-base`

---

## 🧠 Flujo técnico

1. 📤 El usuario carga un video o imagen.
2. ⏱️ Si es un video, se extraen fotogramas específicos (1s, 3s, 5s).
3. 🧠 Cada frame es enviado a la API de Hugging Face para generar una descripción.
4. 📋 Las descripciones se evalúan mediante una lista de frases permitidas.
5. ✅ Se muestra el resultado: video **aceptable** o **requiere revisión**.

---

## 📂 Cómo usar

1. Clona este repositorio o abre el archivo HTML en tu navegador.
2. Carga un archivo de video o imagen local desde la interfaz.
3. Observa la descripción generada y el resultado de clasificación automática.

---

## 📎 Requisitos

- Conexión a internet (para acceder a Hugging Face API).
- Un navegador moderno que soporte la API de archivos y reproducción de video.

---

## 📫 Contacto

**Cristóbal Valencia Cerón**  
📱 3005412940  
📧 cristobal@asymmetricfrequency.info
📧 cristobalvalencia3002@gmail.com

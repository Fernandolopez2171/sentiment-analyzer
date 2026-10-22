# Sentiment Analyzer

[English](README.md) | **Español**

## Descripción del proyecto

Este proyecto es un sistema de análisis de sentimientos en redes sociales desarrollado con inteligencia artificial (IA). Recopila datos de redes sociales, analiza el texto para determinar si el sentimiento es positivo, negativo o neutro, y proporciona estadísticas y visualizaciones sobre la opinión de los usuarios en relación con temas específicos o tendencias actuales.

## Estructura del proyecto

### Frontend
- **Framework:** Next.js
- **Estilos:** Tailwind CSS

### Backend
- **Framework para la API:** Next.js
- **IA:** Python

## Funcionalidades principales
1. **Recopilación de datos de redes sociales**
   - API para recopilar comentarios de YouTube.

2. **Análisis de sentimientos**
   - Algoritmos de procesamiento de lenguaje natural (NLP) para analizar textos de publicaciones y determinar el sentimiento.
   - Un modelo de IA previamente entrenado para identificar sentimientos positivos, negativos y neutros.

3. **Estadísticas y visualizaciones**
   - Estadísticas sobre el sentimiento general de los usuarios en relación con temas específicos.
   - Gráficas de barras y mapas de calor para mostrar la distribución del sentimiento.

4. **Interfaz de usuario**
   - Una interfaz intuitiva para explorar los resultados del análisis de sentimientos.
   - Búsqueda de temas específicos, comparación de tendencias y segmentación de datos.

## Instalación

### Prerrequisitos
- Node.js
- Python 3.x
- pip

### Pasos
1. Clona el repositorio:
   ```sh
   git clone https://github.com/Fernandolopez2171/sentiment-analyzer.git
   cd sentiment-analyzer
   ```

2. Instala las dependencias del frontend:
   ```sh
   cd Frontend
   npm install
   ```

3. Instala las dependencias del backend:
   ```sh
   cd ..\Backend
   pip install -r requirements.txt
   ```

## Uso

### Frontend
1. Inicia el servidor de desarrollo:
   ```sh
   cd Frontend
   npm run dev
   ```
2. Abre `http://localhost:3000` en tu navegador.

### Backend
1. Inicia el backend de IA:
   ```sh
   cd ..\Backend\BertModel
   python app.py
   ```

## Review
![Inicio](./Project_Review/Inicio.png)

![API de YouTube](./Project_Review/ApiYoutube.png)

![Gráfica](./Project_Review/Grafica.png)

## Contribuciones

Las contribuciones son bienvenidas. Haz un fork del proyecto, crea una rama para tu funcionalidad, realiza tus cambios, sube la rama y abre un pull request.

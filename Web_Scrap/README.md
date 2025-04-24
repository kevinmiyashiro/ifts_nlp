# Web Scraping con Python

Este Colab demuestra cómo extraer información de páginas web usando `requests` y `BeautifulSoup`. El objetivo es obtener datos estructurados, limpiar texto y generar una nube de palabras a partir del contenido extraído.

## Funcionalidades

* **Extracción de datos:** Se utiliza `requests` para obtener el HTML de una página web y `BeautifulSoup` para analizarlo y extraer información específica.
* **Limpieza de texto:** Se eliminan signos de puntuación, se convierten las palabras a minúsculas y se eliminan las "stop words" (palabras comunes que no aportan información relevante) usando `nltk`.
* **Nube de palabras:** Se utiliza `wordcloud` para generar una visualización de las palabras más frecuentes en el texto extraído.

## Cómo usar este Colab

1. **Abrir en Colab:** Haz clic en el botón "Abrir en Colab" para abrir el notebook en Google Colab.
2. **Ejecutar las celdas:** Ejecuta cada celda del notebook en orden para realizar las diferentes etapas del proceso de web scraping.
3. **Modificar la URL:** Puedes cambiar la URL en la celda correspondiente para extraer información de otras páginas web.
4. **Ajustar la limpieza de texto:** Puedes modificar la lista de "stop words" o las funciones de limpieza de texto para adaptarlas a tus necesidades.

## Librerías utilizadas

* `requests`
* `beautifulsoup4`
* `collections`
* `wordcloud`
* `nltk`
* `re`
* `matplotlib`

## Ejemplo

El Colab incluye un ejemplo de web scraping de la página de Wikipedia sobre Web Scraping en español. Se extrae el texto de los párrafos, se limpia y se genera una nube de palabras.

## Notas

* Este Colab es solo una introducción al web scraping. Hay muchas otras técnicas y herramientas disponibles para realizar tareas más complejas.
* Asegúrate de respetar los términos de uso de las páginas web que scrapeas. Algunas páginas web pueden tener restricciones sobre la extracción de datos.

# INGENIERIA-DE-SOLUCIONES-CON-INTELIGENCIA-ARTIFICIAL
Asistente RAG para Consejería Académica - Duoc UC
## Stack Tecnológico
* **Orquestación:** LangChain / LangChain Community.
* **Modelo de Lenguaje (LLM):** Google GenAI (`gemini-3.6-flash`).
* **Embeddings:** HuggingFace (`all-MiniLM-L6-v2`) para procesamiento vectorial local.
* **Base de Datos Vectorial:** FAISS.
* **Observabilidad y Trazabilidad:** LangSmith (`@traceable`).
* **Entorno de Ejecución:** Google Colab (Python 3.13).

Instrucciones de Ejecución
Sube el archivo .ipynb y la carpeta data/ con sus respectivos PDFs a tu entorno de Google Colab.

Configura tus llaves de API en la sección de Secrets (Llaves) de Colab con los siguientes nombres:

## GOOGLE_API_KEY (Clave obtenida desde Google AI Studio).

## LANGSMITH_API_KEY (Clave de tu cuenta en LangSmith).

Ejecuta las celdas de forma secuencial (del bloque 1 al bloque 4) para cargar las dependencias, procesar los vectores, inicializar la traza y realizar consultas al asistente.

# Clasificación de mensajes de textos con Keras 

Librerías utilizadas: `Pandas`, `Numpy`, `Nltk`, `Matplotlib`,   `Seaborn`, `Scikit-Learn` y `Keras`.

A continuación, se utiliza la biblioteca Keras para clasificar si un mensaje de texto recibido es spam o no. En este desarrollo, se crea una estructura de red neuronal secuencial que incluye una capa de incrustación (embedding) y utiliza redes LSTM para la clasificación. Durante el procesamiento del conjunto de datos, se crean dos datasets: uno donde solo se codifican las etiquetas , y otro donde, además de la codificación de las etiquetas, se realiza un preprocesamiento del texto utilizando la biblioteca NLTK. La misma estructura de red neuronal se utiliza en estos dos conjuntos de datos para comparar con cuál se obtiene un mejor rendimiento. El proceso de tokenización y padding se realiza utilizando la biblioteca Keras.

Enlace al conjunto de datos: https://www.kaggle.com/datasets/team-ai/spam-text-message-classification?resource=download

Para ejecutar el repositorio de forma local se debe crear un entorno virtual con el siguiente comando:

    Python3 -m venv nombre_entorno_virtual

Se debe activar el entorno virtual e instalar todas las librerías especificadas en el archivo “requirements.txt” con el siguiente comando:

    pip install -r requirements.txt

La versión de python utilizada es la siguiente:

    Python 3.10.0

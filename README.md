# RNN-Resumenes-de-Texto

El presente repositorio se refiere a un curso sobre Redes Neuronales Recurrentes, impartido en colaboración con el [Colegio de Matemáticas Bourbaki](https://www.colegio-bourbaki.com/) 

En este repositorio se implementa una red neuronal recurrente para obtener resumenes de opiniones de clientes sobre alimentos finos vendidos por Amazón. La base de datos utilizada esta disponibles en [Kaggle](https://www.kaggle.com/snap/amazon-fine-food-reviews)

La implementación está hecha en Python, en un notebook de Jupyter, utilizando Tensorflow.

La arquitectura de la red comprende tres elementos principales: un codificador, un decodificador y un módulo de atención 

Tanto el codificador como el decodificador requieren que los vectores de entrada pasen por una capa de embedding, en las que se utiliza el modelo word2vec preentrenado con el corpus Google News, mismo que está disponible [este enlace] (https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit?resourcekey=0-wjGZdNAUop6WykTtMip30g)

Para la implementación se han utilizado principalmente las siguientes referencias:

[1]A. F. Bothe, A. Truesdale, y L. Koble, «State Of The Art Text Summarisation Techniques», Humboldt-Universitat zu Berlin, feb. 06, 2020. https://humboldt-wi.github.io/blog/research/information_systems_1920/nlp_text_summarization_techniques/

[1]P. Aravind, «Comprehensive Guide to Text Summarization using Deep Learning in Python», Analytics Vidhya, jun. 10, 2019. https://www.analyticsvidhya.com/blog/2019/06/comprehensive-guide-text-summarization-using-deep-learning-python/ 






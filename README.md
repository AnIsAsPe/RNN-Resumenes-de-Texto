# RNN-Resumenes-de-Texto

**Datos:** 
Amazon Fine Food Reviews disponibles en [Kaggle](https://www.kaggle.com/snap/amazon-fine-food-reviews)

**Bibliotecas:**
- Numpy
- Pandas
- Tensorflow
- Matplotlib



**Arquitectura:** Codificación-Decodificación con Atención utilizanod embeddings pre-entrenados

- *Embeddings* (Vectores Incrustados de palabras) pre-entrenados [GloVe](https://nlp.stanford.edu/projects/glove/) con 100 dimensiones.
- *Encoded*: 3 capas LTSM con 310 dimensiones latentes.
- *Decoder*: 1 Capa utilizando LTSM.
- *Attantion Layer* disponible en este [repositorio](https://github.com/madhav727/abstractive-news-summary).

## Referencias:

[1]A. F. Bothe, A. Truesdale, y L. Koble, «State Of The Art Text Summarisation Techniques», Humboldt-Universitat zu Berlin, feb. 06, 2020. https://humboldt-wi.github.io/blog/research/information_systems_1920/nlp_text_summarization_techniques/

[1]P. Aravind, «Comprehensive Guide to Text Summarization using Deep Learning in Python», Analytics Vidhya, jun. 10, 2019. https://www.analyticsvidhya.com/blog/2019/06/comprehensive-guide-text-summarization-using-deep-learning-python/ 






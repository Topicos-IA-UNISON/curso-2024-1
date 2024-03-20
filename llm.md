---
title: Grandes modelos de lenguaje 
subtitle: Tópicos Avanzados en Inteligencia Artificial 
layout: page
hero_image: /curso-2024-1/img/banner-poema.jpg
hero_darken: true
show_sidebar: false
---

# Temario

1. Modelos secuenciales tipo LSTM
2. Aplicaciones de modelos secuenciales en PLN
3. El mecanismo de atención
4. Transformadores: arquitectura básica y tokenizador
5. Ajuste fino a modelos preentrenados
6. Grandes modelos de lenguaje (LLM)
7. *prompt engineering* y *langchain* para uso de LLM
8. Ajuste fino de LLM con PERF

## Material para el aprendizaje

### Presentaciones

- [Introducción a los modelos secuenciales y celdas LSTM](https://github.com/Topicos-IA-UNISON/curso-2024-1/blob/main/slides/pln-capitulo-2.pptx)  

- [Embeddings from Language Models (ELMo)](http://hanj.cs.illinois.edu/cs512/slides-students2020/Elmo.pdf)

- [El mecanismo de atención y traductores con LSTM](https://github.com/Topicos-IA-UNISON/curso-2024-1/blob/main/slides/atencion-slides.pdf)

- [El modelo de transformadores](https://github.com/Topicos-IA-UNISON/curso-2024-1/blob/main/slides/transformers.pdf)

- [Transfer learning y modelos preentrenados](https://github.com/Topicos-IA-UNISON/curso-2024-1/blob/main/slides/transfer.pdf)

- [Tareas con secuencias largas](https://github.com/Topicos-IA-UNISON/curso-2024-1/blob/main/slides/secuencias-largas.pdf)


### Explicaciones gráficas

- [The Unreasonable Effectiveness of Recurrent Neural Networks (Karpathy, 2015)](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)

- [Recurrent Neural Networks cheatsheet (Amidi y Amidi, 2019)](https://stanford.edu/~shervine/teaching/cs-230/cheatsheet-recurrent-neural-networks)

- [Using Triplet Loss and Siamese Neural Networks to Train Catalog Item Embeddings (Ramachandran, 2021)](https://doordash.engineering/2021/09/08/using-twin-neural-networks-to-train-catalog-item-embeddings/)

- [The Illustrated Transformer (Alammar, 2018)](http://jalammar.github.io/illustrated-transformer/)

- [BERT 101 🤗 State Of The Art NLP Model Explained (Muller, 2022)](https://huggingface.co/blog/bert-101)

- [A Visual Guide to Using BERT for the First Time (Alammar, 2019)](http://jalammar.github.io/a-visual-guide-to-using-bert-for-the-first-time/)

- [The Illustrated GPT-2 (Visualizing Transformer Language Models) (Alammar, 2019)](http://jalammar.github.io/illustrated-gpt2/)

- [How GPT3 Works - Visualizations and Animations (Alammar, 2020)](http://jalammar.github.io/how-gpt3-works-visualizations-animations/)

- [Recent Advances in Language Model Fine-tuning (Ruder, 2021)](https://www.ruder.io/recent-advances-lm-fine-tuning/) 

- [Understanding Locality Sensitive Hashing(LSH): A Powerful Technique for Similarity Search (Joshi, 2023)](https://medium.com/@sarthakjoshi_9398/understanding-locality-sensitive-hashing-lsh-a-powerful-technique-for-similarity-search-a95b090bdc4a)
  
- [LSH Algorithm and Implementation (E2LSH)](https://www.mit.edu/~andoni/LSH/)


- [Intro to Large Language Models (Karpathy, 2023, youtube)](https://youtu.be/zjkBMFhNj_g?si=al3CCBwB5hqQ5kPy)
  
- [LMM Visualization (Bycroft, 2023)](https://bbycroft.net/llm)


## Laboratorios

### LSTM

- [El problema del desvanecimiento del gradiente](https://github.com/Topicos-IA-UNISON/curso-2024-1//blob/main/labs/RNN/vanish-grad.ipynb)

- [Una RNN a pie, solo para entender la arquitectura](https://github.com/Topicos-IA-UNISON/curso-2024-1//blob/main/labs/RNN/Estados-ocultos.ipynb)

- [Análisis de sentimiento con LSTM](https://github.com/Topicos-IA-UNISON/curso-2024-1/blob/main/labs/RNN/LSTM-IMdb.ipynb)


### El mecanismo de atención

- [El mecanismo de atención a pie, solo para entender](https://github.com/Topicos-IA-UNISON/curso-2024-1/blob/main/labs/atencion/atencion.ipynb)
  
- [Modelo *seq-to-seq* con LSTM y mecanismo de atención](https://www.tensorflow.org/text/tutorials/nmt_with_attention?hl=en) de los ejemplos de uso de la documentación de Tensor Flow


- [Modelo *seq-to-seq* con transformadores, haciendo los transformadores mas o menos a pie](https://colab.research.google.com/github/keras-team/keras-io/blob/master/examples/nlp/ipynb/neural_machine_translation_with_transformer.ipynb) de la guías de ejemplos de la documentación de Keras


#### Usando modelos preentrenados


- [A Visual Notebook to Using BERT for the First Tme](https://colab.research.google.com/github/jalammar/jalammar.github.io/blob/master/notebooks/bert/A_Visual_Notebook_to_Using_BERT_for_the_First_Time.ipynb). libreta de [Alammar](http://jalammar.github.io) de la entrada de su blog [A Visual Guide to Using BERT for the First Time](http://jalammar.github.io/a-visual-guide-to-using-bert-for-the-first-time/)

- [Clasificación de textos con transformers](https://colab.research.google.com/github/topicos-ia-unison.github.io/curso-2024-1/blob/main/labs/atencion/transfer-hf.ipynb). Modificación de [esta libreta que ya no funciona](https://colab.research.google.com/github/somosnlp/nlp-de-cero-a-cien/blob/main/4_transformers_aprendizaje_por_transferencia/clasificacion_de_textos.ipynb), del curso [Curso NLP de 0 a 100](https://somosnlp.org/recursos/curso-de-nlp-de-0-a-100) de la [Sesión 4: Transformers y Aprendizaje por Transferencia](https://somosnlp.org/nlp-de-cero-a-cien/sesion-04)


## Artículos seminales

- [Long Short-Term Memory (Hochreiter y Schmidhuber, 1997)](https://deeplearning.cs.cmu.edu/F23/document/readings/LSTM.pdf)

- [Understanding LSTM -- a tutorial into Long Short-Term Memory Recurrent Neural Networks (Staudemeyer y Morris, 2019)](https://arxiv.org/abs/1909.09586)

- [Neural Machine Translation by Jointly Learning to Align and Translate (Bhadanau et al, 2014)](https://arxiv.org/abs/1409.0473)

- [Attention Is All You Need (Vaswani et al, 2017)](https://arxiv.org/abs/1706.03762)

- [Deep contextualized word representations (Peters et al, 2018)](https://arxiv.org/pdf/1802.05365)

- [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding (Devlin et al, 2018)](https://arxiv.org/abs/1810.04805)

- [Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer (Raffel et al, 2019)](https://arxiv.org/abs/1910.10683)

- [Reformer: The Efficient Transformer (Kitaev et al, 2020)](https://arxiv.org/abs/2001.04451)

- [Switch Transformers: Scaling to Trillion Parameter Models with Simple and Efficient Sparsity (Fedus et al, 2022)](https://arxiv.org/pdf/2101.03961.pdf)


## Sitios y herramientas interesantes

- La de base si estás en tensorflow: [*Keras*](https://keras.io)

- Para NLP, está [*Keras NLP*](https://keras.io/keras_nlp/), la cual es una librería que funciona en forma nativa con Tensorflow, JAX y/o pyTorch. En general ayuda a establecer un flujo de trabajo tanto de entrenamiento como de puesta en producción de procesos de NLP. Muy pensada para el uso y ajuste fino de modelos preentrenados.

- Si estás haciendo PLN con modelos profundos, no es posible vivir sin conocer a fondo [Hugging Face](https://huggingface.co). Es una compañía que mantiene un entorno de desarrollo abierto, una colección de modelos preentrenados, y una librería (la librería de transformadores mñas importante al momento), así como facilidades para poner los modelos en producción.

- Para recursos específicos en español, *Hugging Face* mantiene una rama en los países que hablamos español, [Somos NLP](https://somosnlp.org). Muy recomendable. Incluye una bolsa de trabajo (muy centrada en España por el momento, pero que esperamos crezca).
 
- La [Sociedad Española para el Procesamiento del Lenguage Natural (SEPLN)](http://www.sepln.org) es una de las organizaciones científicas en el área de informñatica más antiguas de España, y mantiene una revista desde 1983. Información interesante, acceso gratuito a la revista, congresos, hackatones. Todo muy español, pero con muchos lazos en Latinoamñerica y en espacial con México.

- [LagChain: Get your LLM application from prototype to production](https://www.langchain.com), su [documentación](https://python.langchain.com/docs/get_started) y si [repositorio de GitHub](https://github.com/langchain-ai/langchain)

## Filosofía, sociedad, implicaciones éticas y sociales

- [Language models and linguistic theories beyond words](https://www.nature.com/articles/s42256-023-00703-8)

- [GPTs are GPTs: An Early Look at the Labor Market Impact Potential of Large Language Models](https://arxiv.org/abs/2303.10130)

- [Yann LeCun and Andrew Ng: Why the 6-month AI Pause is a Bad Idea (Video)](https://www.youtube.com/live/BY9KV8uCtj4?si=ZmGJWo6ERkLwQdRg) 

- Consideraciones éticas del uso de LLM en medicina:
  - [Attention is not all you need: the complicated case of ethically using large language models in healthcare and medicine](https://www.sciencedirect.com/science/article/pii/S2352396423000774)
  - [Ethics of large language models in medicine and medical
research](https://www.thelancet.com/journals/landig/article/PIIS2589-7500(23)00083-3/fulltext)

- [Generative Conversational AI And Academic Integrity: A Mixed Method Investigation To Understand The Ethical Use of LLM Chatbots In Higher Education](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4548263)

- [Student Use Cases for AI: Start by Sharing These Guidelines with Your Class](https://hbsp.harvard.edu/inspiring-minds/student-use-cases-for-ai)




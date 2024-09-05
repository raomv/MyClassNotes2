---
title: Introducción al Machine Learning y las Redes Neuronales
description: Preguntas fundamentales e introductorias al machine learning
date: 2024-09-05 00:20:37 -0300
category: Machine-Learning Redes-Neuronales 
tags:
  - markdown
  - jekyll
---

## El origen del nombre

Las redes neuronales se llaman así porque están inspiradas en la estructura y funcionamiento de las neuronas biológicas. En nuestro cerebro, las neuronas reciben señales a través de sus dendritas, las procesan en el cuerpo celular y luego envían una respuesta a través del axón. Las redes neuronales artificiales imitan este proceso. Tienen nodos (neuronas) que reciben varias entradas, las procesan y generan una salida, similar a cómo una neurona biológica procesa señales eléctricas.

Un modelo simplificado de esto es el perceptrón, una unidad básica de una red neuronal que realiza cálculos con las entradas y aplica una función de activación para generar una salida. Con suficientes perceptrones interconectados en capas (entrada, ocultas y salida), estas redes pueden realizar tareas complejas como el reconocimiento de patrones en imágenes o la predicción de resultados.

## ¿Como se entrenan las redes neuronales?

In all new posts it is necessary to add Front Matter at the beginning of the file. It will override any previously set default value.

```yaml
---
title: Post Title
description: Description of the post
date: YYYY-MM-DD HH:MM:SS +/-TTTT
category: category
tags: tag
---
```

### Standard Layout

In this theme, the post layout was set to `post` by default, so there is no need to add the _layout_ variable in the Front Matter block.

### Date and Time Zone

To precisely define the time at which a post was published, it is recommended to define the _date_ variable with date, time and time zone.

### Categories and Tags

Categories and tags serve to separate subjects by specific topics. They have specific pages.

The categories and tags page can be accessed through the following urls, respectively:

https://yourdomain/categories

https://yourdomain/tags

## Post banner

If you want a banner to be displayed at the beginning of the post, simply add the variable _image_ and its attributes _path_, _alt_ and _caption_.

### Example of Front Matter with Image

```yaml
---
title: Post Title
description: Description of the post
date: YYYY-MM-DD HH:MM:SS +/-TTTT
image:
   path: "path/to/banner/post"
   alt: "Alt text for post banner"
   caption: "Caption for the post banner"
category: category
tags: tag
---
```
---
title: Introducción al Machine Learning y las Redes Neuronales
description: Preguntas fundamentales e introductorias al machine learning
date: 2024-09-05 00:20:37 -0300
category: Machine-Learning Redes-Neuronales 
tags:
  - markdown
  - jekyll
---

## Concepto de inteligencia artificial

El concepto de "inteligencia artificial" fue acuñado por primera vez en 1956 por el científico informático estadounidense John McCarthy y otros tres académicos. Se definió para referirse a las máquinas que pueden ser mejoradas para asumir capacidades que se consideran similares a la inteligencia humana, tales como aprender, adaptarse y autocorregirse. En otras palabras, un sistema de teorías, métodos, técnicas y aplicaciones que puede imitar y extender el comportamiento humano, como percibir el entorno, adquirir conocimiento y obtener resultados óptimos.

La inteligencia artificial (IA) tiene diferentes significados y percepciones desde las perspectivas pública y académica. El público y los medios muestran un gran entusiasmo por la "inteligencia artificial general", como C-3PO en la película Star Wars o el T-700 en Terminator. Esta máquina omnipotente tendría todo tipo de percepciones y racionalidad, pudiendo pensar de manera abstracta, comprender ideas complejas, planificar y resolver problemas tan rápidamente como los seres humanos. Sin embargo, actualmente, estamos en la fase de investigación de la "inteligencia artificial estrecha", una tecnología que puede realizar una tarea específica tan bien o mejor que los humanos.

## Redes Neuronales Artificiales: ¿Cómo funciona la IA por dentro?

Las redes neuronales se llaman así porque están inspiradas en la estructura y funcionamiento de las neuronas biológicas. En nuestro cerebro, las neuronas reciben señales a través de sus dendritas, las procesan en el cuerpo celular y luego envían una respuesta a través del axón. Las redes neuronales artificiales imitan este proceso. Tienen nodos (neuronas) que reciben varias entradas, las procesan y generan una salida, similar a cómo una neurona biológica procesa señales eléctricas.

En el corazón de una red neuronal está el perceptrón, un modelo matemático que simula cómo funcionan nuestras neuronas biológicas. Podemos imaginarlo como una red de neuronas artificiales, cada una recibiendo entradas y decidiendo si "disparar" o no, en función de la información que recibe. Imagina que el perceptrón tiene varias entradas (como diferentes características de una imagen o de un sonido), cada una de ellas con un "peso" asignado, que determina su importancia. Luego, se suman todas esas entradas ponderadas y se compara con un valor umbral. Si la suma supera ese umbral, el perceptrón "dispara" (emite una salida), de lo contrario no lo hace. Este proceso básico se puede representar con la fórmula:

```latex
a = 
\begin{cases}
0 & \text{si } \sum_{i=1}^{n} w_i x_i + b \leq 0 \\
1 & \text{si } \sum_{i=1}^{n} w_i x_i + b > 0
\end{cases}
```

## ¿Como se entrenan las redes neuronales?



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
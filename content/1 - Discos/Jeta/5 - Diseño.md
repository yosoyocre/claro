---
title: "5 - Diseño"
draft: false
tags:
  -
---
## Enso  
[https://es.wikipedia.org/wiki/Ens%C5%8D](https://es.wikipedia.org/wiki/Ens%C5%8D)  
El término ensō (円相) es una palabra japonesa que significa círculo y que está fuertemente relacionada con el zen. Se trata de uno de los temas más típicos de la caligrafía japonesa, a pesar de que el círculo es un símbolo y no un carácter. Simboliza la iluminación, la fuerza, la elegancia, el universo y el **vacío** (mu),  
…  
Algunos artistas pintan el ensō con una abertura en el círculo, mientras que otros completan el círculo. Para los primeros, la abertura puede simbolizar distintas ideas, por ejemplo, que el ensō no es una figura separada, sino que es parte de algo más grande, o que **la imperfección es un aspecto esencial e inherente de la existencia** (como ocurre también en la idea de **simetría rota**). El principio de controlar el equilibrio en **la composición a través de la asimetría y la irregularidad** es un aspecto importante en la estética japonesa: **fukinsei** (不均斉), **la negación de lo perfecto**.
## Cianotipia  
[https://es.wikipedia.org/wiki/Cianotipia](https://es.wikipedia.org/wiki/Cianotipia)
## Collages de David Hockney  
De Polaroids

![[Polaroids de David Hockney.png]]

O de vídeos  

<iframe width="560" height="315" src="https://www.youtube.com/embed/wfHFebXBbbk?si=I3uiO3c4h-IHKT1L" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Tipografía de e1000_

![[Tipografía e1000__.jpg]]

## Tom Sachs

Me mola la idea que tiene de construir cosas complejas a nivel de ingeniería utilizando materiales y técnicas de bricolaje, como si su trabajo fuese un hobby, una aproximación a lo real, un fracaso bonito.

![[Tom_Sachs_1.jpg]]

![[Tom_Sachs_2.jpg]]

![[Tom_Sachs_3.webp]]

## Internet en los 90

Molaba explorar la estética de las páginas de GeoCities de los 90 / 00s, la paleta de 256 colores, Windows 98, etc.

Seguir estos pasos para conseguir un efecto de gradiente de ordenadores antiguos

https://www.instagram.com/reel/DAujA_OMZfk/?igsh=bWI5bmNlZ2M4OXEz


## Chindogu

Objetos que cubren funciones del día a día pero mal, raro

https://en.wikipedia.org/wiki/Chind%C5%8Dgu

Similar al concepto de chindogu, está la obra de [Allan Wexler](https://en.wikipedia.org/wiki/Allan_Wexler)
https://hyperallergic.com/allan-wexler-magnifies-the-absurdity-of-the-everyday/

Podría tratar de construir un **Chindogu digital**

Podría instalar un TinyLlama en mi servidor usando Ollama
https://chatgpt.com/share/691d8c9e-89dc-8009-8375-47e978801cf1

Como el modelo funciona muy mal, podría usarlo para diseñar la portada.

Podría pedir un concepto al usuario y, con eso lo que me dé TinyLlama, rellenar de palabras la portada.

La pregunta al usuario podría ser "Describe un problema que tengas en menos de X palabras" y poner un ejemplo como "me pica la espalda" o "tengo depresión".

El Chindogu digital podría entonces proponer una solución al problema. Como si fuese un **mal terapeuta** o un mal amigo.

Podría ser como un coaching empresarial. La pregunta puede ser relacionada con el trabajo.
El resultado podría ser un cartel inspiracional, de pocas palabras.

Igual es necesario entrenar a TinyLlama en un nuevo dataset propio pero ¿cuál usar? y ¿de dónde lo saco para que sea suficientemente grande, con más de 1.000 ejemplos?. Lo ideal sería entrenarlo en frases motivacionales pero ¿existe una base de datos así en internet?

Podría haber un número limitado de respuestas y TinyLLM podría analizar la temática de la frase que se le da y elegir una respuesta correspondiente. Entonces solo sería un problema de clasificación de frases.

ChatGPT me dice que puedo utilizar un tiny LLM preentrenado en español como ALBETO o DistillBETO. Estos LLM no reciben prompts, porque son solo encoders. Lo que hacen es calcular *embeddings* (un vector de números reales que representa el significado de un texto en un espacio matemático continuo) de cada palabra de un texto. Podemos, por lo tanto, calcular el *mean pooling* (la media de los embeddings de las palabras de una frase) de una frase de entrada, calcular el mean pooling de cada una de las frases motivacionales (o de la categoría del problema a resolver, tipo "Motivación en el deporte") y escoger la frase o categoría que esté más cerca en cuanto a su similitud coseno (mide el ángulo entre vectores porque eso nos da si están en la misma dirección y, por lo tanto, si su significado es parecido).

Quizá podría usar, para cada categoría, una frase que describa un problema típico de esa categoría, o usar palabras clave de esa categoría. ChatGPT propone algo así:

`CATEGORIES = {`
	`"motivacion": "me siento desmotivado en el trabajo",`
    `"estres": "tengo demasiado estrés laboral",`
    `"conflicto": "problemas con compañeros de trabajo"`
`}`

Ejemplos de fases motivacionales
https://www.cosmopolitan.com/es/consejos-planes/familia-amigos/a44105565/frases-motivacion-animo/

# Ideas
![[Idea diseño jeta.m4a]]

![[Idea diseño Jeta 3.m4a]]

![[Idea diseño Jeta 4.m4a]]

![[Idea diseño Jeta 5.m4a]]

![[Idea diseño Jeta 6.m4a]]

![[Idea diseño Jeta 7.m4a]]

![[Idea diseño Jeta 8.m4a]]

![[Idea diseño Jeta 9.m4a]]

![[Idea diseño Jeta 10.m4a]]

![[Idea diseño Jeta 11.m4a]]

![[Idea diseño Jeta 12.m4a]]

![[Idea diseño Jeta 13.m4a]]

![[Idea diseño Jeta 14.m4a]]

![[Idea diseño Jeta 15.m4a]]

![[Idea diseño Jeta 16.m4a]]

# Web de las que sacar las imágenes

https://publicdomainreview.org/
https://pdimagearchive.org/
https://www.nga.gov/
https://digitalcollections.nypl.org/
https://picryl.com/
https://www.publicdomainsherpa.com/public-domain-photographs.html
https://en.wikipedia.org/wiki/Wikipedia:Public_domain_image_resources
# Conceptos para las imágenes
Accident
Atlas
Automata
Business
Businessman
Computer
Exhausted
Factory
Golem
Guillotine
Hell
Jail
Labour
Laziness
Office
Oppression
Panoptic
Protest
Puppet
Rich
Riot
Robot
Sisyphus
Slavery
Sloth
Technology
Tired
Wealthy
Work
# Pruebas

![[jeta.png]]
![[jeta2.png]]
![[jeta3.png]]
![[jeta4.png]]![[jeta5.png]]![[jeta6.png]]![[jeta7.png]]![[jeta8.png]]![[jeta9.png]]![[jeta10.png]]![[jeta11.png]]![[jeta12.png]]![[jeta13.png]]![[jeta14.png]]![[jeta15.png]]![[jeta16.png]]![[jeta 1.png]]
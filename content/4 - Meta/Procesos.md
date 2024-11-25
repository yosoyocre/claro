---
title: Procesos
draft: false
tags:
---
## Pasar imágenes a texto

Por ahora, la mejor forma que he encontrado es pasarle la imagen a **ChatGPT** y pedirle que la transcriba. Funciona muy bien.

También usé un OCR de la aplicación web OCR2EDIT:

https://www.ocr2edit.com/es/

Utilizo la opción "AI-OCR+ Avanzado", que limpia la imagen y reconoce mejor los textos que fotografío, y defino "Español" como idioma.

Si me pide que me pase al plan Premium, abro una nueva ventana de incógnito y lo intento de nuevo.

Aunque hay bastantes textos que le cuesta transcribir, he visto que funciona mejor que usar el OCR [[https://github.com/tesseract-ocr/tesseract|teserract]]

```
tesseract fichero - -l spa --psm 6
```
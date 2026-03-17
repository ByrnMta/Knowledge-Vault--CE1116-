---
Fecha de creación: 2026-03-12 01:54
Fecha de Modificación: 2026-03-12 01:54
tags:
  - "#ia"
Tema:
---


## 📚 Idea/Concepto 

La tokenización es un proceso mediante el cual el lenguaje natural, ya sean palabras, subpalabras o caracteres, es descompuesto en partes pequeñas. A estas partes se les llaman tokens. A dichos tokens se les asigna un valor numérico (ID’s) mediante un vocabulario. Este vocabulario es controlado por algoritmos como el Byte Pair Encoding (BPE), que permite procesar las palabras desconocidas descomponiéndolas en fragmentos presentes en él. Este proceso debe ser bidireccional para lograr la reconstrucción del texto original a partir de los ID’s (decode). Los valores numéricos obtenidos se transforman en vectores (embeddings), sobre los cuales las redes neuronales pueden operar matemáticamente, estos se deben de complementar con codificaciones posicionales para que el modelo comprenda el orden de secuencia. De forma adicional, para el manejo de lotes y límites de contexto, los vocabularios contemplan tokens especiales, como los de relleno o delimitadores.
## 📌 Puntos Claves (Opcional)
- Descomposición de texto.
- Asignación numérica.
- Manejo de un vocabulario a través de algoritmos (BPE).
- Bidireccionalidad para reconstrucción.
- Generación de embeddings.

## 🔗 Connections
- [[ Embeddings]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 
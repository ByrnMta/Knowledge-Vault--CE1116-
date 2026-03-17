---
Fecha de creación: 2026-03-14 23:57
Fecha de Modificación: 2026-03-14 23:57
tags:
  - ia
Tema:
---


## 📚 Idea/Concepto 

La ventana de contexto es la cantidad máxima de tokens que el mecanismo de auto-atención de un modelo puede procesar simultáneamente en un paso de inferencia. Esta memoria de trabajo tiene un límite rígido (hard-coded): cuando se supera, la información más antigua se excluye completamente, volviéndose inaccesible para generar la respuesta. El consumo de la ventana incluye no solo los mensajes del usuario, sino también el prompt de sistema y datos externos. Su gestión es crítica porque el costo computacional escala cuadráticamente (duplicar tokens requiere cuatro veces más procesamiento) y el rendimiento decae en fenómenos como lost in the middle, donde información en el centro de contextos extensos es ignorada.
## 📌 Puntos Claves (Opcional)
- Posee un límite hard-coded.
- Excluye información al superar el límite.
- No solo contabiliza el límite por entradas de usuario, también lo hace con el prompt de sistema.
- Costo computacional cuadrático.
- Aparición de Lost in the Middle en contexto extensos.

## 🔗 Connections
- [[Mecanismos de Atención]]
- [[Arquitecturas Transformer]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 
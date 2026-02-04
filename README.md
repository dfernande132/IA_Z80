# Inteligencia Artificial para el Z80 

**"Si puedes construirlo en 8 bits, realmente lo entiendes"**

Este repositorio contiene los programas y recursos del libro **"Inteligencia Artificial para el Z80: La ciencia de la computación en BASIC"**, escrito por **José Daniel Fernández Santos**. 

Aquí encontrarás el código fuente diseñado para ZX Spectrum (clásico y Next) que permite explorar desde los fundamentos de la computación hasta las redes neuronales modernas, todo bajo la arquitectura del mítico procesador Zilog Z80.

---

## 📖 Sinopsis del Libro
¿Es posible unir la simplicidad cruda del BASIC de los años 80 con la sofisticación teórica de la Inteligencia Artificial? Este libro demuestra que sí. 

A través de un procesador Z80, realizaremos un viaje didáctico para desmitificar la IA, rompiendo la "caja negra" de los algoritmos actuales. Aprenderás a optimizar código, gestionar memoria y construir, línea a línea, algoritmos de regresión, clasificación y redes neuronales. Es una obra destinada a programadores, entusiastas de lo retro y estudiantes que quieran comprender la esencia de la computación sin las distracciones de las librerías modernas.

---

## 📂 Contenido del Repositorio
Este repositorio es un complemento para los lectores del libro. Los archivos están organizados por capítulos para facilitar el seguimiento de las lecciones.

### Formatos de archivo:
* **`.bas.txt`**: Archivos de texto plano. Ideales para leer el código en un PC, copiar fragmentos o estudiar la lógica sin necesidad de un emulador.
* **`.bas`**: Archivos en formato de sistema **+3DOS**. Listos para ser cargados directamente en un **ZX Spectrum Next o 128K**, emuladores o grabados en disquetes/tarjetas SD.
* **`.tap`**: Archivos de cinta, preparados para cargarlos en un ZX Spectrum clásico o en un emulador.
  
### Política de uso:
Estos archivos se comparten para que quienes han adquirido el libro puedan realizar todas las pruebas que deseen, modificar el código y experimentar con los parámetros de los algoritmos a su antojo. ¡La mejor forma de aprender es rompiendo y reconstruyendo el código!

---

## 🚀 Listado de Programas por Capítulo

### Parte I: Fundamentos y Herramientas
* **Capítulo 1**: `bernoulli.bas` (El primer algoritmo: Ada Lovelace).
* **Capítulo 2 (Algoritmia)**: 
    * Laboratorios de eficiencia: `pasos.bas`, `pasos2.bas`, `pasos3.bas`.
    * Visualización: `drawG.bas`.
    * Ordenación: `bubble.bas`, `shell.bas`, `quick.bas`, `quickR.bas`.

### Parte II: IA Clásica (Simbólica)
* **Capítulo 3 (Sistemas Expertos)**: `inferencia.bas` (Motor de inferencia para diagnóstico).
* **Capítulo 4 (NLP)**: `eliza.bas` (Implementación del famoso chatbot conversacional).
* **Capítulo 5 (Búsqueda Heurística)**: `juegoAleatorio.bas`, `juegoArbol.bas` y `juegoMinimax.bas` (Evolución de la IA para el 3 en raya).

### Parte III: Aprendizaje Supervisado
* **Capítulo 6 (Regresión Lineal)**: `moa.bas` (Análisis de tendencias de CO2).
* **Capítulo 7 (Clasificación k-NN)**: `knn.bas` (Clasificador de vecinos más cercanos).
* **Capítulo 8 (Naive Bayes)**: `naiveBayes.bas` (Clasificación probabilística).

### Parte IV: Aprendizaje No Supervisado
* **Capítulo 9 (Clustering)**: `k-means.bas` y `clasificacion.bas` (Agrupamiento de datos).

### Parte V: Redes Neuronales
* **Capítulo 10 (El Perceptrón)**: 
    * `elOjoDeLaMaquina.bas` (Reconocimiento de formas con una neurona).
    * `vemosCincos.bas` (Reconocimiento del dígito 5).
* **Capítulo 11 (Redes Multicapa)**:
    * `sigmoide.bas` (Calculo de LUT de la sigmoide).  
    * `multiClase.bas` (Sistemas multicapa).
    * `entrenamientoDigitos.bas` y `visor.bas` (Backpropagation en 8 bits).
    * `predDigiFILE.bas` (Reconocedor de dígitos con carga del modelo desde fichero).
    * `predDigiDATA.bas` (Reconocedor de dígitos con carga del modelo desde DATA).

### Parte VI: Simulación y Vida
* **Capítulo 12**: `JuegoVida` (El Juego de la Vida de Conway).

---

## 🛠️ Requisitos Recomendados
Aunque muchos programas funcionan en un Spectrum 48K/128K estándar, para los capítulos de Redes Neuronales y Regresión se recomienda el uso de un **ZX Spectrum Next** (o emuladores como CSPECT o ZESARUX) para aprovechar la velocidad de 28 MHz y reducir los tiempos de entrenamiento.

---
**¡Espero que disfrutes explorando la inteligencia artificial en su forma más pura!**

## ¡Feliz codificación! 📟

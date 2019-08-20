## Universidad Austral de Chile

# INFO133: Base de Datos

### Responsable: Matthieu Vernier, mvernier@inf.uach.cl

La prueba se divide en 2 partes: preguntas y trabajo práctico.

Parte "Preguntas":
- Responderán en una hoja. 
- No podrán consultar internet o documentos, excepto los notas que tomaron en clase.
- Sus respuestas estáran sintéticas. Cuidarán evitar utilizar frases de más de 20 palabras.

Parte "Práctica":
- Desarrollarán un script Python, idealmente utilizando Jupyter Notebook.
- Podrán consultar internet o documentos.
- Enviarán su trabajo en su cuenta GitHub al final de la prueba. 

## 1. Preguntas (3 puntos)

1. Supongamos que un modelo de clasificación permite obtener la matríz de confusión siguiente. ¿Calcular la precisión y el recall por cada categoría?

X | Predicción(A) | Predicción(B) | Predicción(C)
---------------|---------------|---------------|---------------
A | 80 | 36 | 21
B | 24 | 131 | 6
C | 4 | 5 | 108


2. Describir el algorítmo de Regresión Logística, explicando lo que aprende y cómo aprende, mencionando conceptos asociados (sin explicarles)

3. Describir el algoritmo de Árbol de decisión, explicando lo que aprendre y cómo aprende, mencionando conceptos asociados (sin explicarles)

4. ¿Cuál es el interés del Algoritmo Random Forest en comparacion con los algoritmos de arboles de decisión?


## 2. Trabajo práctico (3 puntos): Piedra Hoja Tijeras

Queremos desarrollar una máquina capaz de ganar al juego "Piedra Hoja Tijeras" anticipando el gesto del adversario.
Suponemos que tenemos acceso a datos de sensores EMG (electromigrafía) que miden en tiempo real la actividad muscular del adversario.

Tenemos a nuestra disposición un dataset que contiene observaciones de 3 tipos de gestos: piedra (0), hoja (1) y tijeras (2).
Por cada observación, tenemos acceso a 8 sensores musculares y se recopila 8 mediciones de cada sensor justo antes de que el jugador revele su gesto. Es decir, tenemos 64 mediciones por cada observación.

Descargar [dataset](https://github.com/magister-informatica-uach/INFO268/tree/master/unidad1/prueba2/dataset-prueba2.csv) 


Queremos aprender un modelo de clasificación capaz de predecir que gesto va a hacer el jugador. 

1) Desarrollar un script python para entrenar y evaluar al menos 3 modelos de clasificación distintos, limpiando o transformando los datos si lo estiman necesario.
2) ¿Qué precisión y recall obtiene?
3) ¿Cómo se comporta los puntajas de precisión y recall según el tamaño del dataset de entrenamiento? 
Probar con varios tamaño de dataset de entrenamiento y graficar las curvas de Precicion o Recall según el tamaño del dataset de entrenamiento. ¿Qué observan? 



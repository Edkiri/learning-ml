[Aprende Inteligencia Artificial - Dot CSV](https://www.youtube.com/watch?v=KytW151dpqU&list=PL-Ogd76BhmcC_E2RjgIIJZd1DQdYHcVf0)

# Intro
  - La IA comunmente se divide en dos partes. AI Débil y AI Fuerte. Las débiles pueden realizar solamente una tarea, mientas que las fuertes pueden aplicarse a una gran variedad de escenarios y problemas diferentes.
  - Actualmente todas nuestras IAs se encuentran en el primer grupo.
  - Se podría definir la inteligencia artificial como el campo de la informática que busca crear máquinas que 'imiten' comportamientos inteligentes.
  ## Campos de estudio dentro de la IA:
    - Robótica.
    - Voz.
    - NPL (Natural language processing)
    - Visión.
    ### Machinne Learning.
      - Es el campo de la IA que estudia cómo dotar a las máquinas de capacidad de aprendizaje.
      - Entendido como (Generalización del conocimiento en base a un conjunto de experiencias).
      - Puede usarse en todos los campos de estudios.
      #### Estos se clasifican en 3 paradigmas:
        - Aprendizaje supervisado.
        - Aprendizaje no supervisado.
        - Aprendizaje reforzado.
      #### Existen diferentes técnicas que se usan para cubrir diferentes tipos de aplicaciones.
        - Árboles de decisión.
        - Modelos de regresión.
        - Modelos de clasificación.
        - Técnicas de clusterización (Agrupar datos similares en conjuntos distintos).
        - Redes neuronales (capaces de aprender de forma gerarquizada).
          - Lo logran mediante algoritmos por capas. Las primeras capas aprenden conceptos básicos como qué es un tornillo, y las capas posteriores manejan conceptos más complejos como automóvil.
          - La tendencia de estos algoritmos es que cada vez tengan más capas. Dando fama al concepto de:
          - ##### >>> Deep Learning <<<

## Paradigmas de aprendizaje
  - Usa el cerebro humano como inspiración.
  - Estudia los mecanismos que tenemos los humanos para percibir la realidad y cómo procesamos esas percepciones y las convertimos en conocimiento.
  - ### Se han clasificado en:
    - ##### Aprendizaje supervisado
      - Se basa en conseguir la relación existente entre unas variables de entrada y otras variables de salida.
      - Es el paradigma que más aplicación práctica ha tenido en la última década.
    - ##### Aprendizaje no supervisado
      - Es aquel que genera conocimiento únicamente a partir de los datos de entrada.
      - Busca patrones de similitud en los datos.
      - Es difícil comprobar la eficacia de sus resultados.
      - Señala un futuro muy prometedor en el campo de la IA.
    - ##### Aprendizaje reforzado

## Modelos para entender una realidad caótica
  - "Un modelo no es más que una construcción conceptual simplificada de una realidad más compleja"
  - Tres elementos claves:
    - 1. Los datos
      - Es nuestra toma de contacto con la realidad. Las mediciones que hacemos de ella. 
      - Con ellos sacamos toda la información para construir nuestro modelo.
      - Los datos son multidimensionales. 
      - Siendo un conjunto de datos 'x' y 'y' como 2D y 'x', 'y' y 'z' como 3D.
      - El Deep Learning se aplica a problemas que tiene decenas, miles, millones de parámetros, es decir, 9999D.
    - 2. Parámetro
      - Dicta la flexibilidad del modelo. 
    - 3. El error
      - Para medir la precisión del modelo.
      - Podemos ajustar los parámetros del modelo para conseguir el mínimo error. A este proceso se le conoce como entrenamiento o ajuste del modelo.
  
## Regresión lineal y mínimos cuadrados ordinarios
  - Es la base de la estadística y del Machinne Learning.
  - Al analizar una serie de pares ordenados 'x' y 'y', el modelo de regresión lineal busca la función de la línea recta que mejor se ajuste a los datos, permitiendo predecir nuevos valores de 'y' a partir de nuevos valores de 'x'.
  - En el caso de tres parámetros, el modelo de regresión lineal busca la función del plano que mejor prediga nuevos valores.
  - Se utiliza el 'error cuadrático medio' (ECM) para medir la precisión del modelo.
  - Mediante la derivada de la función del error cuadrático medio, podemos encontrar el mínimo, lo que nos permite determinar los coeficientes que minimizan dicho error. Estos coeficientes son seleccionados de manera que ajusten mejor el modelo a los datos observados, logrando así una predicción más precisa. 

## Descenso del gradiente
  - Para buscar el mínimo global de una función, el algoritmo del descenso del gradiente mide la pendiente alrededor de un punto y elige continuar un paso hacia la dirección más pronunciada. La magnitud de este paso está determinada por el producto del ratio de aprendizaje 'x' y la pendiente.
  - Divergir significa que el algoritmo puede alejarse en lugar de acercarse al mínimo global de la función de costo, resultando en una falta de convergencia y en la incapacidad de encontrar la solución óptima. En otras palabras, un ratio de aprendizaje demasiado grande puede hacer que el algoritmo oscile o incluso se aleje de la solución óptima en lugar de converger hacia ella.
  - 'x' se le denomina el ratio de aprendizaje. La elección adecuada de este valor es crucial, ya que un valor muy pequeño puede hacer que el proceso de convergencia sea lento, mientras que un valor muy grande puede causar que el algoritmo diverja.
  - Todo este proceso se utiliza para la optimización de modelos de machine learning, donde el descenso del gradiente ajusta los parámetros del modelo para minimizar la función de costo, permitiendo que el modelo se adapte de manera más efectiva a los datos de entrenamiento.

## Redes neuronales
  - La unidad más pequeña de estas redes se les denomina neurona.
    - #### Neuronas
      - Es la unidad básica de procesamiento dentro de una red neuronal.
      - Como una función matemática, las neuronas reciben unos datos de entrada y generan unos datos de salida.
      - Realiza una suma ponderada de los datos de entrada, donde la ponderación está determinada por los pesos asignados a cada conexión.
      - Los pesos indican la intensidad con la que cada parámetro afecta a la neurona.
      - Las neuronas comúnmente aplican una función de activación a la suma ponderada más el sesgo para introducir no linealidades en la red y permitir su capacidad de aprendizaje de patrones más complejos.
    - #### Capas
      - Las redes neuranales se dividen en capas.
      - Cada una de estas capas tienen diferentes nueronas.
      - A la primera capa, donde están los datos de entrada, se le denomina capa de entrada. A la última, capa de salida. Y a las capas del medio se les llama capas ocultas.
      - Cada una de las neuronas de una capa, reciben la información de todas las capas anteriores.
      - Igualmente, todas las neuronas de una capa pasan su salida a todas las neuronas de la capa siguiente. 
      - Estructurando las capas y neuronas de forma secuancial conseguimos que las capas posteriores obtengan la información de forma gerarquizada. Ya que la información que recibe por ejemplo la capa 2 ya ha sido procesada por la capa 1, consiguiendo así la resolución de problemas complejos.
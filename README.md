# Mechatronic-Engineering-Topics-Homework1
Resolución de diferentes problemas de Machine Learning utilizando Python

# Mechatronic-Engineering-Topics-Homework1

En este portafolio se compartirá la resolución de una tarea del curso de Tópicos de Ingeniería Mecatrónica, la cual fue resuelta usando Python. Los archivos de Python tienen formato .ipynb por lo que se necesita Python y Jupyter Notebook para poder ejecutarlos.



# Autor
- **Alejandro Muñoz**

* [LinkedIn](https://www.linkedin.com/in/alejandromz2/)

# Descripción de la tarea

El trabajo esta dividido en 4 preguntas, cada pregunta fue respondida usando Python y Jupyter Notebook 
   
## 1.1 Pregunta 1.
Considerar los datos que se brindan en el archivo datos regresion train.csv, donde la primera columna corresponde a los atributos, y la segunda columna a los valores deseados. Desarrollar un modelo de regresión que se ajuste a los datos. Mostrar la función de costo en función del número de iteraciones. Evaluar el desempeño del modelo usando los datos de datos_regresion_test.csv, a través del MSE. Dado que es un modelo de una sola variable, graficar, además, los datos reales junto con los datos que se predice.
Lectura de datos: Se leeran los datos para el entrenamiento y el testeo del ejercicio 1. En este modelo no consideramos necesario normalizar nuestros datos.

### Gráfico de la función real vs la función resultante de la predicción:
![image](https://github.com/alejandromz2/Mechatronic-Engineering-Topics-Homework1/assets/30611516/4bf2889a-9cea-414e-9431-4a8f8b95749c)

### Optimización de parámetris usando Descenso del Gradiente:
#### Gráfico de la función de costo vs el número de iteraciones:
![image](https://github.com/alejandromz2/Mechatronic-Engineering-Topics-Homework1/assets/30611516/00291683-eaf0-49a1-b22c-592ffeee62b9)

#### Gráfico de la función real vs la función resultante de la predicción (Descenso del Gradiente):
![image](https://github.com/alejandromz2/Mechatronic-Engineering-Topics-Homework1/assets/30611516/55e787a2-8378-4006-bce5-54e8377f0d30)

## 1.2 Pregunta 2. 
Descargar los archivos housing.data y housing.names del repositorio UCI Machine Learning Repository. El primer archivo contiene varios atributos relacionados con el precio de casas en
Boston; y el segundo archivo contiene la descripción de lo que representa cada columna. Los datos deben ser divididos de manera aleatoria en un 80 % para entrenamiento y un 20 % para prueba, aproximadamente. Usar regresión lineal (multivariable) para encontrar el modelo de predicción, visualizando el comportamiento de la función de costo. Utilizar el conjunto de prueba generado, para validar el funcionamiento del modelo, usando alguna métrica.
### Gráfico de la función de costo vs el número de iteraciones:
![image](https://github.com/alejandromz2/Mechatronic-Engineering-Topics-Homework1/assets/30611516/a3ae6945-1190-4b2e-ab64-dadc5dae7003)

### Métricas de evaluación:
MSE es: 18.923
MAE es: -1.012
MAPE es: -0.087
RMSE es: 4.35
El coeficiente de determinación es: 0.76129

## 1.3 Pregunta 3.
El archivo datos clasificacion.csv tiene tres columnas: las dos primeras representan los dos atributos x1, x2, y la última columna representa la clase y a la cual pertenece la instancia, donde y {0, 1}. Dividir los datos en conjunto de entrenamiento y conjunto de prueba (usando el criterio 80 %-20 %). Entrenar un clasificador basado en regresión logística para clasificar los datos. Dado que la curva de decisión es no lineal, se usará bases polinomiales que incluirán combinaciones de ambos atributos hasta el sexto grado. Estos atributos se obtienen usando la función generacion bases. Además, el clasificador debe tener un término de regularización L2. Graficar los puntos y la frontera de decisión (se puede usar las funciones plot data y plot frontera). Igualmente, graficar la función de costo para verificar que converge.

### Gráfico de los datos normalizados:
![image](https://github.com/alejandromz2/Mechatronic-Engineering-Topics-Homework1/assets/30611516/8a6043d1-e59d-4b55-8dc2-ce2ee69f9b9c)

### Evolución de función de costo:
![image](https://github.com/alejandromz2/Mechatronic-Engineering-Topics-Homework1/assets/30611516/43000a2a-ac29-45cf-a9fc-722dd6bfba91)

### Clasificación de datos clase 1 y clase 0:
![image](https://github.com/alejandromz2/Mechatronic-Engineering-Topics-Homework1/assets/30611516/239022bf-b337-4cfb-a746-561509c37244)

### Testeo del modelo (Gráficos normalizados):
![image](https://github.com/alejandromz2/Mechatronic-Engineering-Topics-Homework1/assets/30611516/0f1559e5-66f0-45c2-84d4-63cd8ee1547f)

### Testeo del modelo (Aplicación del clasificador a los datos normalizados):
![image](https://github.com/alejandromz2/Mechatronic-Engineering-Topics-Homework1/assets/30611516/26d9d56e-9d34-4a3f-8061-552005691d85)


# Instalación
Descarga estos archivos como un zip usando el boton verde, o clona el repositorio en tu máquina usando Git. 
Los programas tienen el formato .ipynb y necesitan Jupyter Notebook y Python para ser ejecutados.

# Información Adicional
Si tienes dudas sobre algún tema en especifico referente a este laboratorio escribeme a alejandrozevallos.218@gmail.com. 

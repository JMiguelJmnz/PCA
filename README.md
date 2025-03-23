# PCA

Analisis de componentes principales para generar conclusiones de agrupaciones de acuerdo a diversas categorias aplicado a los datos de Iris

Comenzamos cargando las librerías necesarias y los datos que utilizaremos para realizar el análisis de componentes principales.
<br>![image](https://github.com/user-attachments/assets/69d59b8a-3499-4f3c-9900-32f9ec62972a)

Separamos los primeros dos componentes en el DataFrame para realizar la evaluación y hacemos el conteo de renglones
<br>![image](https://github.com/user-attachments/assets/c8ad9dc7-4dfe-420c-a68b-750b49b0618f)
<br>![image](https://github.com/user-attachments/assets/a1100441-0cb6-4f29-80de-e2cf3f6edd3c)

Estandarizamos los valores que tenemos
<br>![image](https://github.com/user-attachments/assets/6383fb3e-42de-4c92-894c-4f44ff3504ee)

Calculamos la matriz de correlaciones
<br>![image](https://github.com/user-attachments/assets/4f5bcf76-950c-4561-8c99-8edd86cd110c)

En este punto podemos realizar el entrenamiento del modelo PCA, extraemos los eigenvalores y el porcentaje de varianza
<br>![image](https://github.com/user-attachments/assets/191cedee-2a07-4f82-8909-ddfd86a3daed)

Calculamos los eigenvectores para poder hacer la representación
<br>![image](https://github.com/user-attachments/assets/e17d70fd-6573-446c-9ab0-6c3fd9847ad2)

Realizamos la proyección seguido de la graficación para visualizar esta información
<br>![image](https://github.com/user-attachments/assets/f3dbe856-d376-45e7-83bf-c184cc815dc9)
<br>![image](https://github.com/user-attachments/assets/1372d7f1-37f8-4007-8c1c-9f5be88a1d71)

Por último realizamos la graficación de los componentes para observar la forma en la que se relaciona la información
<br>![image](https://github.com/user-attachments/assets/ff2c0a43-8b30-447c-b0ff-a97349aee249)

Con los gráficas finales podemos ver como las observaciones se dividen principalmente en dos grupos y podemos relacionarlo con la ubicación de los factores en el siguiente gráfico.
<br>![image](https://github.com/user-attachments/assets/904ddbd9-7e8e-433f-9581-00fd132bea0f)

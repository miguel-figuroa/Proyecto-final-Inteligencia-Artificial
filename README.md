# Proyecto-final-Inteligencia-Artificial
 Dos Métodos de regresión para la estimación de la cantidad de ingresos a las películas estrenadas desde 1902 hasta 2017.

# Proyecto-final-Inteligencia-Artificial

## Integrantes:
Natalia Rodriguez Prado-
Miguel Ernesto Figueroa Salas
             
## Introducción del proyecto
En el presente proyecto se presentan 2 métodos de regresión para la estimación de la cantidad de ingresos a las películas estrenadas estrenadas desde 1902 hasta 2017. Este conjunto tiene características de entrada como: presupuesto, ingresos, fechas de estreno, productora, país, recuento de voto, votos promedio, entre otras. Tambíen contiene archivos con veinti seis millones de calificaciones de doscientos setenta mil usuarios para las cuarenta  y cinco mil peliculas. Estas calificaciones están a una escala de 1 a 5.  El dataset se obtiene en Kaggle en: (https://www.kaggle.com/rounakbanik/the-movies-dataset). 

## Desarrollo:
Por medio de phyton y sus librerias se realizo la extracción y procesamiento del conjunto de datos pasando de aproximadamente treinta mil datos a siete mil muestras. Seguido a esto se implemento dos métodos de regresion, el primero, Regresion Lineal y el segundo, Regresión mediante Soporte Vectorial con el objetivo de poder predecir cual es la película que tendrá mayor ingresos (Revenue).

## Resultados
Regresión lineal

![image](https://user-images.githubusercontent.com/91579735/171971001-5afed3dc-c452-402b-b77e-5224e091dda4.png)
![image](https://user-images.githubusercontent.com/91579735/171971006-a6194217-7dde-451a-b153-50cca9cfdd29.png)

Regresión mediante soporte vectorial

![image](https://user-images.githubusercontent.com/91579735/171970970-7c0b76ab-c7d9-4e7f-8335-787deccae0eb.png)
![image](https://user-images.githubusercontent.com/91579735/171970974-e1fd1bb6-e8be-4747-9fbe-e1a15b57e26e.png)
![image](https://user-images.githubusercontent.com/91579735/171970982-0bb7e66e-05b1-48da-9aaf-b00facd2a2c5.png)


## Conclusiones
Se logro determinar con exito que película tuvo el mayor ingreso la cual dio como resultado "The samurai" con: para conjunto de entrenamiento R2
0.6225006477171241 y para conjunto de Validación R2 0.6040854106550964.

## Link al video de youtube en el readme.md
https://youtu.be/axZ59waKVG8

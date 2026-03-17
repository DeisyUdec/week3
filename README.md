# week3
Estudiante: Deisy Yazmin Murcia Diaz


Actividad:
Implementación de mediante backpropagation y el uso de funciones de activación.

Objetivo: Crear un programa en python en donde se evidencia la implementación de una red nuronal con funciones de activación como sigmoid y ReLu, ademas donde sea visible el proceso de ajustes de parametros.


A continuación se da a conocer como se implemento el desarrollo del código:
1. se importaron las librerias
2. se crearon los arreglos de variables de entrada y salida segun la compuerta lógica del AND.
3. Se crea un método Sigmoid den donde convierte los valores de la funcion en 0 o 1 
4. se deriva la función anterior.
5. se crea el método de ReLu en donde se tienen en cuenta que si el valor es menor a 0 aparece de lo contrario a 1
6. se crea el metodo de activación con una cantidad de 5000 interacciones y taza de parendizaje de 0.1, adicional inicializa los pesos, sesgos de la primera etapa y de la segunda, adicional se crea un ciclo hasta aque se cumpla la cantida de interacciones en donde se * la entrada por el peso y se suma con el sesgo, se activa la función de sigmoid y relu, por ultimo se tiene una actualización de los datos.
7. se muestra los resultados de la salida sogmoid y el relu
8. muestra la predicción de las comparaciones de los dos metodos
9. se crea la gráfica para visualizar el error como se comporta en cada cantidad de interaciones.

Comparaciones: 
Teniendo en cuenta los resultados se puede evidenciar se aplico las comparaciones de sigmoid y ReLU, en el cual segun la margen de error cuando se colocan un valor por debajo de 2500 interacciones hay una margen mayor de errror en la activación de sigmoid segun el ejercicio.


Resultados -Conclusiones: 
Se puede decucir que según la gráfica de error segun la cantidad de interaciones el mejor metodo que se acerca en un tiempo mas minimo es el de ReLu según el ejerccio debido que mas o menos en la interacción de 300 ya bajo su error mas o menos 0.025, en cambio el metodo de Sigmoid segun la misma cantidad de interacciones esta en 0.06 mas o menos teniendo una difernecia de 0.035, pero se puede deducir que los dos metodos son eficientes cuando la cantidad de interacciones son mayores a 3000. 

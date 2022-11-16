# OOP_SP
Segundo Parcial OOP

Description: Este programa busca simular el manejo de un parqueadero donde los usuario pueden reservar puestos en base a sus disponibilidad teniendo en cuenta las restricciones debido a hora y tamaño de su vehiculo.

Descripcion del UML: El UML consta de una clase abstracta  Cars donde esta el metodo abstracto de park() de ella heradan las Clases de Compact,SUV, y Van que con sus propios atributos y completan el metodo park() con sus propios resultados. Siguiente es la clase Parking que contiene como atributo las identificaciones, la cantidad de parqueos para cada tamaño de carro y la lista de puestos reservados.  La ultima clase es la clase Usuario que contiene los atributos de identificación y su tipo de carro junto a un metodo para reservar un puesto utilizando los datos de las clases Car y Parking. 
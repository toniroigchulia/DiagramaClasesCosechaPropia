# DiagramaClasesCosechaPropia

Crea un diagrama de clases UML para representar un programa que administre las relaciones, datos y posibles acciones de los Propietarios, Vehículos y Seguro. 

Las relaciones principales son que los propietarios tienen uno o varios vehículos y por cada uno de los vehículos deben pagar un seguro. 

Del propietario queremos guardar el nombre, la dirección y el número de teléfono, también. Y el propietario puede realizar las acciones de registrar el 
vehículo y pagar el impuesto de su seguro.

Sobre el seguro también como mínimo debemos guardar el tipo del seguro, coste del seguro y la duración del mismo. El seguro debe de poder calcular su coste total 
y renovar el seguro.

Y la clase vehículo debemos guardar su marca, modelo y año. El vehículo puede encenderse, apagarse y acelerar. La clase vehículo debe tener tres tipos de herencia de 
vehículos más específicos: Moto, Camioneta, Coche. La moto debe tener los atributos tipo de motor y número de marchas y puede cambiar de marchas y ajustar la suspensión. 
La camioneta guarda la información de que capacidad de carga tiene y de qué tamaño es la caja de carga y la camioneta puede cargar y descargar la caja de carga. 
Y por último del coche queremos guardar la información de su número de puertas y la potencia del motor, el coche puede cambiar de aceite y cambiar el filtro de aire.

Cada una de las clases debe tener sus respectivos Getters And Setters de cada atributo.

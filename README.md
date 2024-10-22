Actividad 3 Parte 1 – Practica de POO con C#

Crear un sistema que permita registrar vehículos usados para poder venderlos.
Las clases que deben crear son las siguientes:

Vehiculo
• String patente
• String descripcion
• Double precioVentaEsperado
• Marca marca
• Int añoFabricacion
• String modelo
• Int cantPuertas
• Int kilometros
• Bool primeraMano
• Int cantAirbags
• Color color
• TipoCombustible tipoCombustible
• TipoCarroceria tipoCarroceria
• Transmision tipoTransmision
• Direccion tipoDireccion
Las otras clases como, por ejemplo, Marca, Color, TipoCombustible y Transmision tienen solo un atributo
“nombre”.
Al comenzar el programa se deben crear automáticamente estos objetos (pueden agregar otros):
Marcas: Volkswagen, Peugeot, Ford, Renault, Chevrolet, Toyota, Fiat, Citroen.
Colores: Blanco, Negro, Gris claro, Gris oscuro, Azul, Verde, Rojo, Amarillo.
Transmisiones: Manual, Automática, Automática secuencial, Semiautomática.
Direcciones: Hidráulica, Eléctrica, Asistida, Mecánica.
Tipos de carrocerías: Hatchback, SUV, Coupé, Sedan, Camioneta, Pickup.
Tipos de combustible: Nafta, Gasoil, Gas, Eléctrico, Hibrido.
Un ejemplo de un vehículo completo sería:
Patente AB569BB
Descripción: Auto en buen estado con llantas de 15 pulgadas.
Precio Venta Esperado: 150.000
Marca: Volkswagen
Año de Fabricación: 2018
Modelo: Gol 1.6 GL
Puertas: 5
Kilómetros: 80.000

Primera Mano: Sí
Airbags: 2
Color: Negro
Tipo de combustible: Nafta
Tipo de carrocería: Hatchback
Transmisión: Manual
Dirección: Asistida

Crear un programa con todas las validaciones de datos que sean necesarias y con un menú de opciones que
permita:
1. Ingresar un nuevo vehículo
Verifiquen que la patente no exista en el sistema antes de continuar pidiendo los datos.
2. Modificar un vehículo
Buscando por patente, el usuario podrá modificar alguno de los datos del vehículo. Le deben ir
mostrando uno por uno los datos (todos menos la patente) y si ingresa un ‘enter’ queda el dato que
ya tenía, pero si coloca un dato nuevo se actualiza el vehículo. Por ejemplo, mostramos:
Descripción: “Vehículo chocado, pero funciona bien” y coloca un ‘enter’, queda sin modificar ese
dato. Ahora si coloca “Vehículo en buen estado”, cambia la descripción por esta nueva.
3. Eliminar un vehículo
Buscando por patente, podrá eliminar un vehículo del sistema.
4. Ver catálogo
El usuario podrá ingresar un dato cualquiera o dejar en blanco la búsqueda y serán mostrados todos
los resultados que coincidan con el dato a buscar. Si deja en blanco el dato a buscar, se muestran
todos los vehículos. Se deben tener en cuenta todos los atributos, por ejemplo, si coloca “primera
mano” deberían ser mostrados los que cumplan con esa condición.
5. Evaluar Marcas
El sistema mostrará la cantidad de vehículos y el total estimado de venta (suma de todos los precios
de venta estimados) por cada una de las marcas que tengan vehículos en el sistema.
6. Promedios y máximos
El sistema debe informar por pantalla (agrupados por el tipo de combustible) el promedio de
kilómetros, el promedio de años y un cálculo de cuantos kilómetros por año tienen los vehículos
cargados.
Además, deberá informar el más común (el más usado) de los Colores y de los Tipos de carrocería.

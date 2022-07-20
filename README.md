# orders-tech
![img](./assets/MundoPC-UJS.png)

## agregaciones y modificaciones
- Agregar las siguientes entidades con sus atributos.
  - componente (clase abstracta)
    - tipo componente
  - dispositivo de salida (extiende de componente)
    - marca
    - costo
  - dispositivo interno (extiende de componente)
    - marca
    - costo
  - altavoz (extiende de dispositivo de salida)
    - descripcion
    - cantidad
    - fecha ingreso
  - procesador (extiende de dispositivo interno)
    - descripcion
    - cantidad
    - fecha ingreso
  - placabase (extiende de dispositov interno)
    - descripcion
    - cantidad
    - fecha ingreso

- relacionar las nuevas entidades en la creacion de una computadora, y contemplar la opcion de crear mas de una computadora,  agregando los atiributos de cantidad y fecha de creacion, costo(la suma de todos los componentes). 

-  **Historias de usuario:**
  
  1. El usuario puede crear, modificar, eliminar y actualizar cada componente.
  2. El usuario puede agregar(incrementar) la cantidad de un componente.
  3. El usuario puede listar los componentes por su tipo.
  4. El usuario puede realizar una busqueda de un componente por su marca.
  5. El usuario puede listar componentes con los filtros(tipo, cantidad)
  6. El usuario puede listar los componente creadas recienteme (1 dia)
  7. El usuario puede crear una o varias computadores(siempre y cuando los compoenente la cantidad de los componentes no sea cero o menor). 
  8. El usuario puede puede listar las computadoras creadas recientemente (1 dia)
  9. El usuario puede puede listar las computadoras en orden ascendente o descente conforme a la cantidad.
  10. El usuario puede crear una orden de computadoras creadas(actualizar la cantidad de computadoras, y obtener el costo total de la orden). 
  11. El usuario puede listar las ordenes dada una fecha.
  12. El usuario puede actaulizar una orden (actualizar los datos afectados)
  13. El usuario puede listar las ordenes creadas recientemente (1 dia)


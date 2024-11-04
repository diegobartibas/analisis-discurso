# analisis-discurso
universo.nombre=”concesionario”
universo.discurso.comienzo

El universo es un concesionario de automóviles 
De los clientes se conocen los datos habituales también los coches también de los coches de los vendedores y de las ventas
Un coche puede ser recomprado a un cliente.

universo.discurso.fin
#-----------------------------------------------------------
v2
universo.discurso.comienzo

      concesionario de automoviles 
      - cliente:se conocen los datos habituales
      - coche:se conocen los datos habituales
      -vendedor:se conocen los datos habituales
      -venta:se conocen los datos habituales
      
      Un coche puede ser recomprado a un cliente.
      universo.discurso.fin
#-----------------------------------------------------------
v3
universo.discurso.comienzo

      -concesionario(de automoviles)
      -cliente(,,)
      -coche(,,)
      -vendedor(,,)
      -venta(,,)
      -recompra(de coche)(por cliente)
      
universo.discurso.fin
#-----------------------------------------------------------
v4(con diseño)

      - concesionario(de automoviles)
      - cliente(dni, nombre, ape, tf, direccion, ...)
      - coche(numBastidor, matric, año marca, modelo, color )
      - vendedor(numVendedor,,)
      - venta(coche, cliente, vendedor, importe, fecha, ... )
      - recompra(de coche)(por cliente)
        

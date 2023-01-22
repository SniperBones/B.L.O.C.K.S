# B.L.O.C.K.S
Prueba para consumo de API con SpingBoot / MAVEN / PostgreSQL

Blockbuster 

Requerimiento Funcionales:
    - Las peliculas deben tener caracterisiticas como :
        - Titulo
        - Portada(s)
        - Fecha de lanzamiento (Dia en cines)
        - Director
        - Reparto
        - Sinopsis
        - Categorias
        - Calif. RottemTomatoes
        - Cantidad en inventario
        - Precio (Compra / Alquiler)
        - Trailer 

    - Se pueden dar de alta nuevas peliculas
    - Se pueden mostrar las peliculas en inventario 
    - Se puede traer los datos de una pelicula especifica
    - Se pueden eliminar peliculas 
    - Se pueden buscar peliculas y se mostraran coincidencias en titulo , descripcion y categorias 
    - Se puede actualizar el inventario de peliculas (Chocoentrega)

    -Los usuarios tendran informacion como :
        - ID
        - Nombre
        - Apellidos
        - Correo
        - Nombre de ususario 
        - Telefono 
        - Contraseña
        - Direccion
        - (pendiente) Tarjeta de credito 
        - Saldo 

    - Los usuarios se pueden registrar 
    - Los usuarios pueden iniciar sesion 
    - Los usuarios se pueden dar de baja
    - El usuario va a tener una wishlist 
    - El usuario tendra lista de peliculas compradas y alquiladas 
    - Los usuario podran hacer comentarios de las peliculas 
    - El usuario podra recargar saldo desde la pagina 
    - Las peliculas a comprar y alquilar  se agregaran a un carrito :
        - El carrito contara con el total a pagar 
        - Mostrara las peliculas a comprar/alquilar 
        - Se podra eliminar peliculas del carrito
        - Se podra modificar la cantidad de peliculas a comprar/alquilar 
        - Si se alquila se cuenta con 7 dias para devolucion 
        - El costo de alquiler en el carrito sera de 75% del precio total de la pelicula
        - Si el usuario no regresa la pelicula se cobrara el interes de su saldo al regresarla
    - En lista de peliculas alquiladas se contara con un boton de regresar pelicula
    


Requerimientos No Funcionales:
    - Mostrar distintas caratulas
    - Se mostraran recomendaciones para cada usuario 
    - Se agregaran planes para los usuarios 
    - Un sistema de descuentos
    - Un sistema de puntos de compra/alquiler
    - Se agregara metodo de pago 
    - Sistema de regalo (Usuario regala pelicula a usuario)

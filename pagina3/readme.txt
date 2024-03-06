*   En moviles tengo que poner que el ultimo div de la barra de navegacion 
    este centrado en lugar de estar a la derecha (El que tiene lo de messenger y la foto etc)
    -   He puesto justify-content-sm-end y justify-content-center, para que cuando salga del tamaño sm
        se ponga a la derecha pero cuando sea movil se quede centrado.

*   El fs-3 p-3 rounded iba dentro de la clase del i en el menu del medio de la barra superior de nav.

*   Cambiar la clase bi de los iconos a una mas descriptiva y acordarse de la lupa que no tenga los mismos estilos
    -   Le he puesto la clase "pintarfondo" y he creado el estilo para bi con el color del icono.

*   El input en moviles tiene que tener un media query solo para el para que se haga mas pequeño, si no
    descuadra todo.
    -   Hacerlo solo para el tamaño de movil M, el S yo creo que es ridiculo porque no hay moviles asi creo
    
    
-------------------------------------------------------------------------------------------------------------------
                                            03-03
-------------------------------------------------------------------------------------------------------------------

*   He puesto fw-bolder al input de Bilatu, si por lo que sea se descuadra algo, quitarlo.

*   A las historias le he dado un ancho y alto fijo usando scss.

*   En las historias he tenido que poner position-relativa en cada div "principal"
    Luego usando card-img-overlay y moviendolo con flex end lo he llevado al sitio
    Y agregando el tamaño de 50 a la imagen ha quedado medio bien en pc.
    Habra que echarle un ojo al diseño para movil / tablet

**  Al hacer hover en las historias tiene que salir un logo de play y poner HASI
    oscurece la tarjeta por arriba pero por abajo no, hace como un degradado
    COMO HACERLO?? Se puede cambiar la opacidad con css? o mostrarlo? 

*   Mirar las historias al pasar a la version de la tablet etc, el menu de home etc
    queda en todo lo ancho, haciendo mx-md-5 queda mas o menos centrado.
    Mirar como hacerlo y que tamaño dar a las historias y al menu de la izquierda y der.


-------------------------------------------------------------------------------------------------------------------
                                            05-03
-------------------------------------------------------------------------------------------------------------------

**  En la seccion del medio, donde las publicaciones y eso he creado una clase llamada letra
    para pintar las letras del color principal, eso hay que cambiarle el nombre de la clase.

*** Faltan los hover en la seccion central

*******     He creado 2 div, uno a la izquierda del contenido central y otro a la derecha.
            Ambos con col-1 para que la columna de la izquierda y de la derecha valgan 3 espacios
            Así la col de la derecha queda donde esta la del ejemplo

            Tambien he puesto un w-25 a cada historia para que al hacer la pantalla mas pequeña 
            Cada historia tenga un ancho fijo y no quede raro todo. mirar a ver que tal quedan 
            las 2 cosas.
flowchart TD
    Inicio[start] --> id1[\Escoge la opción que quieres llevar a cabo: 1 - Retirar dinero 2- Salir\]
    id1 --> decision{decisión escogida}
    decision --> salir(Salir del programa) --> Fin[End]
    decision --> retirarDinero[\¿Cuánto dinero quieres retirar?\] --> eleccion[/Usuario ingresa dinero/]
    eleccion --> funcionContarDinero(ContarDinero) --> funcionMostrarDinero(MostrarDinero)
    funcionMostrarDinero --> fin[End]
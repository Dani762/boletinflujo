'''mermaid
Flowchart TD
    Inicio[start]
    Inicio --> clasefiguras(Esta clase contiene las funciones de todas las figuras)
    clasefiguras --> calcularAreaTriangulo (Recibe por parámetro los dos números que se le ha pedido al usuario, y con ellos calcula base * altura/2) --> Fin[end]
    clasefiguras --> calcularAreaRectangulo (Recibe por parámetro los dos números que se le ha pedido al usuario, y con ellos calcula lado * ancho) --> Fin[end]
    clasefiguras --> calcularAreaPentagono (Recibe por parámetro los dos números que se le ha pedido al usuario, y con ellos calcula perímetro * apotema/2) --> Fin[end]
    clasefiguras --> calcularAreaHexagono (Recibe por parámetro los dos números que se le ha pedido al usuario, y con ellos calcula perímetro * apotema/2) --> Fin[end]
'''
```mermaid
flowchart TD;
    Inicio[start]
    Inicio --> clasefigura{Esta clase contiene las funciones de todas las figura}
    clasefigura --> CalcularAreaTriangulo --> Fin[end]
    clasefigura --> CalcularAreaRectangulo --> Fin[end]
    clasefigura --> calcularAreaPentagono  --> Fin[end]
    clasefigura --> calcularAreaHexagono --> Fin[end]

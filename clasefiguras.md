```mermaid
flowchart TD;
    A[start]
    A --> B(Esta clase contiene las funciones de todas las figuras)
    B --> C ["Base por altura partido por dos"] --> Fin[End]
    B --> D ["Recibe por parámetro los dos números que se le ha pedido al usuario, y con ellos calcula lado * ancho"] --> E[End]
    B --> G["Recibe por parámetro los dos números que se le ha pedido al usuario, y con ellos calcula perímetro * apotema/2"] --> E[End]
    B --> F ["Recibe por parámetro los dos números que se le ha pedido al usuario, y con ellos calcula perímetro * apotema/2"] --> E[End]
    

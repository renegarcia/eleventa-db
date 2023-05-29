
```mermaid
classDiagram
    Clientesv2 <.. Facturacion
    Ventatickets <.. Articulo
    Caja <.. Ventatickets
    Usuario <.. Ventatickets
    Clientev2 <.. Ventatickets
    Factura <.. Ventatickets
    Turno <.. Ventatickets
    Caja <.. Turno
    Usuario <.. Turno
    Operacion <.. Turno
    class Usuario
    class Turno
```
---
created: 1684912752000
desc: null
id: 66ammrmtr7bdvwf56cg9p3j
title: INVENTARIO_HISTORIAL
updated: 1684912752000
---

```sql
CREATE TABLE INVENTARIO_HISTORIAL (ID TLLAVE NOT NULL,
        PRODUCTO_ID TLLAVE NOT NULL,
        CUANDO_FUE TFECHAHORA NOT NULL,
        CANTIDAD_ANTERIOR TCANTIDAD NOT NULL,
        CANTIDAD TCANTIDAD NOT NULL,
        DESCRIPCION TCADENALARGA,
        COSTO_UNITARIO TMONEDA,
        COSTO_DESPUES TMONEDA,
        AJUSTE_ID TLLAVE,
        RECIBO_INVENTARIO_ID TLLAVE,
        VENTA_ID TLLAVE,
        TRANSFERENCIA_ID TLLAVE,
        CAJA_ID TLLAVE,
        USUARIO_ID TLLAVE,
        ALMACEN_ID TLLAVE,
        VENTA_POR_KIT TBOOLEANO DEFAULT 'f',
PRIMARY KEY (ID));
```
---
created: 1684912752000
desc: null
id: 22m5qifn1wffhmme97wuri1
title: HISTORIAL_INVENTARIO
updated: 1684912752000
---

```sql
CREATE TABLE HISTORIAL_INVENTARIO (ID TLLAVE NOT NULL,
        USUARIO_ID TLLAVE NOT NULL,
        CUANDO_FUE TFECHAHORA NOT NULL,
        TIPO TTIPOMOVIMIENTO NOT NULL,
        HABIA TCANTIDAD,
        CANTIDAD TCANTIDAD NOT NULL,
        CODIGO_PRODUCTO TCODIGOPRODUCTO NOT NULL,
        CAJA_ID TLLAVE,
        TURNO_ID TLLAVE,
CONSTRAINT PK_HISTORIAL_INVENTARIO PRIMARY KEY (ID));
```
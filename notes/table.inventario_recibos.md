---
created: 1684912752000
desc: null
id: 7zme7y6jmk9ejsy4zkkig4n
title: INVENTARIO_RECIBOS
updated: 1684912752000
---

```sql
CREATE TABLE INVENTARIO_RECIBOS (ID TLLAVE NOT NULL,
        FOLIO TLLAVE NOT NULL,
        RECIBIDO_EN TFECHAHORA NOT NULL,
        ORDEN_DE_COMPRA_ID TLLAVE,
        CAJA_ID TLLAVE,
        USUARIO_ID TLLAVE,
        ALMACEN_ID TLLAVE,
PRIMARY KEY (ID));
```
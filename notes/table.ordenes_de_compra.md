---
created: 1684912753000
desc: null
id: 5gs2vv1al3pl2gge9pae96s
title: ORDENES_DE_COMPRA
updated: 1684912753000
---

```sql
CREATE TABLE ORDENES_DE_COMPRA (ID TLLAVE NOT NULL,
        ID_PROVEEDOR TLLAVE,
        FOLIO_ORDEN_PROVEEDOR TCADENAMEDIANA,
        CREADA_EN TFECHAHORA,
        CANCELADA_EN TFECHAHORA,
        ENVIADA_EN TFECHAHORA,
        RECIBIDA_EN TFECHAHORA,
        ESTADO TCARACTER,
        UTILIDAD_ENVIADO TMONEDA,
        IMPUESTOS_ENVIADO TMONEDA,
        SUBTOTAL_ENVIADO TMONEDA,
        TOTAL_ENVIADO TMONEDA,
        UTILIDAD_RECIBIDO TMONEDA,
        IMPUESTOS_RECIBIDO TMONEDA,
        SUBTOTAL_RECIBIDO TMONEDA,
        TOTAL_RECIBIDO TMONEDA,
        NOTAS TCADENAGIGANTE,
        TOTAL_ARTICULOS TINTEGER default 0,
CONSTRAINT PK_ORDENES_DE_COMPRA PRIMARY KEY (ID));
```
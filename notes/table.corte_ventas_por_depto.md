---
created: 1684912752000
desc: null
id: 4p2i18v2wsfwc19awpvz3dp
title: CORTE_VENTAS_POR_DEPTO
updated: 1684912752000
---

```sql
CREATE TABLE CORTE_VENTAS_POR_DEPTO (ID TLLAVE NOT NULL,
        ID_DEPARTAMENTO TLLAVE,
        ACUMULADO_VENTAS TMONEDA,
        ID_TURNO TLLAVE,
        ACUMULADO_GANANCIAS TCURRENCY DEFAULT 0,
CONSTRAINT PK_CORTE_VENTAS_POR_DEPTO PRIMARY KEY (ID));
```
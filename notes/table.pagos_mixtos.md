---
created: 1684912753000
desc: null
id: 33vhq1gw6m9pl26rai4ll3u
title: PAGOS_MIXTOS
updated: 1684912753000
---

```sql
CREATE TABLE PAGOS_MIXTOS (ID TLLAVE NOT NULL,
        TICKET_ID TLLAVE,
        ABONO_ID TLLAVE,
        FORMA_DE_PAGO TCARACTER NOT NULL,
        MONTO TMONEDA NOT NULL,
        REFERENCIA TCADENALARGA,
        CLIENTE_ID TLLAVE,
        CLIENTESV2_CREDITO_ID INTEGER,
CONSTRAINT PK_PAGOS_MIXTOS PRIMARY KEY (ID));
```
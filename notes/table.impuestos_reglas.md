---
created: 1684912752000
desc: null
id: 848xocw2rp84j3hcchc5eoh
title: IMPUESTOS_REGLAS
updated: 1684912752000
---

```sql
CREATE TABLE IMPUESTOS_REGLAS (ID TLLAVE NOT NULL,
        IMPUESTO_ID TLLAVE NOT NULL,
        RECEPTOR_CLAVE_REGIMEN TCADENAMEDIANA,
CONSTRAINT PK_IMPUESTOS_REGLAS PRIMARY KEY (ID));
```
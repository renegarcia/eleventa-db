---
created: 1684912753000
desc: null
id: 3vn3c6gwll434qnlwbu2krb
title: PRODUCTOS_UDF_RECARGAS
updated: 1684912753000
---

```sql
CREATE TABLE PRODUCTOS_UDF_RECARGAS (PRODUCTO_CODIGO TCODIGOPRODUCTO NOT NULL,
        SOPORTA_TELCEL TBOOLEANO DEFAULT 'F' NOT NULL,
        SOPORTA_MOVISTAR TBOOLEANO DEFAULT 'F' NOT NULL,
        SOPORTA_NEXTEL TBOOLEANO DEFAULT 'F' NOT NULL,
        SOPORTA_IUSACELL TBOOLEANO DEFAULT 'F' NOT NULL,
        SOPORTA_UNEFON TBOOLEANO DEFAULT 'F' NOT NULL,
        CARRIERS BLOB SUB_TYPE 0 SEGMENT SIZE 80 DEFAULT NULL,
CONSTRAINT PK_PRODUCTOS_UDF_RECARGAS PRIMARY KEY (PRODUCTO_CODIGO));
```
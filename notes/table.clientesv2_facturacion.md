---
created: 1684912751000
desc: null
id: 5ueddcsklwvwm1zzqz1q6b8
title: CLIENTESV2_FACTURACION
updated: 1684912751000
---

```sql
CREATE TABLE CLIENTESV2_FACTURACION (CLIENTESV2_ID TLLAVE NOT NULL,
        RFC TRFC NOT NULL,
        NOMBRE TCADENALARGA,
        CALLE TCADENALARGA,
        NOEXTERIOR TCADENAMEDIANA,
        NOINTERIOR TCADENAMEDIANA,
        COLONIA TCADENALARGA,
        LOCALIDAD TCADENALARGA,
        MUNICIPIO TCADENALARGA,
        ESTADO TCADENAMEDIANA,
        PAIS TCADENALARGA,
        EMAIL TCADENALARGA,
        REFERENCIA TCADENALARGA,
        CODIGOPOSTAL TCODIGOPOSTAL,
        REGIMENES TNOTA,
        ELIMINADO_EN TFECHAHORA,
        REGIMEN_FISCAL TCADENAMEDIANA,
CONSTRAINT PK_CLIENTESV2_FACTURACION_ID PRIMARY KEY (CLIENTESV2_ID));
```
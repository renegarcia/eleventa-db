---
created: 1684912751000
desc: null
id: 68rxjy69u0ihzlbcaaq02su
title: CACHE
updated: 1685133015960000
---

```sql
CREATE TABLE CACHE (ID TLLAVE NOT NULL,
        PARAMETRO TCADENAMEDIANA,
        VALOR TNOTA,
        TTL TFECHAHORA,
        ETAG TCADENAMEDIANA DEFAULT NULL,
CONSTRAINT PK_CACHE PRIMARY KEY (ID));
```
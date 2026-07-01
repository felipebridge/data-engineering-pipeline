# Architecture Snapshot

_Generated: 2026-07-01_

**20 files** | **159 Python LOC**

## Directory Tree

```
data-engineering-pipeline/
├── docker/
│   ├── init/
│   │   └── 01_create_oltp.sql
│   └── docker-compose.yml
├── docs/
│   ├── dashboard BI/
│   │   ├── Análisis Comercial (2).png
│   │   ├── Análisis Comercial Geográfico.png
│   │   └── Panel Ejecutivo (1).png
│   └── star schema/
│       └── Star Schema.png
├── sql/
│   ├── dw/
│   │   ├── 01_create_dw.sql
│   │   ├── 02_load_dim_date.sql
│   │   ├── 03_load_dim_product.sql
│   │   ├── 04_load_dim_customer.sql
│   │   ├── 05_load_dim_geography.sql
│   │   ├── 06_load_dim_payment_method.sql
│   │   ├── 07_load_dim_order_status.sql
│   │   └── 08_load_fact_order_line.sql
│   ├── oltp/
│   │   └── 02_load_oltp_from_staging.sql
│   └── staging/
│       └── 01_create_staging.sql
├── src/
│   └── etl_load_staging.py
├── .gitignore
├── README.md
└── requirements.txt
```

## Module Size (Python LOC)

| Module | LOC |
|--------|-----|
| `src` | 159 |

## Imports

| Module | Uses |
|--------|------|
| `src` | `mysql`, `pandas` |

## File types

| Extension | Files |
|-----------|------:|
| `.sql` | 11 |
| `.png` | 4 |
| `.md` | 1 |
| `.txt` | 1 |
| `(none)` | 1 |
| `.py` | 1 |
| `.yml` | 1 |

---
# public.mtb_delivery_date

## Description

商品発送日

## Columns

| Name | Type | Default | Nullable | Children | Parents | Comment |
| ---- | ---- | ------- | -------- | -------- | ------- | ------- |
| id | smallint |  | false | [public.dtb_products](public.dtb_products.md) |  | ID |
| name | text |  | true |  |  | 名称 |
| rank | smallint | 0 | false |  |  | 表示順 |

## Constraints

| Name | Type | Definition |
| ---- | ---- | ---------- |
| mtb_delivery_date_pkey | PRIMARY KEY | PRIMARY KEY (id) |

## Indexes

| Name | Definition |
| ---- | ---------- |
| mtb_delivery_date_pkey | CREATE UNIQUE INDEX mtb_delivery_date_pkey ON public.mtb_delivery_date USING btree (id) |

## Relations

![er](public.mtb_delivery_date.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)

# public.mtb_status

## Description

商品ステータス

## Columns

| Name | Type | Default | Nullable | Children | Parents | Comment |
| ---- | ---- | ------- | -------- | -------- | ------- | ------- |
| id | smallint |  | false | [public.dtb_product_status](public.dtb_product_status.md) |  | ID |
| name | text |  | true |  |  | 名称 |
| rank | smallint | 0 | false |  |  | 表示順 |

## Constraints

| Name | Type | Definition |
| ---- | ---- | ---------- |
| mtb_status_pkey | PRIMARY KEY | PRIMARY KEY (id) |

## Indexes

| Name | Definition |
| ---- | ---------- |
| mtb_status_pkey | CREATE UNIQUE INDEX mtb_status_pkey ON public.mtb_status USING btree (id) |

## Relations

![er](public.mtb_status.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)

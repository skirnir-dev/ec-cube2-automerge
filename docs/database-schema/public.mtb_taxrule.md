# public.mtb_taxrule

## Description

課税規則マスタ

## Columns

| Name | Type | Default | Nullable | Children | Parents | Comment |
| ---- | ---- | ------- | -------- | -------- | ------- | ------- |
| id | smallint |  | false | [public.dtb_tax_rule](public.dtb_tax_rule.md) |  | ID |
| name | text |  | true |  |  | 名称 |
| rank | smallint | 0 | false |  |  | 表示順 |

## Constraints

| Name | Type | Definition |
| ---- | ---- | ---------- |
| mtb_taxrule_pkey | PRIMARY KEY | PRIMARY KEY (id) |

## Indexes

| Name | Definition |
| ---- | ---------- |
| mtb_taxrule_pkey | CREATE UNIQUE INDEX mtb_taxrule_pkey ON public.mtb_taxrule USING btree (id) |

## Relations

![er](public.mtb_taxrule.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)

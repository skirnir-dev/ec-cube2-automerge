# public.mtb_authority

## Description

管理者マスタ

## Columns

| Name | Type | Default | Nullable | Children | Parents | Comment |
| ---- | ---- | ------- | -------- | -------- | ------- | ------- |
| id | smallint |  | false |  |  | ID |
| name | text |  | true |  |  | 名称 |
| rank | smallint | 0 | false |  |  | 表示順 |

## Constraints

| Name | Type | Definition |
| ---- | ---- | ---------- |
| mtb_authority_pkey | PRIMARY KEY | PRIMARY KEY (id) |

## Indexes

| Name | Definition |
| ---- | ---------- |
| mtb_authority_pkey | CREATE UNIQUE INDEX mtb_authority_pkey ON public.mtb_authority USING btree (id) |

## Relations

![er](public.mtb_authority.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)

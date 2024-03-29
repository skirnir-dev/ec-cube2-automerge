# public.dtb_recommend_products

## Description

関連商品情報

## Columns

| Name | Type | Default | Nullable | Children | Parents | Comment |
| ---- | ---- | ------- | -------- | -------- | ------- | ------- |
| product_id | integer |  | false |  | [public.dtb_products](public.dtb_products.md) | 商品ID |
| recommend_product_id | integer |  | false |  |  | 関連商品ID |
| rank | integer |  | false |  |  | 表示順 |
| comment | text |  | true |  |  | コメント |
| status | smallint | 0 | false |  |  | 状態 |
| creator_id | integer |  | false |  | [public.dtb_member](public.dtb_member.md) | 作成者ID |
| create_date | timestamp without time zone | CURRENT_TIMESTAMP | false |  |  | 作成日時 |
| update_date | timestamp without time zone |  | false |  |  | 更新日時 |

## Constraints

| Name | Type | Definition |
| ---- | ---- | ---------- |
| dtb_recommend_products_pkey | PRIMARY KEY | PRIMARY KEY (product_id, recommend_product_id) |

## Indexes

| Name | Definition |
| ---- | ---------- |
| dtb_recommend_products_pkey | CREATE UNIQUE INDEX dtb_recommend_products_pkey ON public.dtb_recommend_products USING btree (product_id, recommend_product_id) |

## Relations

![er](public.dtb_recommend_products.svg)

---

> Generated by [tbls](https://github.com/k1LoW/tbls)

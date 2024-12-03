## ● [修改表字段] ┋ ALTER TABLE

```sql
ALTER TABLE [表] ADD [字段] [字段类型] NULL;

ALTER TABLE t_sell_record_v2_order ADD is_giftcard BIT NULL;
EXEC sp_addextendedproperty 'MS_Description', '是否赠卡（false|true）', 'SCHEMA', dbo, 'table', t_sell_record_v2_order, 'column', is_giftcard;
```

-----


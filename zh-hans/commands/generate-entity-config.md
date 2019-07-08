# generate:entity:config
生成新配置实体

**使用方法:**
```
drupal generate:entity:config [options]
gec
```

## 可用选项
选项 | 详细信息
-------|-------------
--module | 模块名
--entity-class | 配置实体类名
--entity-name | 配置实体名称
--base-path | 配置实体路由的基路径
--label | 标签
--bundle-of | 作为内容实体(s) 的 Bundle

## 例子
* Generate config entity specifying the module, the entity class, the entity name, its path and label
```
drupal generate:entity:config  \
  --module="modulename"  \
  --entity-class="DefaultEntity"  \
  --entity-name="default_entity"  \
  --base-path="/admin/structure"  \
  --label="Default entity"
```

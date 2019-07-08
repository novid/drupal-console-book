# generate:entity:bundle
生成新内容类型（node 或实体 bundle）

**使用方法:**
```
drupal generate:entity:bundle [options]
geb
```

## 可用选项
选项 | 详细信息
-------|-------------
--module | 模块名
--bundle-name | 内容类型的机读名称
--bundle-title | 内容类型的名称

## 例子
* Generate bundle entity specifying the module, the bundle name and its title
```
drupal generate:entity:bundle  \
  --module="modulename"  \
  --bundle-name="default"  \
  --bundle-title="default"
```

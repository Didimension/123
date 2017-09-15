﻿# Wiki 数据库结构版本信息

## 版本说明

Wiki 数据库结构版本存储于 [`version.md`](version) 中。

数据库结构版本指数据库目录结构、内容格式等的定义版本，与 Wiki 数据库的数据本身无关。

该版本号供数据库使用方识别用，**除管理员外请勿修改**。
此数字如无意外情况，应该只会使用整数。

ℹ 第三方使用本数据库，建议获取记录本数字，如果发现版本变高，可能涉及数据库结构变化，需要修改获取程序。

## 变更记录

###  [In porgress] version 5 @ ????/??/??
⚠这些修改还未确定，随时有可能变更
1.  [ ] 删除 `tags` 文件夹  
        （`a[href='wiki-version-number']` @ `tags/wiki-version.md` 和 `a[href='ETB_wiki-version']` @ `tags/rows.md` 表示的版本信息也将同时移除([讨论](https://github.com/Mapaler/EhTagTranslator/issues/30))
及）
1.  [ ] 数据库增加外部链接字段([讨论](https://github.com/Mapaler/EhTagTranslator/issues/29))

###  [In progress] version 4 @ [2017/09/14](https://github.com/Mapaler/EhTagTranslator/wiki/wiki-version/fcb5a180e6a233efe5a475411ef915f4e06f0e85)
⚠这些修改还未确定，随时有可能变更
1.  [x] 版本信息链接从 `a[href='wiki-version-number']` @ `tags/wiki-version.md` 迁移至 `a[title='database-structure-version']` @ `version.md` ([讨论](https://github.com/Mapaler/EhTagTranslator/issues/30))     
1.  [x] 移除 `database/rows.md` 中的版本信息([讨论](https://github.com/Mapaler/EhTagTranslator/issues/30))
1.  [x] `tags` 文件夹复制到 `database`
1.  [x] `wiki-changelog.md` 重命名为 `wiki-version-info.md`  

### version 3 @ [2017/09/13](https://github.com/Mapaler/EhTagTranslator/wiki/_compare/f22d6e7138b948d5226b579579881bd67f1a36eb)
1.  移动版本信息至独立文件 `wiki-version.md`  
1.  移动 `rows.md` 到 `tags/rows.md`  
1.  废弃在图片扩展名后添加 `h` 将其隐藏的方法

### version 2 @ [2016/06/06](https://github.com/Mapaler/EhTagTranslator/wiki/_compare/533d5e20bece0c3bc84e1987994fe6ade030f2f9)
1.  新增隐藏图片格式  

### version 1 @ [2016/05/25](https://github.com/Mapaler/EhTagTranslator/wiki/_compare/18b79c1314f53315e96793834550af9692f346c6)
1.  首次记录版本  
1.  新增注释格式

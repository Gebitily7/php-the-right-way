---
isChild: true
anchor:  configuration_files
title: 配置文件
---

## 配置文件 {#configuration_files_title}

当你在为你的应用程序创建配置文件时，最好的选择时参照以下的做法：

- 推荐你将你的配置信息存储在无法被直接读取和上传的位置上。
- 如果你一定要存储配置文件在根目录下，那么请使用 `.php` 的扩展名来进行命名。这将可以确保即使脚本被直接访问到，它也不会被以明文的形式输出出来。
- 配置文件中的信息需要被针对性的保护起来，对其进行加密或者设置访问权限。
- 建议不要把敏感信息如密码或者 API 令牌放到版本控制器中。
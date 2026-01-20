# awesome
与 Ikaros 相关的周边生态资源列表

# 版本适配规则

插件的版本规定

服务端版本.主版本.子版本

插件的服务端版本只取服务端版本的主版本和子版本，忽略第三级别的Bug版本，

比如当前插件适配的服务端是 0.15.5, 那么服务端版本就是15，此时插件的版本就是 15.3.0

如果服务端版本是1.0.0，此时服务端的子版本最大曾是两位数，则，app的服务端版本是 1 * 100 + 0 = 100 ，此时APP的版本就是 100.3.0

# 插件
- [plugin-bgmtv](https://github.com/ikaros-dev/plugin-bgmtv) : [bgmtv](https://bgm.tv/) 插件
- ~~[plugin-local-files-import](https://github.com/ikaros-dev/plugin-local-files-import): 本地文件批量导入插件~~ 推荐使用挂载本地目录的方式
- [plugin-jellyfin](https://github.com/ikaros-dev/plugin-jellyfin): jellyfin插件
- [plugin-baidupan](https://github.com/ikaros-dev/plugin-baidupan): 百度网盘插件（实验性质，不推荐使用）
- [plugin-mikan](https://github.com/ikaros-dev/plugin-mikan): [蜜柑计划](https://mikanime.tv/)插件(目前不推荐使用)
- [plugin-openlist](https://github.com/ikaros-dev/plugin-openlist): [OpenList](https://doc.oplist.org/)插件，支持导入openlsit文件URL到ikaros附件
- [plugin-pan115](https://github.com/ikaros-dev/plugin-pan115): A pan115 plugin for ikaros. | 115网盘插件，提供对115网盘的驱动附件挂载。

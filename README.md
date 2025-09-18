本仓库中的插件仅为示例，来源于**国外互联网**、**国外视频网站**上的**公开内容**，并经过筛选，**排除**且**没有**国内的VIP/付费/试用歌曲。

仓库代码仅供学习和参考之用。请勿将它们用于任何商业目的，并确保其使用合理合法。

# MusicFree 源插件订阅聚合器

个人 MusicFree 源插件订阅聚合器——通过 Github Actions 每日自动检测并同步更新。

## 懒人订阅链接：

这个聚合的插件接口比较多，一个订阅就够用，记得删除原有订阅和点击右上角菜单的`卸载全部插件`以免冲突。

复制下面的链接在 MusicFree 插件订阅中使用：
```
https://rickychaw.github.io/MusicFreePluginsHub/plugins.json
```
注：

1. 部分插件被作者混淆代码，可能在桌面端无法正常使用。等待 musicfree 作者给桌面端更新插件引擎功能吧。
2. 插件属原作者所有，本仓库仅用于聚合及测试 CDN 分发。

## 自行部署

- Fork 本仓库并启用 Actions 后，请在仓库的 Action 菜单中设置 Workflow 权限为“读取和写入”。
- Actions 可以手动触发，或自动执行，生成 plugins.json 文件。
- 在 `Cloudflare Pages`、`Vercel`、`GitHub Pages`、`Netlify` 等平台导入部署仓库后可直接获取 `plugins.json` 的链接。可绑定自定义域名，以便在国内访问。

Gmeek 特性

UI 界面和 Github 同源，只引入了 Github 原生 CSS：primer.style；

博客写作在 Issues 中完成后，自动触发 Actions 执行部署任务；

评论系统引入 utteranc.es；

使用 jinja2 对 html 进行渲染，可通过模板自定义 UI 主题。
安装步骤

点击创建仓库，建议仓库名称为 XXX.github.io，其中 XXX 为你的 github 用户名；

在你创建好的仓库的设置 Settings 中 Pages -> Build and deployment -> Source 下面选择 Github Actions；

打开一篇 issue，开始写作，并且添加一个标签，保存 issue 后会自动创建博客内容，片刻后可通过 https://XXX.github.io 访问。

体验地址：https://blog.meekdai.com/

开源项目地址：https://github.com/Meekdai/Gmeek

开源项目作者：Meekdai
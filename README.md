# SDTTTTT's Blog Generator

[sdttttt.github.io](https://sdttttt.github.io) 网站的生成器, 使用hugo生成. 它是博客, 同时也是生成器.

如果你喜欢我博客的样式, 或者你是hugo的使用者, 都可以fork这个仓库.

我在这个项目做了全自动的生成和部署.只要小小的配置一下, 修改一些个性化说明, 再把自己文章的markdown文件放入, 就成为了你自己的博客.

# Configuration

关于自动部署请查看`deploy.sh`文件, 其中都有说明.

文章目录在content下, 您可以删出他们.

如果您想要更换主题, 请修改`config.toml`中的内容,以及将主题放入`themes`文件夹.

值得注意的是我在我的博客中使用了`Telegram Comment`作为评论系统.
在fork后, 请删除`themes/future/layouts/post/comments.html`中插入comments的JS代码.
如果您想要继续使用, 请在 **https://comments.app/** 处生成属于你自己的评论脚本.然后更换上述的代码片段.

配置是简单的, 我不喜欢复杂的东西.

# Using

每次编写完成博客只需要`make`一下即可自动部署.
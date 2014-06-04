要使用Padrino，需要预装一些库。首先，需要安装Ruby解释器。您可以通过在终端键入`which ruby`来查看您是否安装有Ruby，以及安装的是哪一个版本的Ruby。如果没有安装，我们推荐安装[RVM](http://beginrescueend.com/rvm/install/)，因为在大多数平台上，通过RVM都可以配置您需要的Ruby版本。一旦RVM安装完成，请确认安装Ruby 1.9.2（推荐）或者任何其他版本的，例如1.8.7，Rubinius，或者JRuby都可以，根据您的需要而定。

安装完Ruby之后，您需要确认一下是否安装有[RubyGems](https://rubygems.org)，这可是安装Ruby包的标准软件。您可以通过在终端键入`gem -v`来确认安装的Gem版本。如果没有安装，那么就去[下载安装](https://rubygems.org/pages/download)吧。

特别提示：如果您使用的系统是Windows，我们推荐使用[一键安装包：RubyInstaller](http://rubyinstaller.org)，该软件将上面的软件打包到了一起。

如果您的Ruby和rubygems都安装完毕，接下来即可以安装Padrino框架了，该框架打包为 `padrino` gem：

    gem install padrino

该命令将会首先安装Padrino所依赖的包，然后安装Padrino框架。现在，您准备好使用这个gem来[增强Sinatra项目](standalone-usage-in-sinatra.md)或者创建一个Padrino应用了吗？如果您没有使用过Ruby或者Sinatra，请先查看一下[新手上路](getting-started.md)吧。

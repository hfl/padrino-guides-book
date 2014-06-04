# 概述

Padrino是一个基于非常优秀的[Sinatra](http://www.sinatra.com/)而构建的网络应用框架。Sinatra是一个使用Ruby语言编写的用于创建简单网络应用程序的领域专用程序语言。Padrino就是为了使Sinatra编程变得有趣而且写代码更容易，从而更加彰显Siantra框架的伟大！

## 特色

下面是基于Sinatra构建的Padrino的主要特色：

|特点|内容|
|--|--|
|**Agnostic:**|支持所有流行的测试、模板、模拟和数据库。|
|**Generators:**|创建应用，生成模型、控制器，例如： `padrino g project`.|
|**Mountable:**|与其他Ruby框架不同，原生支持挂载多个应用。 |
|**Routing:**|Full url named routes, named params, respond\_to support, before/after filter support.|
|**Tag Helpers:**|视图帮助方法诸如： `tag`, `content_tag`, `input_tag`。|
|**Asset Helpers:**|视图帮助方法诸如： `link_to`, `image_tag`, `javascript_include_tag`。|
|**Form Helpers:**|表单构建支持，如： `form_tag`, `form_for`, `field_set_tag`, `text_field`。|
|**Text Helpers:**|有用的格式化方法如： `relative_time_ago`, `js_escape_html`, `sanitize_html`。|
|**Mailer:**|简捷快速的传递邮件（类似于ActionMailer）。|
|**Admin:**|内建管理界面（类似Django）。|
|**Caching:**|简化路由和缓存碎片从而加速网络请求的回应速度。|
|**Logging:**|提供一个统一的日志记录器，可以与您使用的ORM或者任何库进行交流。|
|**Reloading:**|开发模式下自动加载服务器端代码。|
|**Localization:**|全面支持I18n||



## 导航

如果您第一次使用Sinatra或者Padrino，我们推荐您先看看 [新手上路](getting-started.md)，该文对本系统做了一个全面的概述。当然，您也可以直接查看 [博客教程](blog-tutorial.md)，该文中通过一步步的实作，最终完成了一个Padrino项目。

Padrino包含多个模块（这些模块用来从不同的方面增强Sinatra功能）。下面描述的为主要几个组件：

-   [新手上路](getting-started.md)
-   [生成器](generators.md)
-   [应用帮助方法](application-helpers.md)
-   [控制器和路由](controllers.md)
-   [开发环境和终端命令](development-commands.md)
-   [挂载子应用程序](mounting-applications.md)
-   [收发邮件](padrino-mailer.md)
-   [管理与授权](padrino-admin.md)
-   [站点缓存](caching-support.md)

注意：作为Padrino用户，每一个主要组件都可以 [独立运行](standalone-usage-in-sinatra.md) 在已有的Sinatra应用中，或者一起运行在一个一栈式Padrino项目中。

这个指南希望能对您有所帮助，如果您有任何问题，联系我们： [@padrinorb](http://twitter.com/#!/padrinorb)，讨论问题在 [google groups](https://groups.google.com/forum/?hl=en#!forum/padrino)，参与讨论在freenode IRC 的 “\#padrinorb” 或者在Github上 [提出一个问题](https://github.com/padrino/padrino-framework/issues) 。

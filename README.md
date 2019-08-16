# 项目预览

这个项目是一个基于 web 的用来读取 rss 源的应用，项目使用 Jasmine 编写单元测试。

# 了解项目

* 查看项目的 HTMl (**./index.html**), CSS (**./css/style.css**) 和 JavaScript (**./js/app.js**) 文件来对项目的工作原理有一个基本的了解。
* 查看 Jasmine spec 文件 **./jasmine/spec/feedreader.js** 然后翻阅阅读 [Jasmine 文档](http://jasmine.github.io)。

# 测试用例

1. 遍历 allFeeds 对象里面的所有的源来保证有链接字段而且链接不是空的。
2. 遍历 allFeeds 对象里面的所有的源来保证有名字字段而且不是空的。
3. `"The menu"` 测试用例中：菜单元素默认是隐藏的，单图标被点击的时候菜单会切换可见状态。
4. `"Initial Entries"` 测试用例中： `loadFeed` 函数被调用而且工作正常
5. `"New Feed Selection"` 测试用例中： `loadFeed` 函数加载一个新源的时候内容会真的改变。

```
联网大数据时代，如何低成本甚至零成本获取高价值数据（国内公开API大全）
以前做网站只需要PC Web版就可以，但随着科技的发展，诞生了智能手机、平板等显示终端，为了适应不同平台的内容展示，很多网站都开发了API。有些自己内部用，有些对外公开。
尤其到了大数据时代，需要各种各样的格式化数据，很多都可以通过API获取。
什么是API？
API（Application Programming Interface，应用程序编程接口）是一些预先定义的函数，目的是提供应用程序与开发人员基于某软件或硬件得以访问一组例程的能力，而又无需访问源码，或理解内部工作机制的细节。
更清晰的解释见：API是什么？为什么它很重要？ | 雷锋网
API是通过把程序内部的一些功能有限地向外开放，这使得应用之间可以分享交换数据，同时不需要公布所有的软件代码。可以把它看成是一扇门、窗或杠杆。
以滴滴打车为例，打开软件你就可以到一张地图，上面会显示附近的车辆。而这个地图并不是滴滴开发的，而是调用的腾讯地图API。（据说滴滴打算要自己做地图了）
还有当你用Safari浏览器看到一篇好文章，可以随意分享到微信、新浪微博、QQ等地方，这也是靠API。
公开的API
很多互联网公司都提供了开放平台，里面就有各自的服务API。
微信开放平台
https://open.weixin.qq.com/
淘宝开放平台
http://open.taobao.com/
百度开放平台
http://open.baidu.com/
新浪微博开放平台
http://open.weibo.com/
腾讯开放平台
http://open.qq.com/
讯飞开放平台
http://www.xfyun.cn/
高德开放平台
http://lbs.amap.com/
搜狗开放平台
http://open.sogou.com/
太多了，不再一一列举，基本上“品牌+开放平台”都可以搜的到。
这些开放平台都是基于自己的产品或利益，开放了一些API接口。
也有一些第三方平台，聚合了更多API，提供付费或免费的API服务，种类更多，功能更细。
国内的第三方API聚合平台
Baidu API Store
API Store_为开发者提供最全面的API服务
极速数据
API接口数据接口平台免费数据大全 - 极速数据

好服务数据
API数据接口开发者数据定制免费数据调用_好服务数据

易源接口ShowAPI
易源接口-致力于互联网数据接口化

阿里云市场
API_API接口平台_API数据【最新】_API接口大全_API认证 - 阿里云

国外的第三方API聚合平台
Apigee API Consoles | Featured provider directory
https://apigee.com/providers

在Github上有一个收藏一万多的项目，里面编辑整理了很多国外的公共API服务。
toddmotto/public-apis
非公开API
除了公开API，实际上有很多平台都有自用的API是不对外公开的。
但是可以通过抓包工具或者简单的Chrome审查元素分析获得。
比如做SEO的都很关注各个搜索引擎的相关搜索词或下拉词：
360下拉词
https://sug.so.360.cn/suggest?callback=suggest_so&encodein=utf-8&encodeout=utf-8&format=json&fields=word,obdata&word=关键词&mid=91553
百度下拉词
https://sp0.baidu.com/5a1Fazu8AA54nxGko9WTAnF6hhy/su?wd=关键词&json=1
搜狗下拉词
https://www.sogou.com/suggnew/ajajjson?key=关键词&type=web&ori=yes
必应下拉词
http://cn.bing.com/AS/Suggestions?pt=page.home&mkt=zh-cn&qry=关键词&cp=2&o=hs&cvid=2EB7121644FB426F9CCC1BB35E11FCE1
如果你采集的文章需要配图，那就可以借助好搜的图片API：
http://image.so.com/j?q=关键词&src=srp&sn=30&pn=20
如果你想搞些新闻类信息，那么今日头条搜索API很适合：
http://www.toutiao.com/search_content/?format=json&keyword=关键词
个人很喜欢“即刻”APP里的某些频道，用Chrome浏览器分析就可以获得API调用方式，结构如下：
http://app.jike.ruguoapp.com/1.0/topics/showDetail?topicId=频道ID
然后我就可以把即刻APP变成个性化的Web版：
乔木阅读器
有些时候即使没有格式化的JSON API，你可以通过编程采集需要的内容，从而“自制API”。
总结
互联网数据量越来越庞杂，当你想要一些有价值的格式化数据时，API是一个很好的选择。
API很符合互联网开放互连的精神，正是因为有这些样五彩缤纷的接口，才能让我们避免重复造轮子，快速搭建实用的服务。比如国外知名的IFTTT和Slack，都在API组合调用上让人叹为观止。
如果你有好的私藏API，欢迎留言分享。
```

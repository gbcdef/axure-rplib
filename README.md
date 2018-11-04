个人制作及从各处收集的优质Axure元件库

# 写在前面
虽然Axure RP的全称是Axure Rapid Prototype，但是Axure的快速原型能力局限于Web1.0时代。如果要做原型，已经有很多更好用的工具，比如Sketch、Principle、Flinto、Framer Studio、墨刀等等。现在，Axure是很好用的wireframing工具，而不是prototyping工具。Axure输出静态产品文档的能力，远远高于Word、InDesign、OmniGraffle之流。

因此，过分注重于可交互原型的元件库（号称“全动态”的那种），将不被收录。

# 文件说明

`default/`
Axure原生提供的默认组件，针对字体、字号、图形填充及边框颜色等进行了修改，并同步更新了样式。

`ant.design/`
[Ant Design](https://ant.design/index-cn)提供的快速原型组件库。[点击查看最新版](https://ant.design/docs/spec/download-cn)

`gb_default`
画了2年线框原型之后，决定返璞归真后的组件库。也是我个人目前主力使用的组件库。相比于画出好看的线框原型，高效、简洁地传递设计信息才是最重要的。
> ![](img/gb_default_desc.png)

`gb_customized`
随意创作的线框图组件库。

`gb_Apple Watch`
基于Apple Watch设计规范制作。尺寸符合Apple Watch规范。可以用作高保真原型制作。

`gb_metronic`（已删除）
推荐使用`ant.design/library.ant.design_Web_3.0.rplib`
~~基于Metronic后台UI主题制作~~。[点击了解Metronic主题](http://keenthemes.com/preview/metronic/)

`gb_WeChatUI`
根据微信小程序提供的Photoshop版设计素材文件，制作的Axure版高保真原型库。[点击查看微信小程序UI素材](https://developers.weixin.qq.com/miniprogram/design/#%E8%B5%84%E6%BA%90%E4%B8%8B%E8%BD%BD)

# 使用方法
将`.rplib`文件复制到`Documents\Axure\Libraries`下即可。
Windows将`Documents`译作`文档`，macOS将`Documents`译作`文稿`。

# 写在后面
Axure有几个弱点：
1. 流程图和图示的能力逊于OmniGraffle和Visio
2. 传阅不便，Axure Share在国内龟速。目前没有找到好的解决方案，蓝湖、产品大牛等等都是HTML文件托管，我随便写的fixd-server都更好用。
3. 团队协作。SVN只能算作版本管理，而不能算作团队协作
4. 矢量的图标库太丑、太少，只能用位图图标库妥协。

以上有好的解决方案的欢迎提issue讨论。

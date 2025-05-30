# 介绍
- 由于旧版PandaOCR在制作时急于增加各种功能而忽视了代码中的各种执行逻辑和对后续维护或添加新功能的不良影响，导致现在的代码堆积成了一座屎山，每次看到源代码都感到满头大汉，与其去翻那座大山，干脆重来，所以又花不少时间重构了一个全新版本，同时为避免与之前的版本混淆，取名PandaOCR.Pro专业版。
- 与PandaOCR不同的是，PandaOCR.Pro主要针对使用私用API版接口的人群，演示接口由于普遍不够稳定且经常需要修复终归不会是长久之计。
- PandaOCR.Pro同样是免费使用，但它有一个激活专业版本状态，在未激活状态下您可以使用除高级功能外的全部功能，同时识别或翻译等功能可使用演示接口和百度API版接口，普通使用基本足够！
- 激活专业版后不受任何限制，您可以使用全部功能，包括全部已接入的API接口和高级功能，如：图文批量识别、调用本地接口、屏幕对照翻译、屏幕显示按键、按键音效播放、快捷短语翻译等！
- 如果您喜欢并愿意支持本工具继续提供更好的功能或体验可以考虑激活专业版，也可以单纯捐助，谢谢！

# 特性
- 重构了整个程序，优化了程序逻辑，所以它理论上应该更稳定，更简洁和更快速。
- 保留了PandaOCR上已有的大部分功能，同时也精简了少许可能会影响性能且不太常用的功能。
- 增加了调用本地接口高级功能，专为开发者准备 [调用本地接口教程](https://www.showdoc.com.cn/PandaOCR/11558471145804815)
- 增加了多种离线OCR引擎调用能力，满足各种识别需求。
- 增加了一些朋友需要的按OCR位置进行排版的功能，虽然目前还只是实验性，但日后还有优化空间。
- 优化了行首缩进功能，旧版强行在行首添加多个空格蹩脚实现，现在改由编辑框原生显示，提升识别速度且更美观。
- 优化了边角触发截图，解决在旧版中容易误触发的问题。
- 优化了程序界面，使之看上去更精简干净，且基本保留了旧版的样式和操作方式，老人们可以无缝切换。
- 优化了截图组件2，现在你可以在截图时快速选择应该使用哪类引擎识别，如搜图，扫码，上传图床或识别公式，而不用在程序界面频繁切换。
- 优化了设置操作，多数设置可直接在程序界面中切换或修改，减少频繁手工编辑配置文件，为新手在使用上提供便利。
- 优化了预览弹窗，并可以调整弹窗本身、弹窗文字、弹窗按钮的位置或样式。
- 优化了图像编码，专业版使用更好的GDI转码图像，解决在旧版中因转码两次导致图像质量降低而影响文字识别或漏字。
- 修复了PandaOCR上恢复焦点窗口时常失效的老问题。

# 下载
- 最新版本：5.58
- 更新日期：2025-05-30
- 更新日志：https://github.com/miaomiaosoft/PandaOCR.Pro/releases
- 蓝奏网盘：https://miao520.lanzoui.com/b016ct8ob  提取码：8888
- 百度网盘：https://pan.baidu.com/s/1gaUeeETeGwvNb5-PUYjxqQ  提取码: kpgh
- 腾讯网盘：https://share.weiyun.com/jpS7MkHB

# 教程
- https://www.showdoc.com.cn/PandaOCR
- https://support.qq.com/products/322047/faqs-more
- https://github.com/miaomiaosoft/PandaOCR.Pro/wiki

# 预览
#### 如果看不到图请到备用主页查看：https://gitee.com/DDDDDGOOO/PandaOCR.Pro

- 截图界面：
- ![](https://raw.githubusercontent.com/miaomiaosoft/PandaOCR.Pro/main/images/%E9%A2%84%E8%A7%8802.jpg)
- 精简窗口：
- ![](https://raw.githubusercontent.com/miaomiaosoft/PandaOCR.Pro/main/images/%E7%B2%BE%E7%AE%80%E7%AA%97%E5%8F%A31.png)
- 整体效果：
- ![](https://raw.githubusercontent.com/miaomiaosoft/PandaOCR.Pro/main/images/%E9%A2%84%E8%A7%8801.jpg)
- 接口合影：
- ![](https://raw.githubusercontent.com/miaomiaosoft/PandaOCR.Pro/main/images/%E9%A2%84%E8%A7%8803.png)
- 段落排版：
- ![](https://raw.githubusercontent.com/miaomiaosoft/PandaOCR.Pro/main/images/%E6%AE%B5%E8%90%BD%E6%8E%92%E7%89%88%E4%BC%98%E5%8C%96.jpg)
- 位置排版：
- ![](https://raw.githubusercontent.com/miaomiaosoft/PandaOCR.Pro/main/images/%E9%A2%84%E8%A7%8804.png)
- 丰富设置：
- ![](https://raw.githubusercontent.com/miaomiaosoft/PandaOCR.Pro/main/images/%E9%A2%84%E8%A7%8805.png)
- 高级功能：
- ![](https://raw.githubusercontent.com/miaomiaosoft/PandaOCR.Pro/main/images/%E9%A2%84%E8%A7%8806.png)

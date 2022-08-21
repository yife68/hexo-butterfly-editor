# 文章

博客最重要的就是给访客查看文章了。优秀的文章需要配合优秀的访问体验才能恢复最大的价值。只给自己做的博客是没有出路的。

## 外挂标签

[Tag Plugins Plus](https://akilar.top/posts/615e2dec/) - Akilar

> 已发布插件版，具体配置方案请参看插件文档。

## 页面组件

[butterfly文章页面上下篇按钮UI调整](https://akilar.top/posts/b77e1c58/) - Akilar

> 我试图通过将文章底部的按钮改至左右两侧，类似翻页键，同时添加悬停动作，通过css对兄弟相邻元素的hover监测来控制显隐，悬停按钮时在页面正中显示对应文章卡片。
>
> 首先要解决的是按钮显示问题，如果是常显，有可能遮盖正文内容，尤其是手机端应该不会有足够的位置。所以尝试通过设置滚动事件监听，在页面滚动至原本上下页翻页的位置，也就是正文刚好读完的时候，才显示按钮。虽然会遮盖一部分评论，不过可以把按钮调整到正中，手机端调扁一点，毕竟不是正文的话，也不用太纠结遮盖问题。

[给博客添加个性名片](https://akilar.top/posts/5ff2da64/) - Akilar

> 为什么要做这个个性名片？
> 因为再不把加群信息放在醒目位置，我的博客群就要彻底变成冰老师的售后群了。

[信笺样式留言板](https://akilar.top/posts/e2d3c450/) - Akilar

> 留言板动态弹出信封样式

[Bilibili Dynamic Banner](https://akilar.top/posts/780a2cea/) - Akilar

> B站同款动态Banner

[SAO UI Plan -- Ranklist](https://akilar.top/posts/b7126498/) - Akilar

> 把SAO Utils Web也归入了 SAO UI PLAN ，复现SAO 风格界面算是告一段落啦。
>
> 这个榜单一开始是准备拿来当做打赏榜单的。可是临到头却发现没人打赏。（疯狂暗示）所以就只能拿来充当友链排行啦。

[版权声明美化](https://akilar.top/posts/8322f8e6/) - Akilar

> 基于@Nesxc同学的项目修改。仅做微调。补齐了两个配置项的默认项。精简配置过程。针对文字偏移做了自适应优化。

## 美化

[生成封面图片主色来作为文章封面顶图](https://blog.zhheo.com/p/c86d8f1f.html) - Akilar

> 本教程只介绍Hexo下的Butterfly主题的方案，其他可供参考，通用性强。
> 需要七牛云图床，其他图床需能提供纯色API，使用方法雷同（使用js计算可能涉及到跨域等诸多问题）

## 评论

[twikoo评论块气泡风格魔改美化](https://akilar.top/posts/d99b5f01/) - Akilar

> 要对twikoo进行魔改，同时又不破坏评论结构。那我首先想到的是用js附加class，然后针对新增的class进行样式覆写。
>
> 但是在尝试过程中，发现不论我如何推迟附加class的js执行时间，它永远早于twikoo评论加载。~~原因还在排查……才怪咧，我它喵直接跑去提issue，才不要在这排查~~

[Valine Visitor Tag Beautify](https://akilar.top/posts/d2222705/) - Akilar

> Valine评论添加[博主,小伙伴,访客]标签

[Butterfly comment board beautify](https://akilar.top/posts/397b8b90/) - Akilar

> 评论区侧栏弹出式美化方案

[Twikoo腾讯云函数部署转移到私有部署](https://blog.zhheo.com/p/99d020fe.html) - 张洪Heo

> 对于腾讯云毫无契约精神的行为表示强烈的抗议和严厉的谴责。
>
> 大概是去年领取到了腾讯云开发的五年期限免费使用权，可是腾讯云直接就毁约，以「计费方式调整」为由，强制要求现有用户退款结束服务。当然我相信是因为「所有解释权归腾讯所有」，腾讯云才可以肆无忌惮的毁约和取消订单。
>
> 作为一个个人的小用户，腾讯云直接以劝退的方式来行动。维权成本那么高，相信腾讯云也觉得没多少人愿意去为了这东西维权吧。

[批量替换旧的Twikoo表情包地址，修复数据库里旧的jsdelivr链接](https://blog.zhheo.com/p/7469b3de.html) - 张洪Heo

> 之前sticker-heo一直使用的是jsdelivr链接，但是因为近期jsdelivr已经彻底失效，近一个多月以来本项目已经换了三家cdn了。更换cdn确实提高了访问速度，但是旧版的sticker-heo表情仍然是不可访问的状态。
>
> 这里介绍一下如何更改旧表情链接地址方法，其他评论系统大同小异，这里只介绍twikoo。

[Twikoo魔改样式分享-博客评论系统的定制皮肤](https://blog.zhheo.com/p/8b1dde4c.html) - 张洪Heo

> 魔改了一下Twikoo的样式，拿出来分享一下，喜欢的可以搞一手。推荐用官方的。
# 关于

本文描述如何发布 Jenkins 官方微信公众号文章。

# 发布时间

我们在每周三下午六点发布文章。

每次发布，同一类型的文章只能包含一篇。需要在同一天发布多篇文章的话，顺序如下：

* 活动、通知
* 原创
* 翻译
* 转载

# 申请权限

如果您愿意帮忙发布 Jenkins 微信公众号文章，您需要新建（或更新）如下的示例文件，并创建一个 PR 。文件名的格式如：`githubid-short-term.yaml`.

示例文件：
```
wechat: wechatid
github: linuxsuren
terms:
- 2018-11-11
```

根据微信公众号平台的规定，可以绑定5个长期运营者, 20个短期（一个月）运营者。上面的字段 `terms` 为管理周期。

## 短期运营者

有至少一篇文章被发布在公众号上，熟悉发布流程，认真负责。

## 长期运营者

有至少三次的短期运营者经历，并经过小组全体成员同意。

# 职责

所有的文章，都需要提交到该仓库中。您的任务是从该仓库中拷贝文章，然后在[公众号平台](https://mp.weixin.qq.com)上创建，进行必要的排版处理。在发布之前，需要把预览链接发送到给[大家](https://gitter.im/jenkinsci/chinese-localization-sig)进行审查。最后，没问题的话，设置发送时间。注意，公众号中的内容必须与该仓库保持一致。


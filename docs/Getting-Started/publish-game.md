# 发布游戏

::: tip 阅读本文大概需要 5 分钟。

完成所有功能，接下来就是将游戏发布到线上直面玩家了！不过在此之前创作者们可以先在手机上测试一下自己的游戏，来排查潜在的手机上运行特有 BUG。本章节将会带领大家学习如何将游戏发布到我们的官方平台，并在手机上玩到它。

:::

关于游戏内容合规问题请查阅产品手册：[管理发布游戏 | 产品手册 ](https://docs.ark.online/CreatorPortal/Publishing&Managing.html)

## 1. 设定房间最大用户数量

在发布游戏之前，首先要设定好我们的游戏单个房间最大可容纳多少人。在口袋方舟编辑器中，与房间内容纳人数相关的的设置有两个：

- 玩家数量上限。

- 服务器预留玩家数量。

第一个参数决定了单个房间内最大可以容纳的玩家数量，要注意的是这个数量包含了预留玩家的位置的。

预留玩家指的是除去正常点击开始游戏进入的玩家，比如通过好友邀请加入房间、通过好友“当前正在玩”功能跟房进入的玩家。

简单来讲，如果我们设置“玩家数量上线”为 5，设置“预留玩家数量”为 1 ，假设现在用户全部是通过在游戏详情页，点击“开始游戏”按钮进入的，那么该房间最多可以进入 4 个人，因为预留了 1 个空位。

::: tip 开启服务器预留玩家后对匹配的影响

设定服务器预留数量后，当玩家加入游戏时，将优先匹配有好友关系的房间；当同时存在多个好友关系房间时，则优先向房间内人数较多的房间内分配。

:::

了解概念之后我们来看看在编辑器中如何设置它们：

- 在编辑器主界面右上角点击设置按钮。

  ![编辑器设置](https://arkimg.ark.online/06e7d94b-e64e-47e2-9a42-371a1d12e7e5.webp)

- 在设置界面中选中世界设置 --> 房间设置。

  ![房间设置](https://arkimg.ark.online/6cef5cbd-1b74-4494-a941-0975ee31ad82.webp)

- 设置最大玩家数量上限（范围 5 ~ 50） 。这里我设置为 10 ，大家可以根据游戏需求设置不同的数值。

  ![设置最大玩家数量](https://arkimg.ark.online/cc719bc1-4545-4916-a9a9-e13c0dce4509.webp)

- 设置服务器预留玩家数量。这里我为了演示功能，将它开启并设置为 1 。同样这个值也需要大家根据实际需求设置。

  ![设置最大预留人数](https://arkimg.ark.online/565b3b68-b254-44cc-a1b0-9276db8f0643.webp)

这样第一步就完成了，接下来创作者们可以关闭设置窗口，进行第二部分的学习了。

## 2. 上传游戏并在创作者后台查看

想要在平台中玩到大家创作的游戏的话，首先需要将游戏工程上传到官方服务器中。等待工程上传完毕后，我们就可以在创作者后台看它的详细信息了。接下来我们就来一起动手上传第一个游戏吧！

- 在编辑器左上角点击功能按钮 --> 点击发布游戏按钮。
  ![工程中选发布游戏](https://arkimg.ark.online/fe14cdf9-d249-461c-89eb-08a69ee948f4.webp)

- 在发布游戏界面填入游戏名称、发布说明，然后按需勾选是否接入 MGS 、是否是单机模式。这里我将游戏命名为《口袋方舟启动!》，填入本次更新的说明：测试游戏。

  ::: tip 关于 MGS 与 单机模式

  - 勾选 `接入 MGS` 选项后发布的游戏就会接入到平台的好友系统，可以实现在游戏中与好友聊天、邀请好友一起玩等社交功能；
  - 勾选 `单机模式` 选项后发布的游戏会变为单机，无法与平台其它用户联机游戏。

  :::

  ![发布游戏界面](https://arkimg.ark.online/d121fe62-a676-41cb-ac2d-fc8d1909ea7d.webp)

- 全部设置好之后就可以点击发布游戏按钮了，等待上传完毕编辑器会自动打开浏览器进入到创作者后台界面。（如果你的浏览器没有自动跳转，也可以手动进入创作者后台：[创作者后台](https://portal.ark.online/)）


## 3. 在创作者后台设置游戏素材

 ::: tip 关于测试游戏

如果只是想使用真机测试游戏，可以先不上传素材。素材仅在正式上线时需要上传。

:::

- 根据后台的提示上传游戏 ICON 、首页图、详情页素材等资料，上传好后等待审核即可。关于素材规范细则请阅读产品手册：[游戏图标规范](https://docs.ark.online/CreatorPortal/Publishing&Managing.html#游戏图标规范)

  - **游戏名称**：作为 233 乐园的游戏名称，可在[创作者中心](https://portal.ark.online/#/admin/game-list)进行二次编辑；
  - **游戏图标**：展示在 233 乐园上的游戏图标；
  - **首页图**：展示在 233 乐园首页的游戏大图（**主要曝光入口**）；
  - **游戏分类&标签**：设置游戏对应的分类和标签，提高游戏曝光；

  ![上传素材](https://arkimg.ark.online/91d5830c-4c73-4351-b64b-6f28571bb1c8.webp)

## 4. 使用手机测试游戏

- 在创作者后台选中想要测试的游戏，在左上角点击“总览”进入到游戏信息总览界面：

  ![总览按钮](https://arkimg.ark.online/b7f24513-1e00-4685-9c73-0b6a52a8f116.webp)

- 在游戏总览页面中的基础信息模块，点击“游戏测试”按钮：

  ![游戏测试按钮](https://arkimg.ark.online/a01b38eb-c3ab-4fff-8db7-f11ab2556efc.webp)

- 点击“游戏测试”按钮后会弹出一个二维码，之后我们就可以使用 233 乐园 APP 扫码进入游戏了：

  ![测试二维码](https://arkimg.ark.online/528e7aa7-0f9a-4a84-b794-b527a7ab81ef.webp)

- 启动 233 乐园 APP ，在首页右上角找到“扫码”按钮（下图中蓝框标记的按钮），点击按钮之后会弹出扫码窗口，接下来就可以使用手机扫描上一步中的二维码了。如果是第一次使用扫码功能，可能会弹出摄像机使用权限弹框，如确定使用该功能请点击同意。

  ![扫码功能](https://arkimg.ark.online/8186ba25-3284-49e8-9817-d3b662ca4edf.webp)

- 扫描之后会弹出游戏预览界面，在这个界面中可以看到该游戏的已上传版本，创作者可以选择指定版本点击“开始”按钮进入游戏测试。

  ![游戏预览](https://arkimg.ark.online/76d8ea30-5b6c-42b1-9457-aa3c829ff70a.webp)

## 5. 提交审核等待正式上线

当我们所有测试全部结束，就可以填写素材与游戏介绍等内容准备上线了 ！

- 在下图 1 号区域内需要填写所有带有 * 号的内容。
- 填写无误后点击提交审核，等待游戏审核即可上线。

![开发者后台](https://arkimg.ark.online/de2f370a-2a06-4045-8144-563c075f0d2a.webp)

- 游戏过审后会在开发者后台右上角消息通知处通知。

  ![消息通知](https://arkimg.ark.online/a6be0a82-2858-4f14-917a-7973710adf57.webp)

## 6. 更新已发布游戏

当游戏内容发生变更，需要将变更推送到线上游戏时，创作者可以使用“更新已发布游戏”功能对线上游戏进行更新。

- 在编辑器主界面左上角依次点击，工程 --> 更新已发布游戏 按钮。

  ![更新游戏](https://arkimg.ark.online/f9e623f3-5e08-4bac-9b7c-98cf1157e202.webp)

- 在弹出的界面中选中要更新的游戏，这里我选择“口袋方舟启动!”这个项目，然后点击下一步按钮。

  ![选中更新游戏](https://arkimg.ark.online/237e62f8-e86d-4f97-9db3-ed2950122f37.webp)

- 填写更新内容，请注意这里要如实填写本次更新/修改的内容否则有可能无法通过审核。填写完毕后点击“更新”按钮，就可以将游戏新版本内容上传到线上了。

  ![更新内容](https://arkimg.ark.online/c7a47573-9467-4b12-8d8e-43cf5f798a39.webp)

- 接下来就是在口袋方舟开发者后台填写素材等步骤了。在信息填写无误后点击审核，等待上线即可。当游戏上线后游戏的版本号会自动往后顺延，创作者可以根据版本号来定位一些信息（如报错日志中可以根据版本号确定问题是否已经被修复）。

  这里要注意的是，口袋方舟在游戏版本更新时并不会强制停止服务器，也就是说游戏更新时已经在房间中的玩家不会受到影响，只有当他们退出游戏重新进入时才会分配到新版本游戏中。

  
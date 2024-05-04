# 关于BBtag
Discord上名为Blargbot的机器人提供了一套仿脚本语言BBtag，它允许你在不学习任何编程语言的情况下开发自己需要的面向Discord服务器的自定义功能。最重要的是，你不需要支付任何资金来开发或使用BBtag，因为Blargbot的开发者维护着一个免费公开的官方托管实例。

# 关于本项目
## 项目功能
本项目允许用户对自己的Discord账号进行多个体的信息管理，这些信息包括关联账号、个人简介、成员头像等。这很好地满足了多意识体系统的需求。同时，它能够根据这些数据实现多账号同步Ban、生日提醒、信息展示等功能。
> [!NOTE]
> 本项目所存储、编辑、调用的个人数据均存储在Blargbot官方实例服务器上，它不具备修改你的Discord账号数据的能力。

## 项目开发进度
本项目开发尚未完成，早期版本中尚**不能完整实现上述功能。**
- [x] 新用户引导功能
- [x] Profile初始化功能
- [ ] 指令行模块功能
- [ ] 系统文本资料创建、编辑、查看功能
- [ ] 个体文本资料创建、编辑、查看功能
- [ ] 头像、横幅功能
- [ ] 扩展功能区
     - [ ] 管理辅助功能
     - [ ] 生日提醒功能
     - [ ] TAG功能
     - [ ] 货币功能
     
## 安装指南
> [!IMPORTANT]
> 为了邀请BOT至你的服务器，你必须拥有待安装Discord服务器的管理员权限。（即`管理服务器`权限）
安装本项目的要求非常简单，请遵循以下步骤：
1.登录你的Discord账号，[邀请Blargbot](https://blargbot.xyz/invite)到你的服务器。为了保证本项目正常运行，建议使用完整邀请，或给予Blargbot可允许范围内的最大权限。
2.在服务器内的任意频道键入(Blargbot必须拥有访问权限和查看消息权限)
```
b!ccommand install <code–URL>
```
其中`<Code–URL>`是本项目源码json文件的链接地址，你可以在release界面中找到。***不应当使用仓库中未格式化的txt源码文件，这会引发错误。***
3. 在BOT提示的界面中确认安装，即可完成安装流程。
4. 额外地，你还可以使用
```
b!ccommand set profile <code>
```
直接编辑profile命令来实现安装目的。其中`<code>`是仓库中txt源码文件的内容。

## 使用指南
在任意频道输入.profile启用本项目。

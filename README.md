**中文｜[English](https://github.com/exthmui/official_devices/blob/master/README_EN.md)**

这里是我们的官方机型仓库: [exTHmUI-devices
](https://github.com/exthmui-devices)
## 如何成为 exTHmUI 官方维护者
你首先需要满足以下条件，任何不满足以下条件的人都无法通过申请：

1. 您必须能够熟练的使用 Git（如cherry-pick、merge、rebase等）
2. 您必须持有您维护的设备
3. 您必须编译一个非官方版本的 exTHmUI 至少半个月以上，并保证该版本稳定
4. 在我们已经开发完成的版本中，您的 SELinux 状态必须为 Enforcing
5. 如您想要移植官方 ROM 中的特性，您必须保证功能使用正常，例如 MIUI 相机、米音
6. 如果厂商官方版本启用了强制加密，您也必须在 exTHmUI 中启用
7. 您的设备树和相应依赖必须 push 到 [exTHmUI-Devices](https://github.com/exthmui-devices)
8. 您的设备树 commit 必须规范，我们不需要 Buildbot
9. 内核禁止使用unwanted file blocker

如果您认为自己符合要求，您可以通过以下几种方式进行申请
1. 您在 exTHmUI 官方 QQ / Telegram 交流群中私聊管理进行申请
2. 在此仓库发起 issues 申请

## 如何成为 exTHmUI 社区维护者
如果您认为自己不满足成为官方维护者的条件，则您可以申请成为社区维护者

1. 您必须持有您维护的设备
2. 社区维护版本不要求您的 commit 完全规范，但不可出现以下行为
- 不保留历史提交
- 不保留原 commit 作者信息
3. 社区维护版本不做 SELinux 要求
4. 不能有影响使用的 bug
5. 内核禁止使用unwanted file blocker

如果您认为自己符合要求，您可以通过以下几种方式进行申请
1. 您在 exTHmUI 官方 QQ / Telegram 交流群中私聊管理进行申请
2. 在此仓库发起 issues 申请
